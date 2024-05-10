---
layout: default
title: Microcontrollers
parent: Projects
nav_order: 1
---

## Microcontrollers

* * *

Some of my favorite projects are showcased below.

* * * 

## Boid Swarm

<video width="600" height="850" src="IMG_1996.MOV" type="video/mov" preload="auto" autoplay muted loop>
</video>

Above: a microcontrollers project for ECE 4760 where we simulated a swarm of birds or "boids." The goal was to program such that as many boids could be animated as possible, while enforcing a strict framerate. This is an end result of the project, where we have 5000 boids animated. The strange snaking behavior arose from messing with our hardware-controlled boid parameters, adjusted with a potentiometer. When the swarm explodes outward, I am turning up the "avoid factor" parameter.

* * * 

## MIDI Synth on RP2040

You can watch a demo video of my midi-controlled synthesizer below. I use my MIDI keyboard as a controller, and the Raspberry Pi parses these messed-up MIDI outputs and plays the right notes (sometimes). 

<iframe width="560" height="315" src="https://www.youtube.com/embed/gv6tslaxl0o?si=n0J7mK1j7EzVpdau" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Also, an article was written about my project [here](https://hackaday.com/2023/12/22/raspberry-pi-pico-becomes-midi-compatible-synth/) for whatever reason. Don't read the mean comments.