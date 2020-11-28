# TrueStep
Closed loop stepper motor driver firmware for the BTT S42B-V1.0 board.

## Special Features
  - Modified version for Sidewinder X1 all default values are set. You just have to set your step size (16 by default). done by spock
  - Enhanced Menu Functionality with more Informations to be shown
  - Prevents starting Calibration by accident with Yes/No confirmation

**NOTE: This is still a work in progress so use with caution!**

This project was forked from the BIGTREETECH-S42B-V1.0 repo. Since I started to make some large modifications to the original work I decided to rename the project.

## General Features
- New UART [interface](SerialInterface.md) 
  - Reduced packet overheads
  - Sequence counter to detect missing packets
  - CRC checksum
- New OLED Menu
  - Simpler navigation
  - Adjustment of PID gains

To ease configuration and to access more advanced features you can use [TrueStepTerminal](utils/TrueStepTerminal).
