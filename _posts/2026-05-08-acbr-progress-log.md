---
layout: post
title: "ACBR Comic Book Reader: Version 3.21.0 Now Available"
categories:
- software
- acbr
---

<p>Changelog:</p>
<ul><li>Added a new command line flag, <a href="https://github.com/binarynonsense/comic-book-reader/wiki/Media-Player:-Launch-in-Stand-Alone-Mode" referrerpolicy="origin" rel="nofollow noopener">--player</a>,  that makes ACBR launch in &quot;Media Player Mode&quot;. In this mode the media  player runs as if it was a stand alone application, without the Reader&#x27;s  main window or other tools.<br>
 </li><li>Added a new command line flag, <a href="https://github.com/binarynonsense/comic-book-reader/wiki/Command%E2%80%90Line-Tools:-Launch-Options" referrerpolicy="origin" rel="nofollow noopener">--cli</a>,  that allows launching a text mode version of some of the tools  (&quot;Convert Comics&quot;, &quot;Extract Comics&quot; and &quot;Create Comic&quot;) that runs  directly through the command line rather than the graphical user  interface.
 </li><li>Fixed the RSS Reader showing the short summary instead of the full content for an RSS feed item if both are available.</li></ul>
<p>[Update] v3.21.1:<br></p>
<ul><li>Made feed items with both description and content data in the RSS  Reader start showing only the description and a expand/collapse button  to show/hide the content, so it&#x27;s easier to read and navigate them.<br>
 </li><li>Added Zona Negativa&#x27;s feed to the RSS Reader&#x27;s defaults.
 </li><li>Fixed the changelog formatting in the check for updates modal when there is a new version.
 </li><li>Fixed the Media Player&#x27;s subtitle rendering so tags (italics, bold...) are shown correctly.</li></ul>
<p>[Update] v3.21.2:
    </p>
<ul><li>Fixed the &quot;Create Comic&quot; tool duplicating pages in the output file when the input list consists only of images.</li></ul>
<p>[Update] v3.21.3:         <br></p>
<ul><li>Added more ways to manage the &quot;Convert Comics&quot;, &quot;Extract Comics&quot; and  &quot;Create Comic&quot; tools&#x27; input list. The &quot;Add Files&quot;, &quot;Add Folders&quot; and  &quot;Clear List&quot; buttons are now at the top of the list and when the list  grows bigger than 10 elements another set of the same buttons is placed  at its bottom. Also, when right-clicking inside the list, the context  menu now shows entries for those actions.<br>
 </li><li>Fixed setting the &quot;Convert Comics&quot; tool&#x27;s &quot;Input Folders Contain&quot;  advanced input option to &quot;The image files from a single comic book each&quot;  no longer working.</li></ul>
<p>[Update] v3.21.4:         
    <br></p>
<ul><li>Fixed EPUB, MOBI and PDF files not working correctly on the Windows  version of ACBR if the app is placed in a path containing spaces.<br>
 </li><li>Fixed images-only MOBIs not working.
 </li><li>Fixed images-only EPUBs that don&#x27;t store the image paths in img tags  not working, and improved the code for the already working ones.
</li></ul>
