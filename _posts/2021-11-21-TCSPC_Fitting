---
layout: post
title: Fitting TCSPC data in MatLab
---

I put together a small example of a typical TCSPC measurement. I used PicoHarp 300 from Picoquant. 
Great system but you are limited to their fitting software which can be something you not really looking for. 
Of course it can fit typical summation of exponential functions but if your fitting model is specific you might 
want to do this in MatLab or some other environement. Picoquant made availabe an script that can load picoquant 
proprietory files in MatLab. From Matlab you have unlimited freedom to deal with your data they way you want.

[This](https://github.com/fathi0amir/TCSPC_Data_Fitting) zip file includes the scripts, 
the fitting models, raw data, processed data and a final figure. I hope they can come handy to 
others as well as a starting point. Included, you can find the raw and processed data as "mat" files. 
If you follow the "Fiiting_TCSPC.m" script you should be able to 
get the included final figure of the fitted data results and a same values in the "processed_data.mat" file. 

Briefly, 
1. load the data
2. crop the meaningful data from the raw TCSPC file
3. remove NAN there if there are any
4. load the intrument response function (IRF) data. 
5. fit it to the model included in the script. This done so we get a clean noise-free IRF
6. Use the included models or write your own funciton file and check which one is more appropriate
7. start fitting and double check the result from the plot after it's done
