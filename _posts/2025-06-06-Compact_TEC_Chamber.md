---
layout: post
title: Compact TEC Chamber to tight spectroscopy setup
---

![Rendered view of the fully assembled TEC chamber (front, back and exploded view)](https://github.com/fathi0amir/fathi0amir.github.io/blob/master/images/TEC_render-2.png?raw=true)

## TE-Cooling Chamber

This sample chamber is designed from scratch to serve the following purposes

- Be used in transmission and reflection mode
- keep the sample at -10&deg;C
- Keep the sample in vacuum
- Keep the sample at a presence of a certain gas

### Transmission and reflection

A large front window is used to measure emission in reflection mode. The back window
is used for excitation which is mostly limited by the TEC chip aperture.

### Temperature

Currently, the chamber can maintain -10&deg;C, but the large area of the chamber
can host a larger heat sink with larger fan which will allow for lower temperatures.

### Vacuum and Purging gas

The chamber has two inlet/outlet which can be used to either vacuum the chamber, purge with a
gas or keep a gas flow.

### Design intent

This chamber was designed with the following intentions

- Pancake design to fit the limited space
- Large area for dissipating heat and mounting heat sink

## Main Parts

- TEC chip (CH-109-1.4-1.5-Potted) from [TE-Technology](https://tetech.com/)
- Thermometer (TH100PT) from [Thorlabs](https://www.thorlabs.com/)

The plots for each part can be found on their website. A printout is included
with the assembly for your reference

## Wiring

TEC chip wires are red and black. They are labeled for the positive and negative connections.
A typical working setting for the TEC would be 13 volts with 5 amps. It is highly advised to
set the current limiter on the power supply before increasing the voltage.
Two green wires are for the thermometer. The temperature can be derived by reading the
resistance and comparing it against the plot from the manufacturer (printed out).
The heat sink fan is on the back can be connected according to the color code.
A small power supply is modified for the use with the fan in the back.

## Assembly

The chamber was assembled and tested and was able to maintain -10&deg;C.

![Assembled TEC Chamber](https://github.com/fathi0amir/fathi0amir.github.io/blob/master/images/tec_assmbled.png?raw=true)
