- [Repository Info](#orgcf761ff)
- [Images](#orga1b146e)
- [Schematic](#org2f8730d)
- [PCB](#orgee0fed7)
- [Bill of Materials](#org8738594)
- [Development](#org028dfc6)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="orgcf761ff"></a>

# Repository Info

-   Project Name: thruster-pcb
-   Synopsis:
-   Documentation Version: 1.0.0
-   Pcb Version: 1.0
-   Enclosure Version: 1.0
-   Supplemental BOM Version: 1.0
-   Release Date: 2025-02-19
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

![img](./documentation/pcb/pcb.png)


<a id="orga1b146e"></a>

# Images

<img src="./documentation/pcb/top.png" width="1920">

<img src="./documentation/pcb/bottom.png" width="1920">

<img src="./documentation/pcb/front.png" width="1920">

<img src="./documentation/pcb/back.png" width="1920">

<img src="./documentation/pcb/left.png" width="1920">

<img src="./documentation/pcb/right.png" width="1920">


<a id="org2f8730d"></a>

# Schematic

[./documentation/schematic/thruster-pcb.pdf](./documentation/schematic/thruster-pcb.pdf)

<img src="./documentation/schematic/thruster-pcb.svg" width="1920">

<img src="./documentation/schematic/thruster-pcb-assembly.svg" width="1920">

<img src="./documentation/schematic/thruster-pcb-power.svg" width="1920">

<img src="./documentation/schematic/thruster-pcb-microcontroller.svg" width="1920">

<img src="./documentation/schematic/thruster-pcb-thrusters.svg" width="1920">


<a id="orgee0fed7"></a>

# PCB

<img src="./documentation/pcb/thruster-pcb-User_Drawings.svg" width="1920">

<img src="./documentation/pcb/thruster-pcb-F_Silkscreen.svg" width="1920">

<img src="./documentation/pcb/thruster-pcb-B_Silkscreen.svg" width="1920">

<img src="./documentation/pcb/thruster-pcb-F_Fab.svg" width="1920">

<img src="./documentation/pcb/thruster-pcb-B_Fab.svg" width="1920">


<a id="org8738594"></a>

# Bill of Materials


## Board

| Item | Synopsis                          | Manufacturer Part Number | Manufacturer                         | Quantity | Reference(s)                       | Package             |
|---- |--------------------------------- |------------------------ |------------------------------------ |-------- |---------------------------------- |------------------- |
| 1    | 50V 3.3uF                         | FS32X335K500EGG          | PSA(Prosperity Dielectrics)          | 1        | C301                               | 1210                |
| 2    | CAP CER 0.1UF 100V X5R            | GRM155R62A104KE14D       | Murata Electronics                   | 5        | C302 C401 C501 C502 C503           | 0402                |
| 3    | CAP CER 1UF 25V X5R               | GRT155R61E105KE01D       | Murata Electronics                   | 2        | C303 C304                          | 0402                |
| 4    | CAP CER 47UF 10V X5R              | CGA0805X5R476M100MT      | HRE                                  | 7        | C305 C504 C505 C506 C507 C508 C509 | 0805                |
| 5    | DIODE SCHOTTKY 20V 1A             | MBR120VLSFT1G            | onsemi                               | 1        | D401                               | SOD-123FL           |
| 6    | MAXIBR M 03POS RA A SMT BK        | 284052-E                 | TE Connectivity                      | 7        | J301 J501 J502 J503 J504 J505 J506 |                     |
| 7    | RES SMD 1.8K OHM 5% 100mW         | ERJ2GEJ182X              | PANASONIC                            | 2        | R401 R402                          | 0402                |
| 8    | 1 Digit SPST 24V 25mA DIP         | EM-01KP                  | Korean Hroparts Elec                 | 1        | SW401                              | SMD,2.5x6mm         |
| 9    | DC-DC 5V 600mA Output 3-65V Input | TPSM365R6V5RDNR          | Texas Instruments                    | 1        | U301                               | QFN-11(3.5x4.5)     |
| 10   | IC SWITCH DEBOUNCER               | MAX6816EUS+T             | Analog Devices Inc./Maxim Integrated | 1        | U401                               | SOT-143             |
| 11   | IC LED DRVR LIN PWM 25MA          | PCA9685BS,118            | NXP Semicon                          | 1        | U501                               | SOT-788-1           |
| 12   | IC TRANSLTR BIDIRECTIONAL         | TXS0108ERGYR             | Texas Instruments                    | 1        | U502                               | VQFN-20-EP(3.7x4.7) |


## Supplemental

| Item | Synopsis                                                            | Manufacturer Part Number | Manufacturer | Quantity | Cost  | Total |
|---- |------------------------------------------------------------------- |------------------------ |------------ |-------- |----- |----- |
| 1    | Adafruit Feather nRF52840 Express                                   | 4062                     | adafruit     | 1        | 24.95 | 24.95 |
| 2    | NiMH Battery (6V, 2700mAh, 2-Pos TJC8 Power Connector [MH-FC], 6-1) | 3100-0006-0001           | servocity    | 1        | 14.99 | 14.99 |
|      | Supplemental BOM Version: 1.0                                       |                          |              |          | Total | 39.94 |


<a id="org028dfc6"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Generate Output from KiCad


### Remove previous versions

```sh
rm -rf ./documentation/3dmodels/* && rm -rf ./documentation/bom/* && rm -rf ./documentation/fabrication/* && rm -rf ./documentation/pcb/* && rm -rf ./documentation/schematic/*pcb
```


### Images

1.  3D Viewer

    Output directory: ../documentation/pcb
    
    -   pcb.png
    -   top.png
    -   bottom.png
    -   front.png
    -   back.png
    -   left.png
    -   right.png

2.  Trim

        make trimmed-images

3.  Schematic PDF

    File -> Plot
    
    Output directory: ../documentation/schematic
    
    Plot All Pages
    
    -   Output format PDF
    -   Page Size = Schematic size
    -   Plot drawing sheet
    -   Output mode = Color
    -   Color theme = KiCad Default
    -   Default line width = 0.006 in

4.  Schematic SVG

    File -> Plot
    
    Output directory: ../documentation/schematic
    
    Plot All Pages
    
    -   Output format SVG
    -   Page Size = Schematic size
    -   Plot drawing sheet
    -   Output mode = Color
    -   Color theme = Solarized Light
    -   Default line width = 0.012 in

5.  PCB SVG

    Add Edge.Cuts, holes, and dimensions to User.Drawings
    
    File -> Plot
    
    Output directory: ../documentation/pcb
    
    -   Plot format SVG
    -   Include Layers
        -   User.Drawings
        -   F.Silkscreen
        -   B.Silkscreen
        -   F.Fab
        -   B.Fab
    -   Plot on All Layers
        -   Edge.Cuts
    -   Plot footprint values
    -   Plot reference designators
    -   SVG Options
        -   Precision = 4
        -   Output mode = color
    
        make cropped-svg


### Fabrication Files

1.  Gerbers

    File -> Fabrication Outputs -> Gerbers (.gbr)
    
    Output directory: ../documentation/fabrication/gerbers
    
    Include Layers:
    
    -   F.Cu
    -   F.Paste
    -   F.Silks
    -   F.Mask
    -   F.Fab
    -   B.Cu
    -   B.Paste
    -   B.Silks
    -   B.Mask
    -   B.Fab
    -   Edge.Cuts - (contain the board outline/cutouts.)
    -   In1.Cu, In2.Cu … - (needed for 4/6 layer designs.)
    
    Options:
    
    -   Select Plot reference designators, otherwise designators will not appear on silkscreen layers.
    -   Select Check zone fills before plotting
    -   Select Use Protel filename extensions, this is recommended as JLCPCB prefers Protel filename extensions.
    -   Select Subtract soldermask from silkscreen, this ensures no silkscreen on pads.
    -   Coordinate format 4.6 unit mm

2.  Drill and Map Files

    Output directory: ../documentation/fabrication/gerbers
    
    Options:
    
    -   Excellon drill file format
    -   Check Use alternate drill mode for "Oval Holes Drill Mode".
    -   Check Absolute for "Drill Origin".
    -   Check Millimeters for "Drill Units".
    -   Check Decimal format for "Zeros Format".
    -   Gerber X2 map file format
    
    Zip gerber files
    
        zip ./documentation/fabrication/gerbers.zip ./documentation/fabrication/gerbers/*

3.  BOM

    Generate BOM from schematic editor using blank command line to create bom xml file.

4.  POS

    File -> Fabrication Outputs -> Component Placement (.pos)
    
    Output directory: ../documentation/fabrication/
    
    Settings:
    
    -   Format = CSV
    -   Units = Millimeters
    -   Files = Single file for board
    -   Do not use drill/place file origin
    
    Modify pos files:
    
    -   Ref -> Designator
    -   PosX -> Mid X
    -   PosY -> Mid Y
    -   Rot -> Rotation
    -   Side -> Layer

5.  Step

    File -> Export -> Step
    
    Output directory: ../documentation/3dmodels/pcb.step
    
    -   Drill/place file origin
    -   Overwrite old file
    -   Standard Board outline chaining tolerance


## Edit metadata.org

    make metadata-edits


## Tangle metadata.org

    make metadata


## Edit project

    make kicad-edits
    exit
