---
layout: post
title: "ACBR Comic Book Reader: Version 3.19.0 Now Available"
categories:
- software
- acbr
---

<p>Changelog:</p>
<ul>
<li>Improved, significantly, the average page loading time in the Reader by implementing a pages cache that is filled in the background. The cache size can be increased in the Preferences (Comic Book Reader &gt; Pages Cache), so it can fit more pages if the user doesn't mind the extra RAM usage.</li>
<li>Added the option to create new page filters for the Reader (go to View &gt; Filter &gt; Manage Filters, or to the Comic Book Reader section in the Preferences), that can be customized by setting values for gamma, white level, black level, brightness, contrast, sepia and saturation.</li>
<li>Added a new advanced image operation, black level / white level, to the convert, create and extract comic books tools.</li>
<li>Added a button, shortcut and menu entry to take a screenshot of a video in the Media Player while it's playing.</li>
<li>Added a new Preferences option to set the System Monitor size in the Appearance section.</li>
<li>Rebuilt one of the libraries' Linux binary so it requires glibc 2.35 instead of 2.38 to run it, making the non-flatpak Linux versions of ACBR now, hopefully, compatible with older Linux distros like Ubuntu 22.04.</li>
<li>Made some changes to the conversion tools to try to avoid potential EBUSY errors on Windows.</li>
<li>Updated some of the core libraries to newer versions.</li>
<li>Fixed not being able to open the metadata in the comicinfo.xml of a CBR file.</li>
</ul>
