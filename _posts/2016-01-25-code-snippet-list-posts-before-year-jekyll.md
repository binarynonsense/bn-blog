---
layout: post
title: "Code Snippet: List posts published before a given year in Jekyll"
categories:
- code-snippets
- jekyll
---

{% highlight liquid %}
{% raw %}
<ul>
    {% for post in site.posts %}
    {% capture year %}{{post.date | date: "%Y"}}{% endcapture %}
        {% if year < "2014" %}
        <li><span>{{ post.date | date_to_string }} &raquo;</span><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
        {% endif %}
    {% endfor %}
</ul>
{% endraw %}
{% endhighlight %}