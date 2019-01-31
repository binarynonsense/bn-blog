---
layout: post
title: "Command Line Tips: Download All the PDF Files Linked on a Webpage and Merge them Together (GNU/Linux)"
categories:
- command-line-tips
- gnu-linux
---

Today I wanted to download a free ebook available on <a href="http://www.gameaipro.com/">gameaipro.com</a>. The page contains a list of links to PDF files, one for each chapter, so I wanted to download them all and merge them. To download the files I used wget (I limit the download speed using --limit-rate, if you don't want to do it just delete that last part):

{% highlight bash %}
wget -r -A.pdf  http://www.gameaipro.com/ -c --limit-rate=150k
{% endhighlight %}

And to merge them together I used:

{% highlight bash %}
pdfunite *.pdf out.pdf
{% endhighlight %}