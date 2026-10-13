---
layout: post
title: "ACBR Comic Book Reader: Version 3.25.0 Now Available"
categories:
- software
- acbr
---

<p>Changelog:</p>
---
layout: post
title: "ACBR Comic Book Reader: Version 3.26.0 Now Available"
categories:
- software
- acbr
---

<p>Changelog:</p>
<ul><li>Added support for Komga and Kavita media servers. The menu &quot;Servers 
&gt; Server Browser&quot; now opens a tool to connect to, browse and open 
books from them.</li><li>Added more advanced PNG image options to the conversion tools and a 
new output toggle to make more clear when the advanced image options are
 going to be applied or not, being now able to force them to be applied 
even when a 100% scale is set and &quot;Keep original&quot; is selected as image 
format (by default, the original untouched images were always used in 
this case, if possible, with no option to override it).</li><li>Added a private mode that can be enabled from &quot;File &gt; Private 
Mode&quot; that makes the file history and reading progress not be updated 
during that session while it&#x27;s on.</li><li>Fixed the advanced image processing options not applying when the 
output image format was set to &quot;Keep original&quot; in the conversion tools.</li></ul>
<p>[Update] v3.26.1:</p>
<ul><li>Fixed the flatpak build failing to encrypt credentials and add servers 
to the saved list in the Server Browser. A change in the way the 
credentials are encrypted and decrypted was needed. Besides fixing the 
problem this new method has better long term support but, sadly, it also
 means that any server saved with the previous version of ACBR will need
 to be deleted from the list and saved again if a Linux build was used 
(the Windows build seems to be compatible).</li></ul>
<p>[Update] v3.26.2:</p>
<ul><li>Fixed not being able to browse a server in the Server Browser if a 
connection with it was already established from the reader to open a 
book from the history and it is still the current one.</li></ul><p>[Update] v3.26.3:</p><ul><li>Fixed a bug introduced in the previous release that made switching 
between servers not work in the Server Browser under some circumstances.</li></ul>

