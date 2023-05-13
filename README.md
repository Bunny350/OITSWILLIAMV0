Work in progress.

<p align=center>
    <a>
        <picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Bunny350/OITSWILLIAMV0/master/Media/Logos/logo-whitetext.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Bunny350/OITSWILLIAMV0/master/Media/Logos/logo.svg">
  <img alt="OITSWILLIAMV0" src="https://raw.githubusercontent.com/Bunny350/OITSWILLIAMV0/master/Media/Logos/logo.svg">
</picture>
    </a>
</p>

<img alt="Voron Zero printers with OITSWILLIAMV0 mods" src="https://raw.githubusercontent.com/Bunny350/OITSWILLIAMV0/For-V0.2/Media/OITSWILLIAMV0.png">

Mod Repository for Voron 0.2

# OITSWILLIAMV0

OITSWILLIAMV0 is a mod project for Voron Zero 3D printer after OITSWILLIAMV2. It comes with two different skirt themes, extended skirts and keeps some stock elements.

This mod project goes different, it is to redefine usability without making it look completely different.

## Extended skirt
OITSWILLIAMV0's main feature is the extended skirt, which adds additional 16mm not just to fit 40mm fans to cool down electronics. In front, left and right sides, it uses Trident skirts that are not scaled down, but cut down.

## As-is top hat
OITSWILLIAMV0 also contains a mod that is used to reduce waste by keeping V0.1 top hat while adding the Cam locks that are introduced for V0.2 extrusion top hat. This mod adds 15mm spacing just for hinges, is made to not use heat seat inserts and can be printed on V0's limited build volume.

## BOM requirements and replacements

### Optional (requires extended skirt)
| Stock V0  | V0 with this mod |
| ------------- | ------------- |
| NEMA17 Stepper Motor (34mm max) with integrated lead screw 200mm T8x8 | NEMA17 Stepper Motor (40mm) with integrated lead screw 200mm T8x8* |
* Without extended skirt, this replacement will not fit.

### Additional parts

<details>
  <summary>Separate parts</summary>
  
#### Back skirt
* 1x 4010 fan
* Minimum 2x or up to 4x M3x12mm BHCS

#### Extended skirt legs
* 4x M3x55mm SHCS / BHCS

#### Rosalina Theme front covers
* Both left and right
* 4x M3x6mm BHCS

#### Extended skirt display
* 2x M3x12mm BHCS instead of M3x6mm BHCS
  * M3x6mm can be kept if mounting the skirt with no display.

#### As-is top hat
* 16x M2x10mm Self-tapping screws
* 8x M3x6mm BHCS
</details>

#### Total (normal, without top hat)
* 2x M3x6mm BHCS
* 2x (without fan), 4x or 6x M3x12mm BHCS
* 4x M3x55mm SHCS / BHCS

#### Total (with Rosalina Theme, without top hat)
* 6x M3x6mm BHCS
* 2x (without fan), 4x or 6x M3x12mm BHCS
* 4x M3x55mm SHCS / BHCS

#### Total (normal, with top hat)
* 16x M2x10mm Self-tapping screws
* 10x M3x6mm BHCS
* 2x (without fan), 4x or 6x M3x12mm BHCS
* 4x M3x55mm SHCS / BHCS

#### Total (with Rosalina Theme, without top hat)
* 16x M2x10mm Self-tapping screws
* 14x M3x6mm BHCS
* 2x (without fan), 4x or 6x M3x12mm BHCS
* 4x M3x55mm SHCS / BHCS

"But can you compare with the normal V0.2?" Heck yes!

<img alt="Stock Voron 0.2 and Voron 0.2 with OITSWILLIAMV0 mod" src="https://raw.githubusercontent.com/Bunny350/OITSWILLIAMV0/For-V0.2/Media/OITSWILLIAMV0-compare.png">
As you can see, the righthand is Voron 0.2 with OITSWILLIAMV0 mod. it has the bigger Voron logo and is taller, which indicates that it uses extended skirt, which allows fit of bigger Z-axis motor. Another thing that it is different is that I modified Mini Stealthburner to reflect my mod. It is just a cosmetic mod but still Voron Mini Stealthburner.

## Other goals
This project has other goals, including:
* Single fan for side skirt
