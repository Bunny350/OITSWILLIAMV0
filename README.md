<p align=center>
    <a>
        <picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Bunny350/OITSWILLIAMV0/master/Media/Logos/logo-whitetext.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Bunny350/OITSWILLIAMV0/master/Media/Logos/logo.svg">
  <img alt="OITSWILLIAMV0" src="https://raw.githubusercontent.com/Bunny350/OITSWILLIAMV0/master/Media/Logos/logo.svg">
</picture>
    </a>
</p>
Project is being constantly updated. 

# OITSWILLIAMV0

<img alt="V0.2 + OITSWILLIAMV0 mod" src="https://raw.githubusercontent.com/Bunny350/OITSWILLIAMV0/For-V0.2/Media/v0-oitswilliamv0-p1-exs.png">

Mod Repository for Voron 0.2

* Currently featured in V0.2378[^config-on-other-side]!

OITSWILLIAMV0 is a mod project for [Voron Zero](https://github.com/VoronDesign/Voron-0) 3D printer after OitswilliamV2. It comes with two different skirt themes, extended skirts and keeps some stock elements.

This mod project goes different, it is to redefine usability without making it look completely different.

## Feature development status
| Feature        | Status |
| -------------- | ------------- |
| Extended skirt | Released |
| As-is top hat  | Released |
| Exhaust XS     | Released |
| Back skirt with ThinkBook 14s fans | Experimental, early access |

## Extended skirt
OITSWILLIAMV0's main feature is the extended skirt, which adds additional 16mm not just to fit 40mm fans to cool down electronics. In front, left and right sides, it uses Trident skirts that are not scaled down, but cut down.

### Variant with ThinkBook 14s fans mounting
This variant is the way where we make 3D printers sound different. This replaces the original's 3510 axial fans.

## As-is top hat
OITSWILLIAMV0 also contains a mod that is used to reduce waste by keeping V0.1 top hat while adding the Cam locks that are introduced for V0.2 extrusion top hat. This mod adds 15mm spacing just for hinges, is made to not use heat seat inserts and can be printed on V0's limited build volume.

## Exhaust XS
Exhaust XS is a *different* type of exhaust unit made for Voron 0. It is intended to be different in sound and the way it is used. The filter cartridge is reusable and can be built & maintained with no tools. 

## BOM requirements and replacements

### Optional (requires extended skirt)
| Stock V0  | V0 with this mod |
| ------------- | ------------- |
| NEMA17 Stepper Motor (34mm max) with integrated lead screw 200mm T8x8 | NEMA17 Stepper Motor (40mm) with integrated lead screw 200mm T8x8* |
* Without extended skirt, this replacement will not fit.

### Additional parts

* [Exhaust XS BOM](https://docs.google.com/spreadsheets/d/1qKHTR9wy5eDcJ8kGZrhbsqijIHyDv_TbETnKIMAwmbk/edit?usp=sharing)
  
* Back skirt (legacy)
    * 1x 4010 axial fan
    * 4x M3x16mm BHCS
    * 4X M3x5x4 heat-set inserts
  
* Back skirt (with ThinkBook fans)
    * 1x ThinkBook 14s cooling fan (big)
    * 6x M2x10mm self-tapping screws

* Extended skirt legs (*dc_usb-c_sbc_exhaust_extended_skirt_middle.stl* + *dc_usb-c_sbc_exhaust_extended_skirt_top.stl*)
    * 4x M3x55mm SHCS / BHCS
    * USB-C power legging
        * 1x ThinkBook 14s cooling fan (small)
        * 3x M2x10mm self-tapping screws
        * *These are not required when using with AC power inlet skirt (power-inlet-extended-skirt.stl).*

* Rosalina Theme front covers
    * Both left and right
    * 4x M3x6mm BHCS

* Extended skirt display
    * 2x M3x12mm BHCS instead of M3x6mm BHCS
    * M3x6mm can be kept if mounting the skirt with no display.

* As-is top hat
    * 16x M2x10mm self-tapping screws
    * 8x M3x6mm BHCS

<details>
  <summary>Total BOM excluding EXS</summary>

* Total (excluding EXS)
    * 2x M3x6mm BHCS
    * 2x (without fan), 4x or 6x M3x12mm BHCS
    * 4x M3x55mm SHCS / BHCS

* Total (V0.2378 Rosalina Theme, without top hat or EXS)
    * 6x M3x6mm BHCS
    * 2x (without fan), 4x or 6x M3x12mm BHCS
    * 4x M3x55mm SHCS / BHCS

* Total (normal, with top hat, excluding EXS)
    * 16x M2x10mm self-tapping screws
    * 10x M3x6mm BHCS
    * 2x (without fan), 4x or 6x M3x12mm BHCS
    * 4x M3x55mm SHCS / BHCS

* Total (V0.2378 Rosalina Theme, with top hat, excluding EXS)
    * 16x M2x10mm self-tapping screws
    * 14x M3x6mm BHCS
    * 2x (without fan), 4x or 6x M3x12mm BHCS
    * 4x M3x55mm SHCS / BHCS
</details>

"But can you compare with the normal V0.2?" Heck yes!

<img alt="Stock Voron 0.2 and Voron 0.2 with OITSWILLIAMV0 mod" src="https://raw.githubusercontent.com/Bunny350/OITSWILLIAMV0/For-V0.2/Media/OITSWILLIAMV0-compare.png">
As you can see, the righthand is Voron 0.2 with OITSWILLIAMV0 mod. it has the bigger Voron logo and is taller, which indicates that it uses extended skirt, which allows fit of bigger Z-axis motor. Another thing that it is different is that I modified Mini Stealthburner to reflect my mod. It is just a cosmetic mod but still Voron Mini Stealthburner.

[^config-on-other-side]: The configuration files for the following printers are not included in this repository, only organized, specific and cleaned-up. To get V0.2378's exact configuration files, you must be a follower of Oitswilliam Pang and then get follower-exclusive features through [this form](https://docs.google.com/forms/d/e/1FAIpQLSe9aEM7jyf0lV2PUAgOg0_tz9F7GI91byWFxUzvXsLlXambJA/viewform?usp=header). Other steps are provided from the form.
