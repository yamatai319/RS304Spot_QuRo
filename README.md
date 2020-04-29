# RS304Spot_QuRo
Spot-like Robot by using Futaba RS304MD or RS303MR Servo. Quro named by Quadruped Robot.
This is only for assembly with RS304MD or RS303MR Servo, M5Stack and M5StickV. If you need to mount sensors or batteries, you have to modify STEP files.

## Image
![Stand View](/Image/RS304Spot_Stand.png)
![Stand View2](/Image/RS304Spot_Stand2.png)
![Down View](/Image/RS304Spot_Down.png)

## Files
- Image: Image Files
- STEP_STL:3D Files(STEP and STL)
- RS304Spot V*.f3z:Fusion360 data.

## For Assembly
### STEP/STL Files
- "Body_Center/Body_CenterMain_Separate" is what to separate "Body_CenterMain". It is for the case that 3D Printing is not good to print "Body_CenterMain".
- There are 3 type of "Body_Center/Body_Upper Cover". Chose 0ne for your purpose.
  -  Body_Cover: It is Normal one. There are no parts to fix something.
  - Body_Cover_M5Stack: It mounts M5Stack inside of it's body.
  - Body_Cover_M5StackProt: It mounts M5Stack on it's body. It is easier to connect USB and pin.
- These parts need to make 2pcs each.
  - Body_Center/Body_Lib
  - Shoulder/ShoulderMain_Left
  - Shoulder/ShoulderMain_Right
  - Shoulder/ShoulderTopCover_Left
  - Shoulder/ShoulderTopCover_Right
- These parts need to make 4pcs each.
  - All files under "LegUnder"
  - All files under "LegUpper"
  - Shoulder/ShoulderWireCover
  - Shoulder/ShoulderCover

### Parts
- x12 Futaba RS304MD or RS303MR Servo.
- x12 M2 6mm Flat Head Screw and Nut (To fix Front/Back Main to there Base)
- x96 M2 4mm Flat Head Screw (To fix servo horn)
- x102(maybe) M2 8mm or 6mm Flat Head Tapping Screw
- M5Stack and M5StickV if you need.

### Others
- "LegUnder/Fott" is recomended to print by TPU.

## Author's blog
https://prototype09.com/

## Licence
Copyright (c) 2020 Yamatai
[Released under the MIT license](https://opensource.org/licenses/mit-license.php)
