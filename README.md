![](pics/logo.png)

---

The Dilemma is a vertical stagger low-profile keyboard with mods.

![](pics/1n.JPG)

## Table of contents

- [Features](#features)
- [Versions](#versions)
- [Required components](#required-components)
  - [3d prints - cases](#3d-prints---cases)
  - [Electronics](#electronics)
  - [Procyon mod](#procyon-mod)
  - [Cirque Trackpad mod](#cirque-trackpad-mod)
  - [Cases](#cases)
    - [Acrylic midplate (v2 only)](#acrylic-midplate-v2-only)
  - [Metal plates](#metal-plates)
  - [Community mods](#community-mods)
  - [Build guide](#build-guide)
  - [Forks](#forks)

---

# Features

- heavy pinky stagger
- MX and choc compatible
- version with hotswap
- underglow RGB, per-key RGB
- 2 Rotary encoders on thumb clusters
- connectors for OLED, LCD

# Versions

There are multiple versions of the dilemma:


| Folder          | Name               | Size  | PCBA | Trackpad | Switches         | Additional features                     |
| --------------- | ------------------ | ----- | ---- | -------- | ---------------- | --------------------------------------- |
| `3x5_2`         | Dilemma DIY V2     | 3x5+2 | no   | Cirque   | MX, Choc V1      |                                         |
| `3x5_3`         | Dilemma V3         | 3x5+3 | yes  | Cirque   | MX, Choc V1      | Underglow, per-key RGB, rotary encoders |
| `3x5_3_hotswap` | Dilemma V3 hotswap | 3x5+3 | yes  | Procyon  | Choc V1, hotswap | Underglow, per-key RGB, rotary encoders |
| `4x6_4`         | Dilemma MAX        | 4x6+4 | yes  | Cirque   | MX, Choc V1      | Underglow, per-key RGB, rotary encoders |


# Required components

## 3d prints - cases

You can find the required 3d prints in the `mechanical` folder.

Most cases require a transparent mid layer to look good. You can either print it, or order it cut in acrylic.

## Electronics

The new revisions are made to be PCBA'd, you can find the gerber, BOM and POS files in the [Releases](https://github.com/bastardkb/dilemma/releases) section.

## Procyon mod

The `dilemma v3 hotswap` is made to work with a [Procyon PCB](https://github.com/bstiq/procyon).

## Cirque Trackpad mod

This mod uses I2C on the DIY version, and SPI on the assembled version.

The DIY version requires removing some resistors from the trackpad:

- R1
- R7 and R8 if you are using a microcontroller that runs on 5V

When installing the trackpad mod, you will need:

| Part name           | Amount | Link / source           |
| ------------------- | ------ | ----------------------- |
| M3 screw, torx, 6mm | 4      | Conrad                  |
| M3x5x5 screw insert | 4      | Aliexpress              |
| 3d printed parts    |        | See `mechanical` folder |
| 40mm cirque trackpad, curved    |        | |


If building the PCBA version, you will also need:

| Part name                                                     | Amount | Link / source |
| ------------------------------------------------------------- | ------ | ------------- |
| 12-position FPC cable, 0.5mm pitch, same side contacts, 100mm, type-B | 1      | Farnell       |


If building the DIY version, you will also need:

| Part name               | Amount | Link / source |
| ----------------------- | ------ | ------------- |
| SOD123 Resistor, 5kOhms | 2      |               |
| Cables                  |        |               |

## Cases

### Acrylic midplate (v2 only)

This case is only compatible with the assembled_v2 version !

Add an underglow effect and a beautiful view into the PCB with those acrylic midplates.

## Metal plates

Optional metal plates enables the use of tripods through magsafe magnets.

Order the [metal plates](mechanical/plates/v2/bottom_metal.dxf) in 3mm thickness. The metal needs to be *magnetized* !
Grab the appropriate DXF from the matched folder.

You will need:

| Part name              | Amount | Details           |
| ---------------------- | ------ | ----------------- |
| Metal plates           | 2      | 3mm               |
| Tripods                | 2      | Neewer Z flex     |
| Magsafe tripod adapter | 2      | Amazon/Aliexpress |

## Community mods

There are a range of community mods available (hex plates, covers...).

You can find more information in the readme in the `mechanical/community mods` folder.

## Build guide

https://docs.bastardkb.com/bg_dilemma/intro.html


## Forks

- [3x6 version](https://github.com/bstiq/Dilemma_3x6/)
- [3x5 + 3 version](https://github.com/dixls/Dilemma-3mod)