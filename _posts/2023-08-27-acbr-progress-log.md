---
layout: post
title: "ACBR Comic Book Reader: Version 3.2.0 Now Available"
categories:
- software
- acbr
---

<p>Changelog:</p>
<ul><li>Added an option in the preferences to enable using a third-party command-line application (<a href="https://www.win-rar.com/cmd-shell-mode.html?&L=0" rel="nofollow">rar</a> from WinRAR) to create and modify cbr files.
</li><li>Added the ability to search for and import comic book metadata from Comic Vine to the ComicInfo.xml editor. A <a href="https://comicvine.gamespot.com/api/" rel="nofollow">Comic Vine API key</a> is required for it to work.
</li><li>Added an option in the comic book conversion and creation tools to split the output into multiple files.
</li><li>Added an option in the comic book conversion and creation tools to  password protect the output files. Only available for some of the output  formats (cbz, cb7, pdf and cbr).
</li><li>Made the creation tool accept not only image files as input but also comic book files.
</li><li>Added an option in the preferences to save the temp folder path as relative.
</li><li>Added an option in the preferences to choose which PDF library is  used for reading, the oldest (quicker but less robust) or the newest  (slower but more robust).
</li><li>Fixed an error in the PDF creation code when using an advanced option other than the default one.
</li></ul>
<p></p>
<p>[UPDATE] v3.2.1:</p>
<p>Hotfix:
 </p>
<ul><li>Fixed error window showing after quitting in some cases.
</li></ul>
<p>[UPDATE] v3.2.2:</p>
<ul><li>Updated the documentation.
</li><li>Fixed some debug messages being logged as errors.
</li><li>All the language localization files are now up to date.
</li></ul>
<p>[UPDATE] v3.2.3:</p>
<p>Hotfix:
 </p>
<ul><li>Fixed error when clicking 'Toggle Full Screen' in the context menu.
</li><li>Fixed 'Zoom &gt; Increase', 'Zoom &gt; Decrease' and 'Zoom &gt; Reset' in the menu bar doing nothing
</li></ul>
<p>[UPDATE] v3.2.4:</p>
<ul><li>Removed the ellipses from the menu entries that no longer open a  dialog or separate window for additional information, and from some that  were using them incorrectly.
</li><li>Added context menus to all the tools.
</li></ul>
<p>[UPDATE] v3.2.5:</p>
<p>Hotfix:
 </p>
<ul><li>Fixed a crash at initialization when no configuration file was found.
</li></ul>
<p>[UPDATE] v3.2.6:</p>
<ul><li>Added Steam Deck and Gaming Mode detection so a better configuration  is now set by default when running in that mode on the Deck. Adding the  "--no-sandbox" command-line flag to the launch options is still needed  in Gaming Mode.
</li><li>Fixed the development mode being incorrectly detected under some circumstances.
</li><li>Fixed the image flickering while zooming in/out.
</li><li>Fixed the image being duplicated some times when zooming quickly.
</li><li>Fixed the reader's scrollbar moving to the top after coming back from a tool.</li></ul>
<p>[UPDATE] v3.2.7:</p>
<ul><li>Added a battery level indicator.
</li><li>Simplified the reader's gamepad controls layout (will expand it in the future).
</li><li>Fixed the delay between changing the page's image and resetting its position.</li></ul>
<p>[UPDATE] v3.2.8:</p>
<ul><li>Included the ability to drag and drop files into a tool so they are added to its input files list (if the tool has one).
</li><li>Drag and dropping multiple files into the program's icon now  initializes the program with the "convert comics" tool open and those  files added to the input files list (dropping only one file opens that  file in the reader, as in previous versions).
</li><li>Added command line arguments to directly open the provided file/s  with the reader or one of the tools, set some of that tool's options...  There's more info on <a href="https://github.com/binarynonsense/comic-book-reader/wiki">the wiki</a>.
</li><li>Improved the keyboard and gamepad page scrolling smoothness.
</li><li>Fixed the "show battery" menu entry not being disabled outside the reader.
</li></ul>
