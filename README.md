- [About](#org0fe81aa)
- [Images](#org7261216)
- [Schematic](#org98852f4)
- [PCB](#orgfe9cefc)
- [Bill of Materials](#orga00b9d5)
- [Notes](#org252d51a)
- [Development](#orgeca6f45)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org0fe81aa"></a>

# About

```markdown
- Project Name: mouse_joystick_controller
- Description: Janelia mouse joystick controller for the Dudman lab experiments.
- Version: 2.0
- Kicad Version: 7.0.1
- Release Date: 2023-04-13
- Creation Date: 2017-08-14
- License: BSD-3-Clause
- URL: https://github.com/janelia-kicad/mouse_joystick_controller
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2023 Howard Hughes Medical Institute
- References:
  - https://www.kicad.org/
  - https://www.transducertechniques.com/rts-torque-sensor.aspx
  - https://placidindustries.com/products/brakes/magnetic-particle-brakes/magnetic-particle-brake-b5z/
  - https://www.newark.com/broadcom-limited/hedr-5421-ep111/encoder-incremental-2-ch/dp/58Y4773
  - https://www.linengineering.com/products/stepper-motors/hybrid-stepper-motors/208-series/208-13-01/WO-208-13-01D
  - https://www.pololu.com/product/2267
```


<a id="org7261216"></a>

# Images


<a id="org98852f4"></a>

# Schematic


<a id="orgfe9cefc"></a>

# PCB


<a id="orga00b9d5"></a>

# Bill of Materials


## Board

|    |
|--- |
|  |


## Supplemental

| Item | Description | Manufacturer Part Number | Manufacturer | Quantity |
|---- |----------- |------------------------ |------------ |-------- |


<a id="org252d51a"></a>

# Notes


## Actuators


### Stepper Motors

1.  Big

    SOYO SY42STH38-1684A

2.  Little

    Lin Engineering WO-208-13-01D-RO


### Brake

Placid Industries B5Z-24-1R Magnetic Particle Brake

-   Current control 0-0.049 A at 24 V


## Sensors


### Torque Sensor

Transducer Techniques RTS-5

-   wheatstone bridge


### Encoder

Newark HEDR-5421-EP111

-   Two channel quadrature


### Limit Switches

MiSUMi D2F-01FL

-   Normally open or normally closed


<a id="orgeca6f45"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Edit metadata.org

    make -f .metadata/Makefile metadata-edits


## Tangle metadata.org

    make -f .metadata/Makefile metadata


## Edit project

    make -f .metadata/Makefile project-edits
    exit