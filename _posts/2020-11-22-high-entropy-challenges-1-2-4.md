---
layout: post
title: "High Entropy: Challenges - Version 1.2.4 Now Available"
categories:
- gamedev
- high-entropy
---

<p>This update adds a new batch of bug fixes and improvements, the most interesting probably being: the computers now have a help command with info about some basic commands, after reading an important document it's saved in the inventory and can be read again from there, a couple new setting options to help those with motion sickness, some adjustment to the enemies' hitboxes...</p>
<p>Here's the full changelog:</p>
<ul><li>Added a help command to the computers' OS that opens a GUI with a list of some basic commands and provides info about them.<br>    </li><li>When
 an important document, like the HEL OS manuals, is read it's now added 
to the inventory and can be accessed there to read it again.
    </li><li>Increased some of the bot's and turret's hitboxes' sizes and/or added extra ones.
    </li><li>Added
 an option to the settings&gt;gameplay menu to change the default 
climbing animation to a simpler one, to try to help some people with 
motion sickness.
    </li><li>Added an option to the 
settings&gt;gameplay menu to disable the running and jump landing camera
 head bobbing, to try to help some people with motion sickness.
    </li><li>Made
 the mines' hitbox bigger. Also, now their red laser tripwire reacts to 
any object, not only 'living' ones, so soda cans can make them explode, 
for example.
    </li><li>Changed the dialogue camera so it not 
longer zooms to the NPCs' face. Now I make them just look at you, it 
feels more natural and fitting to the idea of the helmet camera 
recording. I also disabled Dr Wells' procedural lip movement, it was a 
little weird and I won't probably be able to have the other models for 
the story have even that limited lip movement so I've decided to not 
animate them and see how it feels (I think it works ok despite not being
 realistic).
    </li><li>Changed the internal screenshot taker to 
save images as jpg and its default key to F11 so it isn't the same as 
the default one in Steam.
    </li><li>Made some changes to the empty
 crates' movement code and collision detection when grabbed,  to try to 
avoid cases where they could be pushed through places they shouldn't and
 other related glitches.
    </li><li>Moved the jump/climb tutorial's
 trigger in level 3 so it's not so close to the crane (it was easy to 
press e to pick the crane just when the tutorial appeared and close it).
    </li><li>The alarm's sound now decreases its volume with time, so it gets less annoying if you keep in its view.
    </li><li>Replaced
 the 'mail' command manual in level 5 with a new one that explains the 
'gui' command and hints at how, in general, the levels can be completed 
without using the command line (also placed a copy in level 8 in case 
the player doesn't read it in level 5).
    </li><li>FIXED: the 
command line interface was locking when attempting a telnet connection 
to a device already connected to another computer.
    </li><li>FIXED: the alarm's sound sometimes was not stopping when the camera that started it was disconnected remotely.
    </li><li>FIXED: grabbed objects are now dropped when entering a ladder.
    </li><li>FIXED: the exit sign in level 14 was floating in the air.</li></ul>
