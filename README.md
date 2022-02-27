# BLU-03-Marlin-LVGL
Two Tress Bluer (BLU-3) Marlin LVGL 


Change log:
* Feb 27 - 2022 - Marlin 2.0.8.2 Stable and Robin Nano v1.3  files: No bltouch suport
* Jun 6 - 2021 - Marlin 2.0.8.2 Stable
* March 3 - 2021 - Build for Bug Fix


Note: Please perform PID Tune for E and Bed before print

For gcode preview you will need to install mks wifi plugin in cura. (no need wifi module)

https://marketplace.ultimaker.com/app/cura/plugins/Jeredian/MKSWifiPlugin

This is an still working in progress, based on official Marlin not MKS build.

Based on official config from:
https://github.com/MarlinFirmware/Configurations/tree/import-2.0.x/config/examples/Two%20Trees/BlueR


Bluer Versions:
BlueR V1 : First version of BlueR with a metal extruder.
BlueR V2 : (Formerly "BlueR" out of the box.) BMG extruder with Blue parts and integrated endstop for X and Z.
BlueR V3 : (Formerly "BlueR V2" out of the box.) BMG extruder and more Black parts as your predecessor.


Disabled function,  not been implemented yet on LVGL

FILAMENT_RUNOUT_SENSOR 
POWER_LOSS_RECOVERY

## Compare between Robin Nano V1.2 and V1.3
| ITEMS      |  Robin Nano V1.2  | Robin Nano V1.3 | Robin Nano-S V1.3 |
|------------|--------------------|--------------------|--------------------|
| MCU        | STM32F103VET6(72MHz) | STM32F407VET6（168MHz）| STM32F407VET6（168MHz）|
| FLASH/RAM | 512KB FLASH/64KB RAM | 512KB FLASH/192KB RAM | 512KB FLASH/192KB RAM |
| Drivers | Pluggable | Pluggable | 4 TMC2225 standard mode + 1 Pluggable|
| Firmware offset | 7000 | 8000 | 8000 |

How to install:
Copy content of asset folder and Robin_nano35.bin to the SD card, reboot the machine and enjoy.


