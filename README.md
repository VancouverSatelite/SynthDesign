# Synth/Keyboard Design


## Important Notes about the scope of this project

When envisioning a Keyboard / Synthesizer, I often imagine it with a form factor that of either a Minimoog, an Arturia AstroLab, or a Casio LK-265 (Pictured below). The latter of which I own and got as a christmas gift a few years ago. (I plan on modding it in the near future.) 

This project will probably end up being around the complexity level of an 80's base level casio or yamaha keyboard, making it a solid keyboard for a beginner keys player (such as myself). I'm expecting this to end up being an Oscillator, an ADSR with some sliders, and some presets that mess with the waveform to create different sounds, presumably done with like capacitors and resistors (this is the part I've not looked into yet).


I think this will be a good mid-level project for an engineer such as myself, and as such will be seeing where I go with it.


### Example's Given
Hey look I put them in price order by accident.

---
#### Moog Minimoog

![](https://github.com/VancouverSatelite/SynthDesign/blob/main/Media/MiniMoog.jpg)
 [Image source](https://cdm.link/minimoog-missing-link/)

 Pictured above is Moog's Minimoog, a classic synthesizer, I've only heard glorious things about it, and it's revered as a legend online (yes I know this is anecdotal). I have never actually seen a minimoog or it's line of descendants named in a similar manner.

---
#### Arturia Astrolab 

![](https://github.com/VancouverSatelite/SynthDesign/blob/main/Media/Astrolab.jpeg)
[Image source](https://www.avshop.ca/recording-controllers/arturia-astrolab-61-key-stage-keyboard?__cf_chl_f_tk=p7kz2twG5REP5MgtDt6TkLrt6cTU.ZU4teSZfQjUQQs-1783382631-1.0.1.1-H8EI2DeumR4r.gfAgl3fNApPAfk8RLXopluEpLBcxpQ)

Pictured above is a personal favorite of mine, The Arturia Astrolab (this one's a 61 key). The Arturia Astrolab is a very versatile Synth, with a TON of presets. I have played one like 4 seperate times, because each time I go to guitar center it's what's sitting out and I freak out and get giddy. They are epic!

---
#### Casio LK-265 

![](https://github.com/VancouverSatelite/SynthDesign/blob/main/Media/casio.jpg)
[Image source](https://bestpianokeyboards.com/reviews/casio-lk-265-61-key-keyboard-review/)

Pictured above is the Keyboard which I own, it's pretty good, but the main thing it's missing is a midi/USB out so I can't use it on an audio interface or connected to a DAW. It's great for just plugging my headphones into and playing though if I want some cool presets. it's got like ~400 presets or something crazy, and it's fun to use. The keys aren't weighted, but at this price point you wouldn't expect that.

## Step 1: The Planning Phase

## Step 2: The Oscillator


Okay so I may have completely jumped the gun and went directly to Step 2, so I started with an oscillator. Currently my idea is to use a NE555 chip <sub>[Datasheet](https://www.ti.com/lit/ds/symlink/ne555.pdf?ts=1783341500935&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FNE555%253Futm_source%253Dgoogle%2526utm_medium%253Dcpc%2526utm_campaign%253Dti-null-null-xref-cpc-pf-google-ww_en_cons%2526utm_content%253Dxref%2526ds_k%253DNE555%2526dcm%253Dyes%2526gclsrc%253Daw.ds%2526gad_source%253D1%2526gad_campaignid%253D23167718368%2526gbraid%253D0AAAAAC068F1p6e-_8HsMsWvMZ_rWlRLaM%2526gclid%253DCjwKCAjwu53SBhAhEiwAJzSLNrd038ga1U21k-g-4e6bnKQhk41KmV4a3vjl2LVMLKJhO3CMautZLBoC4H0QAvD_BwE)</sub>, a common timer chip [made by Texas Instruments.](https://www.ti.com/product/NE555), and use this as the oscillator to base everything off of. 

---
## Step 3 (1): Planning, but real

Key components I plan to use for this will be mostly integrated circuit chips, as I feel using an Arduino or a Pi Pico would probably be too easy

### Things to make

#### Oscillator

#### ADSR 

#### Presets

#### Keys

#### Amplifier

#### 




































---
## Resources used

[Circuits DIY](https://www.circuits-diy.com/simple-tone-generator-circuit-using-ne555-timer-ic/)

[Synths'R'Us](https://www.schmitzbits.de/adsr.html)
