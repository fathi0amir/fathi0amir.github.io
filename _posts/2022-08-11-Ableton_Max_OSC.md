---
layout: post
title: Control Ableton Live with OSC through Max for Live
---

One can't imageing to what extent a bored man can go! To prove this I always wanted 
to control my Ableton Live set with my iPad. I wanted to have full control. I started with 
TouchOSC but I found it very limiting. They I saw "TouchAble" and "LK". "LK" looks like a 
great piece of work with an active maintanance. So I bought that. Then before actually making 
any music I thought wouldn't it be cool if I could make my own control surface! Well it is very
very cool. I also always wanted to learn Max so I found this a good opportunity to learn and 
build something that I can use along with LK. 

Max for Live has a series of objects under the name Live Object Model (LOM). This allows 
Max to access every part of the Ableton Live. I start reading the manuals and watching some 
introductory videos on YouTube. After struggling a bit here and there mostly on the way 
Max represent and handle strings I succeeded to control Ableton with OSC. 

In (this)[https://github.com/fathi0amir/Ableton_Max_OSC] I put all the necessary files that 
you need to get started if you are curious, or just bored like me. 
Open the Live set, load the max device in any track and then run Open Stage Control. 
When you open the Live set there are only two tracks with only the first clips being loaded. 
After adding the Max device you can open it in Max and see how things are done. For this 
I prepared the file to only control the first clip of the first track. It is also 
very straightforward to add or modify the device if you wich to do so. The next step is 
to download (OpenStageControl)[https://openstagecontrol.ammd.net/] and set the send and 
recieve ports as the ones in the Max device. After running the Open Stage Control you 
should be able to load the "json" file in the repository with the stop, play and clip progress knob 
that corresponds to the first clip in the frist track. 

I hope this will be of any help for people out there. It was a great fun tot do this and I am going 
expand on this in my spare time. I will also try to upload and update this blog when I have more 
comprehensive version. 

I do need to mentions the following tutorial that helped me to be able to get this far: 
- https://youtu.be/bupVHvMEAz0
- https://youtu.be/yLpvJho5hQA
- https://youtu.be/qeabaagMZr8

Thanks to all of them to their great videos.
