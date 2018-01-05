---
layout: post
title: "EnviroTron"
date: 2016-12-01 12:00:00 -0600
short: envirotron
github: https://github.com/watsonboyett/marvin/tree/master/EnviroTron
image: board-assembled.jpg
tags:
- Environment Sensor
- Home Automation
- Super Tiny SMD
images:
- path: board-assembled.jpg
  title: 
  caption: Fully assembled sensor board attached to WeMos D1 Mini
- path: pcb-top.png
  title: 
  caption: Bare PCB render (look how tiny those SMD parts are!)

---

EnviroTron is a small sensor board that measures the world around it. Temperature, humidity, pressure, light, sound, and motion are all recorded and uploaded (via Wifi) to a central InfluxDB database. Grafana is then used to display the collected data and provide notifications and alarms based on desired criteria. 

These sensors are part of a larger home automation project, called "marvin", that includes feedback and control of other appliances and systems. 
