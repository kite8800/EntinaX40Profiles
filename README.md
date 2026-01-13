# Entina X40 Profiles
Entina X40 Weedo X40 Profiles for OrcaSlicer/BambuStudio/PrusaSlicer
-- kitedriver

## 1.Entina X40 - OrcaSlicer Profile

[Printer]

It use printer g-code to implement tool/filament change.

[Post Processing Script]

It use a batch script to remove all comment in the g-code file.

Please set Other -> Post-processing scripts to "gcode_rmcomment_orca.bat;"

and use the comment removed g-code file to upload to Wii-builder

<img width="408" height="227" alt="Post-processing OrcaSlicer" src="https://github.com/user-attachments/assets/5852faf3-1ccc-45e4-9079-95a8f2aeebc5" />


## 2.Entina X40 - Bambu Studio Profile

[Printer]

The tool change is implemented in filament g-code to avoid "Access Violation" in Bambu Studio


[Tool Change/Filament Change]

It use Filament G-code to control tool change/filament instead of Printer G-code.

<img width="734" height="591" alt="bambu filiment gcode" src="https://github.com/user-attachments/assets/3537c671-e431-410b-9c13-160b34f13133" />



[Post Processing Script]

It use a batch script to remove all comment in the g-code file.

Please set Other -> Post-processing scripts to "gcode_rmcomment_orca.bat;"

and use the comment removed g-code file to upload to Wii-builder

<img width="399" height="290" alt="bambu post-processing" src="https://github.com/user-attachments/assets/9238f3a9-7e52-4c58-a4de-ff382e9894fe" />



## 3.Entina X40 - PrusaSlicer Profile

[Printer]

It use printer g-code to implement tool/filament change.

