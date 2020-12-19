# TrueStep-X1
Closed loop stepper motor driver firmware for the BTT S42B-V1.x board.  
Board version v1.1 is highly recommended to get rid of the OLED issues.  
(Board version v1.1 is a completely redesigned circuit board)
 
## Special Features - managed by spock
  - Modified version for Sidewinder X1. All default values are set. You just have to set your step size (16 by default).
  - Enhanced Menu Functionality with more Informations to be shown
  - Yes/No confirmation before it starts Calibration

**NOTE: This is still a work in progress so use with caution!**

This project was forked from the TrueStep repo (BIGTREETECH-S42B-V1.0 repo). Since I started to make some large modifications to the original work I decided to rename the project.

## General Features
- New UART [interface](SerialInterface.md) 
  - Reduced packet overheads
  - Sequence counter to detect missing packets
  - CRC checksum
- New OLED Menu
  - Simpler navigation
  - Adjustment of PID gains

To ease configuration and to access more advanced features you can use [TrueStepTerminal](utils/TrueStepTerminal).
