---
layout: post
title: "ACBR Comic Book Reader: Version 3.18.0 Now Available"
categories:
- software
- acbr
---

<p>Changelog:</p>
<ul><li>Overhauled the audio player and made it a media player. It now also  plays video files (supports web-compatible codecs and formats like MP4  and WebM) and youtube URLs and shows subtitles from SRT files. If FFmpeg  is installed and in the system&#x27;s PATH, or its path is configured in the  preferences, it will support many other containers and codecs (MKV,  AVI, WMV, H.265...), multiple video and audio tracks and embedded  subtitles.
</li><li>Added a section in the Preferences, Third-Party Executables, to configure the paths for optional executables like rar or ffmpeg.
</li><li>Added a new localization file, Japanese, contributed by coolvitto.
</li><li>Added some improvements to the deletion and move operations to make  them more resiliant against potential short external locks by OneDrive  or similar external programs of the temporary files and folders created  during conversions.
</li><li>Set a better default temp folder for the flatpak version.
</li><li>Fixed the flatpak version not finding the rar binary in the system&#x27;s PATH (if available).
</li></ul>
