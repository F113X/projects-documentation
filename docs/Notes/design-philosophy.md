I'm not sure how to call this, but it is basically the overarching concept of my stuff. 


Through the past 2 years of learning about, designing, and making synthesizer modules, I have constucted an idea of how I want my modules to be like. The following article (or text) will guide the developments of future modules, and may also partially reflect my previous modules. 

*Please note that everything here may change in the future, but as of 2026 it is how I will proceed*

[TOC]

# Precision

First of all, I dislike unwanted unpredictablity. It's probably due to the test equipment content from [Hainbach](https://www.hainbachmusik.com/) that I consume way to much. I want my modules to be precise and accurate, no unstable behaviors such as unwanted distortion, drifting, or others. 

For example, a VCO should be temperature compensated ensuring minimal drifting, have the full range or better (20-20k Hz), low distortion in harmonically pure waveforms, and a good enough v/oct tracking that I don't hear it during use. (I don't have perfect pitch, but the [302](Eurorack/302-Dual-Analog-Saw-Core-VCO/index.md) VCO tracks pretty darn well with minimal calibration, though I might want a bit more than that) 

Of course, absolute precision is impossible, and I am far from being able to optimise circuits to a high degree as well as being too lazy for extra steps in the construction such as applying thermal paste (hopefully that laziness goes away), so I will probably still utilize janky solutions anyways. 

With that said, it is probably obvious that my definition of precision is not surgical, but still up to some standards. 

# Randomness

However, that doesn't mean I dislike randomness or using modules creatively, because that is boring. I just want the module to do exactly what it says on the cover if you use it the "right" way.

The [Buchla 266 Source of Uncertainty](https://buchla.com/product/266/) is a wonderful demonstration of precision while still yielding randomized results. It provides a large variety of controls and quantisation possibilities for the user to decide how random the signal will be. 

In conclusion, I'd probably say I like the concept of "controlled randomness", if that's a good way to put it. 

# Pure Tone vs Noise

Recently I've grown increasingly attracted to pure waveforms such as sine and triangle. 

# Limitations

It is difficult to decide how much freedom you want to give the user. Everytime I wanted to make a standalone device, I always wanted to give the user every single control possible, and it is getting clearer and clearer to me that this will make the device boring to play with. 

This was until I've discovered the [THC EIMTO](https://thehumancomparator.net/eimto.html), which only have 10 controls, but looks insanely fun to play with. This directly inspired me to draw up designs for the [Dronebox 1 (no offical name yet)](Standalone/Dronebox-1/index.md), which still has "too many" controls and is not produced yet. 

# Interface

It should be quite obvious that I like big knobs, but interface is not just about knobs, obviously.

Recently, I wanted to make a touch controller of some sort, which can be used a keyboard, sequencer, arppegiator, and other purposes. I also hope for it to have position and pressure sensing capabilities, similar to the [Verbos Electronics Mini Horse](https://www.verboselectronics.com/modules/mini-horse). I have no idea how to achieve all of this yet, but it should be a good insight to my concept of interfacing. 

I'm not sure if I really like new or "gestural interfaces", I sure wouldn't want to use fruits as CV sources (yet), I just want something that is super intuitive and hands on to use, while still having some degree of expressiveness.  

# Cohesion 

I always wanted to make a independent, cohesive system that has great flexibility, and I have always been designing my modules with this overarching structure. (though most of my modules still follow my needs of the time, but I still consider this when making new modules)

Panel aesthetics should be consistant

# Production

I generally avoid IC's and components that are rare, expensive, or obsolete. I *could* explain this with the standard answer of "I hope others can make or repair it just as easily" or something like that, but even though that is partially true, the main reasons already existed when I just started out, and it boils down to 2 points:

1. I have a budget too. This is why I generally avoid slightly expensive stuff, especially when I'm not 100% sure if it will work or not. 
2. I have a trusted components supplier and I hope to get my components from exclusively, because I don't trust the small sketchy distributers and they generally have higher shipping fees. However, my supplier doesn't stock most rare chips such as the 33XX chips or similar. This also explains why I use LM13700s, because my supplier stocks them (luckily). I recently realised how difficult it is for some people to obtain LM13700s, so I will probably reduce its use for VCAs, and only use them when absolutely necessary. 

# Sources of inspiration

This section will just list some of the sources that inspired and shaped my conception of sound synthesis, as well as some descriptions of what inspired me. There is no specific order to the list. 

## [Xaoc Devices](http://xaocdevices.com/main/)

This is one of the largest influences to me. 

If it wasn't obvious already (it probably wasn't lol), my panel designs are largely inspired by Xoac Devices' modules. My panels do not emphasize it as much as theirs, but it has a "lab grade" feel to it. All the knobs are so clearly marked out, and everything fits together so well that it feels like you could actually do scientific experiments with it. Although I don't own any of their modules (or any from the other brands), I just could see how the modules can work together perfectly, as well as the [Leibniz Subsystem](http://xaocdevices.com/main/drezno/), which is a wonder on its own. The module that introduced me to Xaoc is [Belgrad](http://xaocdevices.com/main/belgrad/), which offers so much flexibility with such a simple concept. Also, the big knobs are just begging for use, and the layout is so easy to understand. 

## Buchla

## Serge

## [Verbos Electronics](https://www.verboselectronics.com/)

## Erica Synths

## The Human Comparator

## Music Thing Modular

## [Mengqi Music](https://www.mengqimusic.com/) (btw i like his original website better)

## Others

It's important to recognise that brands other than the ones mentioned above have also greatly influenced my 

Roland, Moog, Korg, and all the big brands should definitely be recognised, and I have also looked deeply into their work. Other synth DIYers such as LMNC, Rene Schmitz, Moritz Klein, and others are all people that I look up to. I've felt a need to address this, as those are who brought me to synthesizer and DIY in the first place. 