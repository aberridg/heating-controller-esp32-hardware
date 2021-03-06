# heating-controller-esp32-hardware

This is a multi-zone heating controller, based on an ESP-32.

It uses Triacs for switching the boiler, pump and thermostats.

Right now, it is set up for 3 zones plus Domestic Hot Water.

It's designed to be used with this firmware:

https://github.com/aberridg/heating-controller-esp32-mqtt

The design can be used with physical thermostats or with triggering
via MQTT (for use with home automation systems such as Home Assistant).

![3D Rendering of PCB](heating-controller-esp32.png)

[Schematic](/heating-controller-esp32.pdf)

I'm having some PCBs made/assembled by JLCPCB, so if you want one, let me know (via LinkedIn - link in my bio)! Or if you can't do that, raise an issue.

IMPORTANT: v1.0 - the connector for the thermostats is the wrong way round on the PCB, so the pin numbers are not consistent with the others. No matter, just wire accordingly. For reference, GND is the upper pin, closest to the bottom edge of the board.

Also IMPORTANT: v1.0 - to flash the ESP32, hold down the Boot button and press reset.
