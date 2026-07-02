---
layout: post
title: "ACBR Comic Book Reader: Version 3.25.0 Now Available"
categories:
- software
- acbr
---

<p>Changelog:</p>
<ul>
<li>Updated Electron to a newer version. This should bring full Wayland support to the Linux builds and, hopefully, help fix the previous version not working in some systems running Wayland, especially the flatpak build, due to a combination of the version I was using, me forcing X11 due to that Electron version not fully supporting Wayland, and some changes I made to the flatpak manifest.</li>
<li>Changed "Add Folders" to "Add Folder" in the conversion tools in the Linux builds as a needed compromise, due to the new Electron version not allowing multiselection in folder dialogs on that OS. Drag and dropping multiple folders into the input list still works as a way to add more that one at once.</li>
<li>The Home Screen folder favorites now open when clicked in the app's custom file browser instead of using a file dialog on Linux, due to new limitations in how the new Electron version handles dialogs in that OS.</li>
<li>Removed YouTube URLs support in the Media Player, at least for now, as it no longer works due to new header restrictions in the new version of Electron.</li>
</ul>
