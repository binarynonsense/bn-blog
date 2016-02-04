---
layout: post
title: "Code Snippet: Animated Loading Screen in Unity"
categories:
- code-snippets
- unity
---


![screenshot]({{ site.baseurl }}/images/posts/snippet_loading.gif)


{% highlight c# %}
{% raw %}
using UnityEngine;
using System.Collections;
using UnityEngine.UI;

public class GUILoading : MonoBehaviour
{
    public Text m_text;
    public RectTransform m_circle;
    public Text m_precentageText;

    float m_circleAngle = 0;

    void Update ()
    {
        m_circleAngle = - 360 * Time.unscaledDeltaTime;
        m_circle.Rotate(new Vector3(0, 0, 1), m_circleAngle);
    }
} 
{% endraw %}
{% endhighlight %}


{% highlight c# %}
{% raw %}
...

GUILoading m_guiLoading;
float m_loadProgress;

public void LoadScene(string sceneName)
{
    StartCoroutine(LoadSceneAsync(sceneName));
}

IEnumerator LoadSceneAsync(string sceneName)
{
    m_guiLoading.gameObject.SetActive(true);
    Application.backgroundLoadingPriority = ThreadPriority.Low;
    AsyncOperation async = Application.LoadLevelAsync(sceneName);
    while (!async.isDone)
    {
        m_loadProgress = (int)(async.progress * 100);
        m_guiLoading.m_precentageText.text = m_loadProgress + "%";
        yield return null;
    }
}

...
{% endraw %}
{% endhighlight %}