---
layout: post
title: City Project - Work in progress video 52: New sound manager (using OpenAL)
categories:
- gamedev
- city-project
---

I've created a simple sound manager using <a href="http://connect.creativelabs.com/openal/default.aspx">OpenAL</a> (previously, I was using DirectSound/DirectMusic). Now, when a sound asks the manager to be played, a preallocated pool of channels (OpenAL sources) is checked to see if there's one available, in which case, the sound will use it. The manager is not finished, I've yet to implement priorities so a sound using a channel can be stopped to give it to a new one with more priority that needs to be played, but it's already usable:<br /><br /><div style="text-align: center;"><iframe height="367" src="http://www.youtube.com/embed/nyB8KKU00-k" width="600"></iframe></div>