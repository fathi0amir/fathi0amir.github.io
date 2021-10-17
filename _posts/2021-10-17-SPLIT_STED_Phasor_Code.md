---
layout: post
title: Phasor Analysis to Improve Resolution Enhancement in STED with Less Laser Power
---

STED is a well-known technique to achieve sub-diffraction resolution in 
fluorescent microscopy. This technique along with two other techniques 
recieved the noble prize in 2014. On chanllenge in STED is the second 
intense laser beam to deplete the excited state. One workaround to 
overcome this to some extend was publish [here](https://doi.org/10.1038/ncomms7701). 

During my PhD I was working on a super-resolution project. I thought I could used 
this approach to improve my resolution enhancement even further. Althoug it didn't 
really workout well for me I thought I leave this code here in case it comes handy 
for othere. In all honesty, this code was made to replicate the results in the 
afformentioned article. A similar plugin can be also found for imagej [here](http://www.spechron.com/Spectral%20Phasor-Download.aspx).
Although the imagej plugin (in java) is not as easy as matlab to modify I find 
it a great starting point for anyone trying a phasor approach. please head to 
[this](https://github.com/fathi0amir/SPLIT_STED_Phasor_Code) repository for the 
matlab code. The file named Phasor_Simulation_1.4.m is file you should be 
able to run and get the results without hassle. When you run the file 
you will get three figures; a side by side comparison and 2D phasor plot and 
a 3D phasor plot. The zip file contains my other 
codes that resulted in the final version. 
