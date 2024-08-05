- [About](#orgbfb5ebf)
- [Images](#org912eb98)
- [Schematic](#org0782f5f)
- [PCB](#org14a825d)
- [Bill of Materials](#orgcd1d3bb)
- [Notes](#org100e3b2)
- [Development](#orga0ec191)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="orgbfb5ebf"></a>

# About

```markdown
- Project Name: mouse_joystick_controller
- Description: Janelia mouse joystick controller for the Dudman lab experiments.
- Version: 2.0
- Kicad Version: 7.0.11
- Release Date: 2024-08-05
- Creation Date: 2017-08-14
- License: BSD-3-Clause
- URL: https://github.com/janelia-kicad/mouse_joystick_controller
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2024 Howard Hughes Medical Institute
- References:
  - https://www.kicad.org/
  - https://www.transducertechniques.com/rts-torque-sensor.aspx
  - https://placidindustries.com/products/brakes/magnetic-particle-brakes/magnetic-particle-brake-b5z/
  - https://www.newark.com/broadcom-limited/hedr-5421-ep111/encoder-incremental-2-ch/dp/58Y4773
  - https://www.linengineering.com/products/stepper-motors/hybrid-stepper-motors/208-series/208-13-01/WO-208-13-01D
  - https://www.pololu.com/product/2267
```


<a id="org912eb98"></a>

# Images


<a id="org0782f5f"></a>

# Schematic


<a id="org14a825d"></a>

# PCB


<a id="orgcd1d3bb"></a>

# Bill of Materials


## Board

|    |
|--- |
|  |


## Supplemental

| Item | Description | Manufacturer Part Number | Manufacturer | Quantity |
|---- |----------- |------------------------ |------------ |-------- |


<a id="org100e3b2"></a>

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


<a id="orga0ec191"></a>

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
