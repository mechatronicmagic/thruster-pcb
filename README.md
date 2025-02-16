- [Repository Info](#org2e50548)
- [Images](#org1e0b407)
- [Schematic](#org3ffac3e)
- [PCB](#org363fa67)
- [Bill of Materials](#org24314fe)
- [Development](#org9f407c8)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org2e50548"></a>

# Repository Info

-   Project Name: thruster-pcb
-   Synopsis:
-   Documentation Version: 1.0.0
-   Pcb Version: 1.0
-   Enclosure Version: 1.0
-   Supplemental BOM Version: 1.0
-   Release Date: 2025-02-16
-   Creation Date: 2025-01-04
-   Kicad Version: 7.0.11
-   License: GPL-3.0h
-   URL: <https://github.com/mechatronicmagic/thruster-pcb>
-   Author: Peter Polidoro
-   Email: peter@polidoro.io
-   Copyright: 2025 Mechatronic Magic
-   References:
    -   [Servo Control](https://en.wikipedia.org/wiki/Servo_control)
    -   [SB2264MG Servo](https://www.savoxusa.com/products/savsb2264mg-low-profile-hv-brushless-servo)
    -   [PCA9685](https://www.nxp.com/products/power-management/lighting-driver-and-controller-ics/led-drivers/16-channel-12-bit-pwm-fm-plus-ic-bus-led-driver:PCA9685)
    -   [nRF52840 Express](https://www.adafruit.com/product/4062)

![img](./documentation/pcb/raytrace.png)


<a id="org1e0b407"></a>

# Images


<a id="org3ffac3e"></a>

# Schematic


<a id="org363fa67"></a>

# PCB


<a id="org24314fe"></a>

# Bill of Materials


## Board

|    |
|--- |
|  |


## Supplemental

| Item | Synopsis                      | Manufacturer Part Number | Manufacturer | Quantity | Cost  | Total |
|---- |----------------------------- |------------------------ |------------ |-------- |----- |----- |
|      | Supplemental BOM Version: 1.0 |                          |              |          | Total | 40.11 |


<a id="org9f407c8"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Edit metadata.org

    make metadata-edits


## Tangle metadata.org

    make metadata


## Edit project

    make kicad-edits
    exit
