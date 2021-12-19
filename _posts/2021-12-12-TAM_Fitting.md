---
layout: post
title: Complex Temporal Profile Fitting in MatLab (Lifetime Mapping in Time-resolved Transient Absorption Microscope (TAM) Images)
---

I tried to put together a demo file and project to demonstrate the procedure to undergo to map the lifetime or amplitude or etc to 
transient absorption images. [The work](https://onlinelibrary.wiley.com/doi/abs/10.1002/anie.202008305) was published in July 2020
that helped to shed light on grain boundaries relaxation dynamics. 

The matlab file "TAM_Image_Proc_20200421.mlx" is the main code and I tried to comment it as much as I can 
for extra clarity. the fitting model that used in this project takes into acount two exponentials with 
rise feature, baseline, tail offset, cross-phase modulation (coherent artifact). All the the prameters can be 
set fixed or fitted. This code helped me to do large data processing like a snap and I hope it can 
helps others for their specific application somehow. 

All the codes, and demo files are available [here](https://github.com/fathi0amir/TAM_Image_Processing_Demo)

Additionally for reading, saving and showing tiff files I used the two following MatLab packages
- https://www.mathworks.com/matlabcentral/fileexchange/49768-view-image-stack-gui
- https://www.mathworks.com/matlabcentral/fileexchange/35684-multipage-tiff-stack
