# SenseSwitch
A smart switch with a lot of sensors inside of it!


## Overview
The ultimate goal is that it can replace a standard light switch. And it is not just a smart switch, but you get a whole lot of sensors within it.
So I made a list of requirements and started with the design.

Requirements:
- Needs to fit in a standard flush-mounted box (instead of a light switch)
- Power supply is 230Vac (Live and Neutral)
- Relay for switching a light (or something else)
- Basic functionality needs to be in ESPHome, configuration possible on client side (Home Assitant)

Current selected hardware:
- ESP32-D1-Mini board
- HLK-PS01 Power supply for 5V
- SRD-05VDC-SL-C Relay for switching the light
- BH1750 as an Illuminance sensor
- SGP30 as a TVOC sensor
- BME280 for Temperature, Humidity and Pressure
- HLK-LD2410C mmWave sensor for Presence detection.


## Actions
List of actions to do:

- [x] Globaly design in 3D
- [x] Electrical design
- [x] PCB design
- [x] Prototype on breadboard
- [x] Writing basic ESPHome config
- [ ] Finish final PCB design after testing
- [ ] Review 3D-design of whole device
- [ ] 3D-design mounting bracket for PCB's
- [ ] Finalize PCB design and order PCB's
- [ ] Assebly of all components
- [ ] Testing of first prototype
