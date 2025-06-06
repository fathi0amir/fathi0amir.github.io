---
layout: post
title: Intensity Calibration of HR4000 Without Using a Calibration Lamp
---
![Calibrated Spectrum](https://github.com/fathi0amir/fathi0amir.github.io/blob/master/images/HR4000_Calibrated_Spectrum.svg?raw=true)

## Spectral Response

The data is digitized from the datasheet of Hamamatsu S15351 CCD QE curve. 
It is then converted to spectral responsivity by taking into photon energy and 
pixel size of Toshiba TCD1304 in HR4000 spectrometer. The pixel size is 8 x 200 µm.
Sample curve is shown below.
![Spectral Response](https://github.com/fathi0amir/fathi0amir.github.io/blob/master/images/HR4000_QE_and_SR.svg?raw=true)

## Grating Efficiency

Digitized Grating Efficiency of 300 Lines/mm 300 nm Grating from Edmund Optics is shown below.
![Grating Efficiency](https://github.com/fathi0amir/fathi0amir.github.io/blob/master/images/HR4000_Grating_Efficiency.svg?raw=true)

## Calibration Curve

Calibration curve is obtained by normalizing the spectral response and grating efficiency and multiplying them together.
![Calibration Curve](https://github.com/fathi0amir/fathi0amir.github.io/blob/master/images/HR4000_Calibration_Curve.svg?raw=true)

## Calibrated Spectrum Vs. Calibrated Spectrometer Data

On the top of the page I compared the raw data from HR4000 spectrometer with the calibrated spectrum and with data from BWTek Spectrometer (Calibrated with a calibration lamp).
The spectrum is from broadened 1030 nm femtosecond laser pulse.


I have uploaded a reproducible quarto document in [GitHub Repository](https://github.com/fathi0amir/HR4000_Calibration)

Still, using a calibration lamp is the best way to calibrate the spectrometer, but this
method can be used to get a rough estimate of the calibration curve without using a calibration lamp.
From the above comparison, it is clear that the calibrated spectrum is not as accurate as the one obtained with a calibration lamp, but it is still better than the raw data from the spectrometer.
