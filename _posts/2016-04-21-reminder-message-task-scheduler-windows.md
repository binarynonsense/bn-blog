---
layout: post
title: "Displaying a Reminder Message Every Hour Using the Task Scheduler (Windows)"
categories:
- windows
---

Today I wanted my Windows 10 machine to display a message every hour during part of the day (only on weekdays) reminding me to take a break from the computer. I ended up using Windows' Task Scheduler as some websites suggested and a .vbs script to do it, and it seems to work as I wanted. In case someday I need to remember how I did it or someone needs to do something similar I'll put here some screenshots, the simple code of the script (it is called by the scheduler and just shows a message box with some text) and the links to a couple of websites where I found useful information.


![screenshot]({{ site.baseurl }}/images/posts/windows_reminder_01.jpg)


![screenshot]({{ site.baseurl }}/images/posts/windows_reminder_02.jpg)


![screenshot]({{ site.baseurl }}/images/posts/windows_reminder_03.jpg)


The script:

{% highlight vbnet %}
MsgBox "Time to take a break!!!", vbSystemModal
{% endhighlight %}

References:

* <a href="http://www.howtogeek.com/136894/how-to-create-popup-reminders-with-no-additional-software/?PageSpeed=noscript">howtogeek.com</a>
* <a href="http://www.sevenforums.com/tutorials/211758-task-scheduler-create-task-display-message-reminder.html">sevenforums.com</a>

