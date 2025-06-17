---
layout: post
title: "Update 1.4 - High Entropy: Challenges"
categories:
  - gamedev
  - high-entropy
---

<div>
<p>The main feature this update adds is gamepad support. The game can now be played using one and all the controls, prompts, menus and user interfaces in general have been adapted for that type of input device, including the in-game computers, that will show a virtual keyboard as part of their GUI in the command line interface to be able to enter commands.</p>
<p>
<span><img src="https://clan.fastly.steamstatic.com/images//38478693/c29d67a6711320ce7bc3c19fa37c2595ef74fa01.jpg"></span>
</p>

<p>It's been a bit of work as originally, due to my lack of experience playing with controllers, especially FPS games, and the fact that the in-game computers required being able to type commands, I didn't give it much thought and decided the game would be keyboard and mouse only, so I didn't build things with gamepad in mind. But the last couple of years I've been playing mostly on my Steam Deck so I recently  decided to give it a try and implement gamepad support and a custom virtual keyboard and see how it felt... and I'm pretty happy with the results, hope you feel the same (and that I haven't broken anything / added new bugs :)).</p>
<p>
<span><img src="https://clan.fastly.steamstatic.com/images//38478693/fbef9112b8e3a909d7f1cea47fc383f4f73cbc3b.jpg"></span>
</p>
<p></p>
<p>I've also included a bunch of new configuration options, some gamepad specific (dead zones, sensitivity curves, buttons mapping...) and others related to accessibility (image brightness and gamma correction, UIs scaling, toggle/hold options for running and aiming, separate audio levels for SFX and UI sounds...).</p>
<p></p>
<p>Hope you like it!</p>
<p>Álvaro</p>
<p></p>
<p>P.S.: I've added custom button prompts for Xbox, Dualshock and Steam Deck controllers but I have only tested the game with an Xbox 360 controller and the Steam Deck, as I don't own a more modern Xbox or Dualshock one and they are too expensive for me to buy just for testing so, although the correct ones should show depending on the type of controller, I haven't been able to test all possibilities with real hardware.</p>
</div>
