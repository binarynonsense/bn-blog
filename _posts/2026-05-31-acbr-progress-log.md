---
layout: post
title: "ACBR Comic Book Reader: Version 3.22.0 Now Available"
categories:
- software
- acbr
---

<p>Changelog:</p>
<ul><li>Added a new zoom mode to the Reader, &quot;Fit to Both&quot;, to fit the page/s to the width and height of the viewable area.<br>
 </li><li>Expanded the &quot;Automatic Page Turn&quot; setting in the &quot;Comic Book Reader  &gt; Navigation&quot; subsection of the Preferences. Now, when selecting the  &quot;On scroll boundaries&quot; option, some time values can be changed to  customize its behavior.
 </li><li>Made scrolling the pages using the keyboard smoother on key presses,  instead of instant, and more precise if you keep holding down.
 </li><li>Added more advanced options to the &quot;Convert Images&quot; tool.
 </li><li>Increased the timeout for the Project Gutenberg search tool and  added a cancel button, as the website it relies on can be quite slow to  respond lately.
 </li><li>Updated the Flatpak version&#x27;s runtime to 25.08.
 </li><li>Updated the image processing library, sharp, to a newer version.
 </li><li>Refactored all the image operations&#x27; code to avoid crashes due to  glib conflicts caused by the new runtime and image library updates.
 </li><li>Fixed books with broken image files getting stuck trying to load the error page image due to a path change in a recent update.
 </li><li>Fixed the test images used by some tools showing as broken due to a path change in a recent update.
</li></ul>
