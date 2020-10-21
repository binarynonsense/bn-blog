---
layout: post
title: "High Entropy: Challenges - Version 1.2.3 Now Available"
categories:
- gamedev
- high-entropy
---

<p>This update adds a bunch of bug fixes and improvements, the most important probably being a fix for a bug in the save system where, in some cases, if the player's windows username contained non-english characters the save file wasn't being created correctly. So, if your level unlocks and scores were not being saved and/or loaded before, hopefully it will now work.</p>
<p>Also loading and reloading levels from the menu is now slightly faster, there's a new settings' option to limit the frame rate...</p>
<p>Here's the full changelog: </p>
<ul><li>Added an option in the settings&gt;image menu to limit the maximum frame rate.    </li><li>Made loading and reloading levels from the menu a little faster by starting with the elevator doors already opened.    </li><li>Took out a couple of commands from the basic commands manual, they weren't essential and some people were overwhelmed by the amount of commands it listed.    </li><li>Moved a wall computer in level 14 so it can't be used through the tripwires.    </li><li>Added a tutorial for the medkit in level 6.    </li><li>FIXED: the save system was not working correctly in some cases where the player's windows username contained non-latin characters.    </li><li>FIXED:  the correct keys for opening the safes were not being used if they had been remapped (the default ones were used no matter what).    </li><li>FIXED: some sounds not using the master volume setting.    </li><li>FIXED: master volume saved setting not being applied at the start of the game in some cases.    </li><li>FIXED: seating again in the vr chair sometimes left the player looking in a weird direction.    </li><li>FIXED: small typos in documents.</li></ul>
