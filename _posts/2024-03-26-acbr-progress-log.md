---
layout: post
title: "ACBR Comic Book Reader: Version 3.4.0 Now Available"
categories:
- software
- acbr
---

<p>Changelog:</p>
<ul><li>Updated some of the core libraries to newer versions.
</li><li>Added support for converting and extracting CBR files bigger than 2GB.
</li><li>Added support for converting, extracting and creating CBZ files bigger than 2GB.
</li><li>Added support for reading CBR and CBZ files bigger than 2GB.
</li><li>Added the option to remap the reader's navigation keys in the preferences.
</li><li>Improved temporary folders creation and cleanup.
</li><li>Added F2 as a shortcut to show the current file's properties in the reader.
</li><li>Added options to change the quality parameter used when encoding  each type of image file format to the advanced section of some tools and  removed the generic image quality one.
</li><li>Added an option to enable mozjpeg when encoding JPGs to the advanced section of some tools.
</li><li>Changed how the comics conversion tool treats input files with  multiple folders. It now preserves the original folder structure  whenever possible, hopefully avoiding the chance of having output files  with out of order or missing pages in some specific situations.
</li><li>Made running more than one instance of the app at the same time not  possible. This is needed to prevent problems with the temp folder,  settings and history management.
</li><li>Increased the minor version number to 4, given the amount of changes  and fixes already accumulated during the latest betas, making this new  release v3.4.0 instead of the initially planned v3.3.3.
</li><li>Fixed PDF files with a path containing the hashtag character (#) not working.
</li><li>Fixed not being able to drag and drop input files into the extract tool like in similar tools.
</li><li>Fixed malformed settings file not being handled properly.
</li><li>Fixed last fullscreen state not being correctly saved in the settings some times.
</li><li>Fixed the conversion tool's cancel button not working correctly in some cases.</li></ul>
