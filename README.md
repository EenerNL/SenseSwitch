# SenseSwitch
A smart switch with a lot of sensors inside of it!


## Overview
The ultimate goal is that it can replace a standard light switch. And it is not just a smart switch, but you get a whole lot of sensors within it.
So I made a list of requirements, selected the hardware and started with the design.

Requirements:
- Needs to fit in a standard flush-mounted box (instead of a light switch)
- Power supply is 230Vac (Live and Neutral)
- Relay for switching a light (or something else)
- Basic functionality needs to be in ESPHome, configuration possible on client side (Home Assitant)
- The relay can operate as normal on-off switch or pulse-output.
- Pushbutton for switching on and off the relay (light)

Current selected hardware:
- ESP32-D1-Mini board
- HLK-PS01 Power supply for 5V
- SRD-05VDC-SL-C Relay for switching the light
- BH1750 as an Illuminance sensor
- SGP30 as a TVOC / eCO2 sensor
- BME280 for Temperature, Humidity and Pressure
- HLK-LD2410C mmWave sensor for Presence detection.


## Roadmap:
List of actions and wishes:

- [x] Globaly design in 3D
- [x] Electrical design
- [x] PCB design
- [x] Prototype on breadboard
- [x] Writing basic ESPHome config
- [x] Enable Bluetooth BLE proxy (change framework to esp-idf)
- [x] Testing hardware and finetunig of config
- [ ] Finalize PCB design after testing
- [ ] Review 3D-design of whole device
- [ ] 3D-design mounting bracket for PCB's
- [ ] Finalize PCB design and order PCB's
- [ ] Assebly of all components
- [ ] Testing of first prototype
- [ ] Get approval for the 'Made for ESPHome' program
- [ ] Add more functionality to the config
    - [x] Add config entities for setting temperature and humidity offset
    - [x] Switching light based on presence and/or illuminance
    - [x] Config entities to configure the relay-functionality
    - [ ] Multiple options for the relay-functionality (light, ventilation, covers)
