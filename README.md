This repository is a fork of FloppidyDingo's original project.

The models included here are dimensional adjustments of the original designs to address fitment issues encountered on my own SCPH-70002 console.

## Modified Models

This fork includes two optional modified models based on my own testing. Please note that these issues may be specific to my printer, print settings, material, or console. I recommend trying the original models first before using these modified versions.

### 1. PS2 Laser Ribbon Shield V5 Screw -0.2 mm Shield

On my printer, the original `PS2 Laser Ribbon Shield V5 Screw.stl` worked correctly when first installed, but after a few days the PLA version developed permanent upward warping due to material creep. The warped shield eventually interfered with the optical pickup's movement.

Reprinting the part in PETG eliminated the creep issue, but PETG's lower stiffness allowed the ribbon cable to push the shield upward during installation, which also caused interference with the optical pickup.

To address this, I lowered the ribbon shield by **0.2 mm**. When printed in **PETG** and attached using **3M transfer adhesive (such as 3M 467MP)** on the shield side, the modified model has worked reliably in my testing.

### 2. PS2 Laser Guard +0.2 mm Legs

On my console, the original `PS2 Laser Guard.stl` positioned the guard slightly too low, causing it to rub against the optical pickup during movement.

The modified version increases the height of the two support legs by **0.2 mm** while preserving the original mounting features, including the locating pin, screw recess, and chamfers.

### Notes

These modifications were made specifically to compensate for issues I experienced on my setup.

Possible causes include:

- Printer dimensional accuracy
- Material shrinkage
- Print orientation
- Layer height
- Different PS2 tolerances

For this reason, I recommend trying the **original models first**. If you experience the same issues, these modified versions may be helpful.
For a fully reversible installation, I recommend using the screw-mounted version instead of the super glue version whenever possible.

# PS2-Disk-Saver

A PS2 Slim mod that fixes an issue where the laser ribbon peels up and scratches your disks

If you are printing from this source, you will need to print one of Laser Guard.stl and one of either Ribbon_Shield_V5.stl or Ribbon_Shield_V5_Screw.stl

Installation instructions here: https://github.com/FloppidyDingo/PS2-Disk-Saver/wiki/Installation-Instructions

You can buy premade kits here: https://www.etsy.com/listing/1260716684/playstation-2-disk-saver-ribbon-shield
