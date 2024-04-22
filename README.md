# Avdisplay Cape

Kicad design for beaglebone black cape. Provides Dual CAN bus & bus
protection. Provides 3A of 5V power to the beaglebone black using dual
offboard 1.5A switching power supplies. These are load balanced using
a LTC4370 device. Since the project is also using a LCD display, only
one of the beaglebone's dual CAN devices is available due to pin
conflicts, so another external MCP2515 CAN controller connected via SPI is
onboard.

## View and Schematics

![3D View](avdisplay-cape-3D.png)

![Schematics](avdisplay-cap.pdf)
