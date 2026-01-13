*This page has a lot of text and no images. I will try to incorporate some images later to make things interesting.*

I'm not sure how to call this, but it is basically the overarching concept of my stuff. 

Through the past 2 years of learning about, designing, and making synthesizer modules, I have constucted an idea of how I want my modules to be like. The following article (or text) will guide the developments of future modules, and may also partially reflect my previous modules. 

*Please note that everything here may change in the future, but as of 2026 it is how I will proceed*

[TOC]

# Precision

First of all, I dislike unwanted unpredictablity. It's probably due to the test equipment content from [Hainbach](https://www.hainbachmusik.com/) that I consume way to much. I want my modules to be precise and accurate, no unstable behaviors such as unwanted distortion, drifting, or others. 

For example, a VCO should be temperature compensated ensuring minimal drifting, have the full range (20-20k Hz) or better, low distortion in harmonically pure waveforms, and a good enough v/oct tracking that I don't hear it during use. (I don't have perfect pitch, but the [302](https://f113x.github.io/projects-documentation/Eurorack/302-Dual-Analog-Saw-Core-VCO/) VCO tracks pretty darn well with minimal calibration, though I might want a bit more than that) 

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

This was until I've discovered the [THC EIMTO](https://thehumancomparator.net/eimto.html), which only have 10 controls, but looks insanely fun to play with. This directly inspired me to draw up designs for the [Dronebox 1 (no offical name yet)](https://f113x.github.io/projects-documentation/Standalone/Dronebox-1/), which still has "too many" controls and is not produced yet. I still want to make it, just with some changed circuitry I have learnt a lot about the circuits since I designed that PCB.  

# Interface

It should be quite obvious that I like big knobs, but interface is not just about knobs, obviously.

Recently, I wanted to make a touch controller of some sort, which can be used a keyboard, sequencer, arppegiator, and other purposes. I also hope for it to have position and pressure sensing capabilities, similar to the [Verbos Electronics Mini Horse](https://www.verboselectronics.com/modules/mini-horse). I have no idea how to achieve all of this yet, but it should be a good insight to my concept of interfacing. 

I'm not sure if I really like new or "gestural interfaces", I sure wouldn't want to use fruits as CV sources (yet), I just want something that is super intuitive and hands on to use, while still having some degree of expressiveness.  

When speaking of the interface, another factor is the actual exterior design of modules. Panel aesthetics should be consistant, and should follow my long term design language. I believe beautiful products that give users an enjoyable experience using it (I'd probably prefer a beautiful product over an ugly one, even if they had the same functionality).

It is also important to define what I mean by "beautiful" product design. 

On the scale of an individual module, different elements should not be crowded together, labels should be clear and technical (that's how I like it, not some weird terms you have to decipher when you want to use it), and indicator LEDs should serve a clear purpose, and **not too bright**. I typically don't show the normalled connections because I haven't found a good way to incorporate them into the panel yet, but that would also help a lot. The general rule of thumb for me is: if I can figure out what a module does just by looking at the panel, it is designed well (especially if it's analogue, digital menu diving is technically still fine as long as it's not too bad). This is also why my module names are basically their functions. 

On the scale of complete systems, the user should feel that they are within a single system, not collections of different modules. As an example, I am actively designing future modules so that all the jacks and knobs fall into the same columns and rows. Also, a note on the conflict between individual modules and complete systems: single modules can look really ugly while still making a beautiful system. For example, I don't really like (no offense btw, we all have different preferences) the [NLC](https://www.nonlinearcircuits.com/) panel design, but entire NLC systems can still look very impressive and engaging to play with, because of the overall consistancy of designs. 

However, I'm not saying that I dislike the "mixing and matching" nature of Eurorack, but sometimes it goes too far and is really tiring to look at. (I would love to make a list of brands that make modules that I consider ugly, but I've decided against that for various reasons. Also the list will be too long :P)

# Cohesion 

I always wanted to make a independent, cohesive system that has great flexibility and inspires the user to experiment, and I have always been designing my modules with this overarching structure. (though most of my modules still follow my needs of the time, but I still consider this when making new modules)

# Production

I generally avoid IC's and components that are rare, expensive, or obsolete. I *could* explain this with the standard answer of "I hope others can make or repair it just as easily" or something like that, but even though that is partially true, the main reasons already existed when I just started out, and it boils down to 2 points:

1. I have a budget too. This is why I generally avoid slightly expensive stuff, especially when I'm not 100% sure if it will work or not. 
2. I have a trusted components supplier and I hope to get my components from exclusively, because I don't trust the small sketchy distributers and they generally have higher shipping fees. However, my supplier doesn't stock most rare chips such as the 33XX chips or similar. This also explains why I use LM13700s, because my supplier stocks them (luckily). I recently realised how difficult it is for some people to obtain LM13700s, so I will probably reduce its use for VCAs, and only use them when absolutely necessary. 

# Sources of inspiration

This section will just list some of the sources that inspired and shaped my conception of sound synthesis, as well as some descriptions of what inspired me. There is no specific order to the list. BTW the subtitles are links if you wanted to check these brands out for yourself. 

**I am not affiliated with the brands mentioned below in any way, they just really brought me a long way. I will put links, as I really want others to look into the things for themselves.**

## [Xaoc Devices](http://xaocdevices.com/main/)

This is one of the largest influences to me. I've spent literal hours in their website just reading the descriptions over and over. 

If it wasn't obvious already (it probably wasn't lol), my panel designs are largely inspired by Xoac Devices' modules. My panels do not emphasize it as much as theirs, but it has a "lab grade" feel to it. All the knobs are so clearly marked out, and everything fits together so well that it feels like you could actually do scientific experiments with it. Although I don't own any of their modules (or any from the other brands), I just could see how the modules can work together perfectly, as well as the [Leibniz Subsystem](http://xaocdevices.com/main/drezno/), which is a wonder on its own. The module that introduced me to Xaoc is [Belgrad](http://xaocdevices.com/main/belgrad/), which offers so much flexibility with such a simple concept. Also, the big knobs are just begging for use, and the layout is so easy to understand. 

## [Serge](https://serge-modular.com/)

This was also one of the first brand I've known of (before knowing Eurorack even!), due to the videos I watched, which happened to be mostly using Serge instruments. I'm not sure whether I've even grasped what the modules do yet, so honestly there is not much to say, it is mostly the exterior design and the overall cohesiveness (you can make a whole system of only Serge and make wonderful stuff) that got me. This will probably be mentioned several times later, and for more information please refer to the cohesion section for more info. 

## Buchla

There is not much to be said about this brand, mostly just aesthetics, cohesiveness, and creative product design that gave me many new ideas. 

## [Verbos Electronics](https://www.verboselectronics.com/)

There is not much to be said about this brand, mostly just aesthetics, cohesiveness, and creative product design that gave me many new ideas. 

## [Erica Synths](https://www.ericasynths.lv/)

A significant portion of my circuits originally come from the EDU series, which is a collaboration project between Moritz Klein and Erica Synths. It is probably to a point where even if I encounter problems in other circuits, I will refer to the manuals of this series as it makes things so easy to understand, and honestly the modules they put out are basic building blocks of a synthesizer, so it's basically applicable anywhere. 

## [The Human Comparator](https://thehumancomparator.net/)

This brand mostly inspires me from the clean, elegant product design. Each product feels like an art piece, and the website is like an art gallery. There is also so little information on this brand, I've only found a couple of videos that Hainbach made on two of their products, and it is quite hard to figure out the true potential of the products just by looking at panels and different documents in the website. 

## Music Thing Modular

## [Mengqi Music](https://www.mengqimusic.com/) (btw i like his original website better)

Remember when I said that I disliked new gestural interfaces? This section will contradict with that *slightly*. 

As one of the first smaller brands I've encountered during my synthesizer journey, Mengqi Music really was an eye-opener. One of the first instruments that I knew about is the [Wing Pinger](https://www.mengqimusic.com/wingpinger-introduction), which is such a simple instrument on the surface but so fun and deep to experiment with. 

His instruments also opened a new door to several other synth creators which also went on to inspire me, e.g Peter Blasser, Rob Hordijk etc, but I will probably not write whole sections on those creators, as it would become too complicated too quickly. Just know that I've tried to make P. Blasser's circuites several times with no avail, and didn't even attempt Rob Hordijk's work because of rare components. 

The attention for detail is also insane, as I've met him once and he told us that one reason the Wing Pinger is so expensive is because he took a long time to find the best potentiometers, and nothing other than a very expensive one that matched his desired resistance and smoothness exactly. 

Also his archive just has some of the most beautiful instruments I've ever seen and it's just nice to look at, even though there is also minimal information on most of them. 

I now own the DPLPG (not on his site, dual passive lopass gate) and the [Wingie2](https://www.mengqimusic.com/wingie2-introduction), and both are absolute inpirations and fun to play with in general. 

## [Nonlinear Circuits](https://www.nonlinearcircuits.com/)

Also a great place to find interesting opensource designs, NLC has directly inspired me to make the [Percbox](https://f113x.github.io/projects-documentation/Standalone/Percbox/), which sadly doesn't work yet and a new revision is needed. 

## Others

It is important to mention that just because some brands weren't mentioned above doesn't mean I haven't looked into their work and/or is inspired by their work. It's just not to such a high degree or I forgot to add them in the time of writing. 

Here are some others that deserved to be mentioned, as I've either learnt a lot from them or made stuff they designed:

Music from Outer Space

Yusynth

Benjiao Modular

modular.khiat (Their site is down)

Instruo

Look Mum No Computer

René Schmitz

Moritz Klein

[Kassutronics](https://kassu2000.blogspot.com/)

[Synthfox](https://sfcs.neocities.org/)

Ken Stone (CGS)