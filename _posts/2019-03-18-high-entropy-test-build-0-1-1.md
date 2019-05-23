---
layout: post
title: "High Entropy: Test Build 0.1.1 Now Available"
categories:
- gamedev
- high-entropy
---

<p>A bunch of fixes and improvements, some of them based on the feedback from the first build, including a progress save system for the challenges and some changes in the computers' operative system.<br></p>
<p>Changelog:</p>
<ul><li>Added a progress save system for the challenges.</li><li>Added an FOV slider to the graphics settings menu. Needs some testing, are the max and min values enough for everyone?</li><li>HELOS: Redesigned the telnet connection interface in the computers and changed the way the connection is closed to make it more intuitive and closer to the real thing.</li><li>HELOS: changed the prompt to make it shorter. You now need to use whoami to see the logged user.</li><li>Challenge 7: updated the instructions doc to show the specific door number.</li><li>Challenges: increased the font size of the hud objectives' text a little to improve readability at some resolutions (is it enough?).</li><li>The keyboard's numpad is now supported as input for the keypad panels.</li><li>Rewrote the HELOS manuals found in levels 5 and 7 to reflect the changes I've made.</li><li>Whenever possible, the prompted key to stop using an interactive object will now be E, although ESC will always work (for now, I've changed the document and panels UI to do so).</li><li>Added Left Ctrl as a secondary key for crouching.</li><li>Tutorials are not longer showed if the current level was already completed at least once.</li><li>Reduced the line jitter effect in the menus a little.</li><li>FIXED: HELOS, floppy content not being deleted after extraction, and path always resetting to c: after extracting disk...</li><li>FIXED: the window telling the player that was the last level in the build wasn't working correctly, at least some times, and there was no way to exit it (there was a pointer that could be null under some circumstances that I wasn't checking before using).</li></ul>
