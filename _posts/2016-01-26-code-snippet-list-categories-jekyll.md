---
layout: post
title: "Code Snippet: List categories alphabetically in Jekyll"
categories:
- code-snippets
- jekyll
---

{% highlight html %}
{% raw %}
{% assign sorted_categories= (site.categories | sort:0) %}
<ul>
{% for category in sorted_categories %}
<li><a href="">{{ category | first }}</a></li>
{% endfor %}
</ul>
{% endraw %}
{% endhighlight %}