---
layout: post
title: Detecting Cell Units (Neurons) and Their Activies
---

The past two years as my first postdoc project I started building a two photon microscope 
and virtual reality setup. The setup runs in a close loop so the animal behaviour can be 
mapped to its brain activity. To extract the neurons activities I ended up using CaImAn 
package in Matlab. To ease my pain and build a smooth pipeline for my application I 
build a script that calls CaImAn function in a certian order. The script starts 
with a popup that ask for user input for essential parameters and then ask for the 
image file. At the end, after the script finishes it will clean up the unncessary variables 
and save the rest for the user's reference as a ".mat" file in the same directory. 

[CaImAn](https://github.com/flatironinstitute/CaImAn-MATLAB) 
is a great work done by fine group of people. Please cite them and support them. 
For more details and learn about this package please visit their repository. 

I have put together [here](https://github.com/fathi0amir/Calcium_Imaging) 
my script and a striped down verstion of CaImAn with the hope 
that it might be of any assistance to anyone using CaImAn is a similar application. 

[Here](https://drive.google.com/file/d/1X2KKHsawJwGURE5jlL181OVath0NPnSu/view?usp=sharing)
is a test file for anyone to give it a try. One needs to only open and run "aaa_Extract_Calcium_Traces_04.m" 
which will promp for user input and the image file. 


