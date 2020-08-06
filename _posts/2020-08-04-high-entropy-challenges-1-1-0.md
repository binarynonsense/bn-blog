---
layout: post
title: "High Entropy: Challenges - Version 1.1 Now Available"
categories:
- gamedev
- high-entropy
---

<p>This update adds some improvements based on the feedback I received for the previous version and a few tweaks and fixes.</p>
<h4><br>Changelog:</h4>
<ul><li>Updated the engine (Unity) to version 2019.4.6f1 LTS.</li><li>Created custom icon.</li><li>Remade the damage and detection indicators to make them less blurry.</li><li>Made the bot's death by explosion more dramatic.</li><li>Updated the enemy sound detection tutorial text in level 4, to try to explain the NPCs response to sounds a little better.</li><li>Added screen mode option to the settings: full, full (windowed) or windowed</li><li>When soda cans break a window now enemies are alerted as if the player had broken it directly (which means they'll rotate to look at the source of the sound).</li><li>Added collision sounds to the bot's ragdoll.</li><li>Level 7: moved the bot's position a little.</li><li>Changed the way laser tripwires are turned on and off, it was creating some confusion because turrets turned them back on when deactivating even when players had turned them off.</li><li>Turrets now change targets if the original hasn't been seen for a few seconds and there's another one in sight.</li><li>FIXED: being shot while using a computer could leave the player in a weird state in some cases (hud still in computer mode, camera in weird angle and computer still running). There may be still some corner cases left to fix.</li><li>FIXED: player could climb over NPCs.</li><li>FIXED: the death sound for the walking turrets' legs had been accidentally disabled.</li><li>FIXED: turrets could detect enemies while turning off (could leave it that way, but seems more intuitive not to).</li><li>FIXED: dead walking turrets' legs could block the path for other NPCs.</li></ul>
