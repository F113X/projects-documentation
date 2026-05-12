# A Note on Naming Modules

*07-05-2026*

[TOC]

This page will be about how I name my modules, it will be updated as new rules and series appear. 

Some of the naming doesn't make a lot of sense, and this is because I haven't thought things through when I named them. They might make things a bit confusing at first, but I have kept them consistent so it. 

The naming scheme only applies to the *Eurorack* section of this site, as all the others (*Archive* and *Standalone*) were made before I have decided on a design language. 

# Overall Pattern

This should be the most straightforward to understand. If you look at any module on this site, it should be obvious that the module names are comprised of a identifier + function.

Below are a few examples of module names that represents the naming conventions pretty well.

|Identifier|Function|
|:--------:|:------:|
|201|Dual Attenuverters|
|305|Analogue Stochastic Signal Generators|
|310c|Diode Voltage Controlled Filter|
|2399|Digital Delay Line|

As seen above, both parts are unique for each module, but the function is written in plain language and doesn't follow any naming conventions in particular, so the rest of the article will focus mainly on the identifier.

# Suffixes

In the identifier, there are 2 sub-sections. The beginning half is the number, which will be explained later; and the ending half is the suffix (currently only 1), which is universal regardless of the first half and will be explained in this section. 

|Suffix|Definition|
|:----:|:--------:|
|-c|compact|

Below will be a detailed explanation for each suffix.

## -c

As of now this is the only suffix in the name, it stands for compact. The determination of whether a module needs this suffix is pretty subjective, meaning it is not used whenever a module is below a certain width (i.e any module below 8hp will get this suffix). However, there is reasoning behind why a certain module will get this suffix, given below. 

For me, each module has a *reasonable* width. This is because I like to have varying knob sizes, and an overall layout that is comfortable to use. Refer to the [interface section of design philosophy](design-philosophy.md/#interface) for more details. However, those designs can get pretty big and there are situations where HP is low and you just need a compact module. This is when the -c suffix comes in. They are modules that give up *some* quality-of-life features and aesthetics in exchange for a smaller footprint. 

The [310c](https://f113x.github.io/projects-documentation/Eurorack/310c-Diode-Voltage-Controlled-Filter/), which is currently the only module with this suffix, is a good example of that. In just 4hp, it only has 1 CV input and has normal sized knobs for cutoff frequency and resonance (I usually like to at least have a large cutoff knob), so it only contains the essentials and don't have the more *interesting* features my other modules may have. I know it could be smaller and such like [2hp](twohp.com), however I don't want to give up my usual design language for the ultimate saving of width.

Another example would be **if** the [302](https://f113x.github.io/projects-documentation/Eurorack/302-Dual-Analog-Saw-Core-VCO/) would be made into a *hypothetical* 302c, it will have a smaller layout to fit into about 8-10hp, saving 4-6hp of space, but giving up the nice large knobs. 

In conclusion, the -c suffix is kinda like the *μ* prefix commonly seen when other manufactures make smaller versions of a module. Not every module will get a compact version though, it really depends on whether I want or need one, but I do want to make more of them in the future. 


# 3XX Series

This is the main series of my modules, and the simplest to understand. The first number is 3, which shows it is 3U, and the next 2 numbers just count up from 1. I have not considered the possibility that it exceeds 99, but if it does, there might be a 3XXX module at some point. the 2 numbers at the end of the model are counting up from 1 for all of the other series, so it will not be repeated again. I realised that the 3 could represent 3U only after I developed the first 2XX series module, which is why the 1U series is 2XX instead of 1XX

# 2XX Series

This is the second series that I made. It is a series of 1U Intellijel modules meant for mostly utility, but also may have some modules with interesting functions in the future. 

# 5XX Series

This is the third series that I made. There is a long explanation of what it is [here](https://f113x.github.io/projects-documentation/Eurorack/501-Timbre-Workshop/#foreword), and there is no particular reason why it starts with 5 other than the fact that I think it looks cool. 

# The Outliers

There are a few modules where the identifiers do not match any series given above, as they are intentionally different due to specific characteristics. 2 of the names were also given before I came up with any of the series mentioned above, which is also partially the reason to their different names. 


## 2399 & 4022

Those 2 identifiers come from the 2 chips that were used in the 2 modules, PT2399 and CD4022, respectively. 

They are also what lead to the naming conventions above, as initially I planned for the identifiers to be the name of a specific chip I used in a module, but then I would realise not all modules used unique chips and there would be a whole lot of modules with the identifier "074" (those who knows knows). 

## 606 & 909

Those 2 identifiers are used for 2 drum modules for pretty obvious reasons, the circuits are inspired by the original Roland drum machines and the resulting sound is also reminiscent of them. I have reserved the 303 slot for the same reason, and other modules that are heavily inspired or are clones of classic gear with good numbers will continue to do that. 

*Will it cause lawsuits and other complications? I don't know XD*