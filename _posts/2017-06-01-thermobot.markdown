---
layout: post
title: "ThermoBot"
date: 2017-06-01 12:00:00 -0600
short: ThermoBot
github: https://github.com/watsonboyett/ThermoBot
image: oven-internals.jpg
tags:
- Temperature Controller
- Reflow Oven
- Process Control
images:
- path: oven-internals.jpg
  title: 
  caption: inside the oven -- rewired to include the controller 
- path: board-assembled.jpg
  title: 
  caption: the assembled temperature controller PCB
- path: pcb-top.png
  title: 
  caption: bare top layer of the PCB
---

ThermoBot is a temperature controller that allows users to define custom heating profiles. The target application is a DIY reflow oven, but it can easily be extended to other applications that require heating profiles.

ThermoBot supports conventional thermostat and PID control algorithms, as well a more "advanced"/experimental convolutional control algorithm. The convolutional control method requires prior knowledge of the system response and the heating profile must be calculated in advance (currently done by an off-line python script). However, these features could be implemented into the controller firmware at a later date.
