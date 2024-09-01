![](pics/logo.png)

<div align="center">

![GitHub Issues](https://img.shields.io/github/issues/bastardkb/dilemma?style=for-the-badge)
![GitHub License](https://img.shields.io/badge/license-CERN%20OHL%20V2-lightgrey?style=for-the-badge)
</div>

---

The Dilemma is a vertical stagger low-profile keyboard with mods.

![](pics/1k.jpg)

## Table of contents

- [Features](#features)
- [Versions](#versions)
- [Required components](#required-components)
  - [3d prints - cases](#3d-prints---cases)
  - [Electronics](#electronics)
  - [Hardware - trackpad mod](#hardware---trackpad-mod)
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


| Folder          | Name               | Size  | PCBA  | Switches         | Additional features                     |
| --------------- | ------------------ | ----- | ----- | ---------------- | --------------------------------------- |
| `3x5_2`         | Dilemma DIY V2     | 3x5+2 | no    | MX, Choc V1      |                                         |
| `3x5_3`         | Dilemma V3         | 3x5+3 | yes   | MX, Choc V1      | Underglow, per-key RGB, rotary encoders |
| `3x5_3_hotswap` | Dilemma V3 hotswap | 3x5+3 | yes   | Choc V1, hotswap | Underglow, per-key RGB, rotary encoders |
| `4x6_4`         | Dilemma MAX        | 4x6+4 | yes   | MX, Choc V1      | Underglow, per-key RGB, rotary encoders |


# Required components

## 3d prints - cases

You can find the required 3d prints in the `mechanical` folder.
For the Dilemma V3, the `cases/3x5_3_hotswap` folder contains all the required prints.  

## Electronics

The new revisions are made to be PCBA'd, you can find the gerber, BOM and POS files in the [Releases](https://github.com/bastardkb/dilemma/releases) section.


## Hardware - trackpad mod

This is the first mod made for the keyboard - so it can function as a standalone input device.

When installing the trackpad mod, on top of the 3d prints you will need:

| Part name                                                     | Amount | Link / source           |
| ------------------------------------------------------------- | ------ | ----------------------- |
| M3 screw, torx, 6mm                                           | 4      | Conrad                  |
| M3x5x5 screw insert                                           | 4      | Aliexpress              |
| 3d printed parts                                              |        | See `mechanical` folder |
| 40mm cirque trackpad, curved                                  | 1      |                         |
| 12-position FPC cable, 0.5mm pitch, same side contacts, 100mm | 1      | Farnell                 |


## Metal plates

Optional metal plates enables the use of tripods through magsafe magnets.


![](pics/1m.jpg)

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

![](pics/1i.jpg)

## Build guide

https://docs.bastardkb.com/hc/en-us/sections/6848232395410-Dilemma


## Forks

- [3x6 version](https://github.com/bstiq/Dilemma_3x6/)
- [3x5 + 3 version](https://github.com/dixls/Dilemma-3mod)
