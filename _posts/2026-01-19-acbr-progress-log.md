---
layout: post
title: "ACBR Comic Book Reader: Version 3.15.0 Now Available"
categories:
- software
- acbr
---

<p>Changelog:</p>
<ul>
<li>Increased, significantly, the speed of conversions that require image processing (scale, change image format...) in the "Convert Comic Books" tool by piping all the image processing operations for a page together, instead of doing them in stages as before, and also using worker threads to work on multiple pages at once. There are now advanced options to fine tune some parameters of this new method, which is now the default, in the tool's settings section (or to select the old method, which has the new operation piping but doesn't use worker threads, just in case it works better in some cases).</li>
<li>Added the total time the conversion took to the end of the log in the "Convert Comic Books" tool.</li>
<li>Added advanced image operations to crop and add borders in the "Convert Comic Books" tool.</li>
<li>Added an advanced input option, "Input Folders Contain", in the "Convert Comic Books" tool to select how to treat the contents of folders in the input list: either look for comic book files inside them (as up to now) or for images (that will be treated as the contents of a single comic book). With this second option, it's now possible to batch convert folders containing images into comic book files.</li>
<li>Added an advanced output option, "Keep Subfolders Structure", in the "Convert Comic Books" tool to choose to keep the subfolder structure from folders in the input list when the advanced input option "Search Input Folders Recursively" is enabled and an output folder for all files has been selected in the output options. This will replicate the folder and subfolder structure from the folders in the input list in the selected output folder and place the converted files in the corresponding place.</li>
<li>Increased the default history capacity to 50 and made the "History" tool show the current number of entries vs the current capacity in the "Recent" section title.</li>
<li>Added small tags to the file icons in the "Home Screen" for known extensions and other small quality of life improvements.</li>
<li>Added a new section in the history file to remember files in the "Home Screen" lists but not in recent.</li>
<li>Fixed toast notification's close button's color in light color mode.</li>
<li>Fixed "Home Screen" breaking for rtl languages.</li>
<li>Fixed book in user list in "Home Screen" not opening if it wasn't in the recent history.</li>
<li>Fixed the final log being truncated in some of the tools if errors occurred.</li>
</ul>
