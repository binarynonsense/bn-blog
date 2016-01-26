---
layout: post
title: "Code Snippet: List posts published before a given year in Jekyll"
categories:
- code-snippets
- jekyll
---

{% highlight html %}
{% raw %}
<ul>
    {% for post in site.posts %}
    {% capture year %}{{post.date | date: "%Y"}}{% endcapture %}
        {% if year < "2014" %}
        <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
        {% endif %}
    {% endfor %}
</ul>
{% endraw %}
{% endhighlight %}