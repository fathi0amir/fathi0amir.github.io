---
layout: post
title: Create Fixed Length String from the LabVIEW Controls' Label and Value
---

For the programs I wrote, I wanted to save all the controls values and theirs labels 
along with some remarks on the experiments to a text file. This file could be used 
later to reproduce the same result or report the used parameters. 
![String from labels and values](https://raw.githubusercontent.com/fathi0amir/lv-save-control-to-text/main/SaveControlsToText.png) 

To do it nicely, 
I get the reference of the controls I need to track, then pass it to a subvi 
that can find the data type of the referenced control. Using this information, 
another deeper subvi will infer the control's label and uses correct 
data type do a string-conversion. The strings are used then to make nicely 
formatted table as a fixed length ASCII string. This can be then saved 
to disk as a txt file. All the necessary files can be found [here](https://github.com/fathi0amir/lv-save-control-to-text)