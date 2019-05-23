---
layout: post
title: "High Entropy: Test Build 0.1.1 Now Available"
categories:
- gamedev
- high-entropy
---

<p>This update adds 3 new challenge levels (8, 9 and 10). There are also some fixes, tweaks to the NPC enemy detection code (needs some more testing and probably adjustments), new gameplay elements like a scissor lift, ladders... here are some screenshots and the full changelog:</p>
<p><img src="https://img.itch.zone/aW1nLzE5ODc3MzQuanBn/original/RX8eij.jpg"><br></p>
<p><img src="https://img.itch.zone/aW1nLzE5ODc3MzUuanBn/original/nZkbEE.jpg"><br></p>
<p><img src="https://img.itch.zone/aW1nLzE5ODc3MzYuanBn/original/0qiugZ.jpg"><br></p>
<p><img src="https://img.itch.zone/aW1nLzE5ODc3MzkuanBn/original/uKl0Ky.jpg"><br></p>
<p>Changelog:</p>
<ul><li>Added 3 new challenges (8, 9 & 10).</li><li>Added an interactive scissor lift.</li><li>Sentry Turrets: modified to improve enemy detection (now it has a detection meter like the bots) and network access. Also, now when a turret is woken up it doesn't go to sleep on its own, it goes to scanning mode if the target is gone.</li><li>Challenge 4: some changes to adapt it to the new Turret's behaviour (my solution to get a 100% score needs now an extra step).</li><li>Redid the doors to make adding new variations easier in the future, hopefully didn't break anything (had to tweak all the doors in the levels and reenter some values).</li><li>Security cameras: rewrote part of the code and added a raycast check to make the player detection more accurate/realistic. Still a little janky in some extreme cases but good enough for now. Also, the alarm sound now propagates and NPCs can hear it.</li><li>Added player footstep sound&nbsp; propagation, a footstep plays a sound and now also checks a small area around it to for NPCs to alert, bigger when running.&nbsp; Moving while crouched makes no sound (needs some tweaking and testing, is it worth it?).</li><li>Added working ladders.</li><li>Added composite objective (you have to achieve at least one of the sub-objectives to be successful).</li><li>Added 'pickable' handwheels to use with the pipe's valve.</li><li>The tutorials' window can now be closed using 'E'.</li><li>FIXED: HELOS: if a disk was inserted before turning a computer on for the first time, it broke (the path was malformed and the prompt was &gt; instead of c:&gt; and dir and other commands gave an error).</li><li>FIXED: run key now does nothing when crouched.</li><li>FIXED: turret bullet tracers were broken at some point and weren't visible (I hadn't noticed until now), they work again.</li></ul>
