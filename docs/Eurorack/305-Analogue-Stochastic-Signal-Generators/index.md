# Title

![img](Images/img)

[TOC]

*Collection of Utilitarian Random Signal Generators*

# v0.1

## Specifications

|Parameter|Value|
|---------|-----|
|Width|10hp|
|Depth|~35mm *skiff friendly*|
|+12 Current|-|
|-12 Current|-|
|+5 Current|0mA|

## Features

- Based on Moritz Klein's design
- Analogue noise generator with three colours of noise (white, pink, blue)
- Jfet based S&H circuit with an input attenuator which is externally triggered.
- Slew rate limiter with slew amount control
- Two random triggers/gates (configurable with pins on the back) using comparators and the S&H signal with adjustable threshold
- Internal normalisations (Noise -> S&H -> Slew) that can be overridden with switched jacks.

## Quirks and Problems

- S&H section currently doesn't work, I think my batch of jfets are bad (edit: it turns out I may have misunderstood the pinout of the jfet and connected the Gate and Source the wrong way around)
- Pink noise sounds wrong (not lowpass-ed, but grainy), I think I used a bad capacitor (looking at my previous claims, I may be wrong again)

# v0.2

## Specifications

|Parameter|Value|
|---------|-----|
|Width|10hp|
|Depth|~35mm *skiff friendly*|
|+12 Current|-|
|-12 Current|-|
|+5 Current|0mA|

# Features

- JFET wiring issue resolved
- Slightly adjust wiring of pink noise circuit just in case it is the reason the issues are caused 

## Quirks and Problems

**HAS NOT BEEN TESTED YET**