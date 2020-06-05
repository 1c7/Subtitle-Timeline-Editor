## Product Name: Subtitle Timeline Editor
(Temporary name until I come up with a better one)

## Design 
![](./img/design.jpg)  
(using Sketch)

## Current Status: Developing
Estimated release date: Next half of 2020   

## What problem does it solve?
improve the efficiency of adding subtitle to video   

## What exactly that mean?
1. Beautiful UI (including night mode)
2. Make adjust subtitle time easier
	* Support Hotkey
	* Display audio waveform

## Why?
The current software for making subtitle is not good.  


## Behind the scene: Design 

### I made multiple version
![](./img/1.jpg)

### Zoom out to view all canvas: 
![](./img/2.jpg)

## Software for making subtitle
Currently: 

* Aegisub
* Arctime Pro

I ignore these ugly software which built between 2000 and 2010 and support windows only，  

## Downside of Aegisub
![](./img/aegisub.jpg)

* no update since 2014
* UI look olds, no night mode
* hotkey support is not good, it crash the software sometimes  


## Downside of Arctime Pro
![](./img/arctime.jpg)

* UI look OK, but not good enough
* the experiences on macOS just not good
* Subtitle block with same timeline would overlap, making bilingual subtitle is difficult

Pro:  
* Arctime have waveform in the background

## Product Roadmap
Overall Goal:
* Aegisub have way too many feature, So I am not gonna set my goal to replace Aegisub for now
* make adjust timeline for subtitle a great experiences

### Version 1.0
* beatuiful UI
* easy to change timeline
* Support one or two subtitle format for now (srt / ass)
* it's a MVP, try to as minimal as possible

### Version 1.5
* Hotkey

### Version 2.0
* Add machine translate feature (Google / IBM / Azure / Amazon)
* Add hard burn subtitle into video feature (make subtitle as part of the pixels)
