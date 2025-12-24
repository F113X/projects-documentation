# Title

![img](Images/img)

[TOC]

*VCF and VC-Wavefolder Combo*

# v0.1 - Defunct

## Specifications

|Parameter|Value|
|---------|-----|
|Width|16hp|
|Depth|-|
|+12 Current|-|
|-12 Current|-|
|+5 Current|-|

## Features

- This module is a combination of 3 circuits (all practically no changes done to them)
- VC-Wavefolder Circuit by SynthFox: [Lyssa Wavefolder](https://sfcs.neocities.org/module/SFP50/), with several flavours of wavefolding achieved by switch combinations
- Classic René Schmitz [late MS20 VCF](https://www.schmitzbits.de/ms20.html)
- Bonus Saw to Triangle converter based on the Moritz Klein x Ericasynths [EDU DIY Wavefolder](https://www.ericasynths.lv/shop/diy-kits-1/edu-diy-wavefolder/)
- **Only changes:** added an attenuverter for VCF CV, Highpass input, and Saw to Tri out normals into wavefolder 

## Quirks and Problems

- 3 issues found within PCB:
    1. Missing resistor (R4, 100k on original schematic) in the fold CV section (on topboard)
    2. 1.8k resistor in the resonance path connected to + input of op-amp rather than - input (on mainboard)
    3. Story time: remember the [201 Dual Attenuverters](/Eurorack/201-Dual-Attenuverters/)? I originally didn't draw the schematics for it, and when I needed the circuit again I went back and traced the PCB to produce this schematic:
    ![original schematic](Images/wrong-attenuverter.png)
    Guess what? **IT WAS WRONG!**
    In conclusion, this mistake caused the CV of the VCF to not work :(, and the only way to (partially) solve that is to not connect the op-amp pins for the attenuverter, so the VCF will only have 1 CV input. Also, it explains at least one of the issues in the [307 Dual Analogue State Variable Filters](/Eurorack/307-Dual-Analogue-State-Variable-Filters) (which contains 3 of those incorrect attenuverters), though it still doesn't work when the attenuverters are disabled.
- Other than that, no issues have been found yet

# v0.2 - Untested

## Features

- Fixed all of the problems mentioned before, and more importantly, **updated the attenuverter schematic**

## Quirks and Problems

- Might still have issues, however untested and not manufactured yet




