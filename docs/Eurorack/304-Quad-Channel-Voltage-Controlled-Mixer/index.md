# 304 Quad Channel Voltage Controlled Mixer

![img](Images/img)

[TOC]

*Quad VCAs or 2/3/4 channel Mixer*

# v0.1

## Specifications

|Parameter|Value|
|---------|-----|
|Width|10HP|
|Depth|~35mm *skiff friendly*|
|+12 Current|-|
|-12 Current|-|
|+5 Current|0mA|

## Features

- Four channels of seperate/mixed VCAs
- Attenuators for CV modulation
- Sliders for adjusting volume
- Internal normalisation: if channel output not plugged in, automatically mixes signal into channel 4 out (mix out), the module can be used as four seperate VCAs and a four channel VC mixer and everything in between

## Quirks and Problems

- Mostly works fine, some channels overdrive sometimes, some channel leaks sound when volume is fully down, mixer chip (TL072) becomes hot (IDK if that's normal)
- sliders are logarithmic, but I can't notice it during use.