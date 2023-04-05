- [About](#org922585e)
- [Images](#org6002fee)
- [Schematic](#orge2a122c)
- [PCB](#orgf4728b8)
- [Bill of Materials](#orgd620f33)
- [Development](#org24aa909)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org922585e"></a>

# About

```markdown
- Project Name: mouse_joystick_controller
- Description: Janelia mouse joystick controller for the Dudman lab experiments.
- Version: 2.0
- Kicad Version: 7.0.1
- Release Date: 2023-04-05
- Creation Date: 2017-08-14
- License: BSD-3-Clause
- URL: https://github.com/janelia-kicad/mouse_joystick_controller
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2023 Howard Hughes Medical Institute
- References:
  - https://www.kicad.org/
```


<a id="org6002fee"></a>

# Images


<a id="orge2a122c"></a>

# Schematic


<a id="orgf4728b8"></a>

# PCB


<a id="orgd620f33"></a>

# Bill of Materials


## Board

|    |
|--- |
|  |


## Supplemental

| Item | Description | Manufacturer Part Number | Manufacturer | Quantity |
|---- |----------- |------------------------ |------------ |-------- |


<a id="org24aa909"></a>

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