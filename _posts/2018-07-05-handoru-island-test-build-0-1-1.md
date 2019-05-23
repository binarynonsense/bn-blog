---
layout: post
title: "Handoru Island: Test Build 0.1.1 Now Available"
categories:
- gamedev
- handoru-island
---

<p>A minor update to add a few bug fixes and changes:</p>
<ul><li>Created a blurred rotor texture to use when the heli is flying to avoid the <a href="https://en.wikipedia.org/wiki/Wagon-wheel_effect" target="_blank">Wagon-wheel effect</a>.</li><li>(FIX) The interface of the shops now works with a gamepad.</li><li>Increased the range of the player vehicles' headlights.</li><li>Interiors: increased the ambient light, they were too dark at times.</li><li>Worked on the pedestrian's reactions after getting hit: for slow/minor collisions they just yell and jump a little but if run over they fall down, the player gets a  traffic warning (or ticket if keeps doing it too soon) and they get up afterwards (needs more testing, I could have introduced some animation bugs).</li><li>Interiors: made some of the interactive objects (doors, console, chess, computer...) blink so it's more obvious what you can interact with.</li><li>Dynamic objects: added more things you can collide and 'break' or move if you hit them hard enough: traffic signs, mail boxes and fire hydrants.</li><li>Weather: adjusted the time a storm lasts (needs some more testing, I'm trying to make the a little shorter).</li><li>(FIX) You were able to park a trailer outside of the marked area while barely touching one of the lines, hopefully that's now fixed (needs more testing).</li><li>Made an easy (bigger) version of the marked area to park the trailer for "easy difficulty" trailer jobs. The first couple of test jobs use that, so the players get used to how things work and don't get frustrated if they are not good at parking at first.</li><li>Tweaked the input for the vehicles using a curve to change how fast the steering angle changes depending on the current angle, making it slower at the start and end. Not sure if it's even noticeable but the goal is to make it harder to lose control at normal speeds, avoiding some of the <span class="st">brusque movements that could happen</span>, especially with a gamepad (somehow I like how they handle with the keyboard more, but should work the same), although I still want them to be harder to control if you speed up too much.</li></ul>
<div class="iframe-container">
<iframe allowfullscreen src="//www.youtube.com/embed/9J9Ee4Z0pDM"></iframe>
</div>
