---
layout: post
title: "ACBR Comic Book Reader: Version 2.4.5 Now Available"
categories:
- software
- acbr
---

<p>Changelog:</p>
<ul><li>Added support for ComicInfo.xml files in the comic books converter.  If the original contains a ComicBook.xml file and the output format  allows it, the file is now preserved and even updated if the pages were  changed in format or scale (previously this xml file was ignored and not  included in the output comic file).
</li><li>Switched to a custom epub generator, instead of the third-party  library used so far, to be able to focus only on those features needed  to create comic book files and add some new options.
</li><li>Added a new section to the Advanced options of the comic book  conversion tool to allow creating epubs with the images embedded as  base64 in the html and limiting the image formats to only those allowed  by the specification.
</li><li>Added an option to the preferences, disabled by default, to  automatically turn the page when a scroll boundary is reached (i.e. if  you keep scrolling after reaching the top/bottom of the page the  previous/next page will be loaded).
</li></ul>

