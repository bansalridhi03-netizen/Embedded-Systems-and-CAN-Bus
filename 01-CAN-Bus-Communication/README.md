# CAN Bus Communication — Arduino and ArduPilot

## Overview
This folder contains embedded programming examples exploring CAN bus communication between Arduino and ArduPilot systems using C++ and Lua scripting.

## Communication Examples

### ArduPilot to Arduino
- `canwrite.lua` — CAN message transmission from ArduPilot.
- `canflexcan.ino` — CAN message reception using Arduino and FlexCAN.

### Arduino to ArduPilot
- `canflexcansend.ino` — Experimental CAN message transmission from Arduino.
- `canread.lua` — CAN message reception using ArduPilot Lua scripting.

## Technologies
- Arduino / C++
- Lua
- ArduPilot
- FlexCAN_T4
- CAN Bus

## Notes
These are experimental communication scripts. Hardware validation and complete bidirectional communication have not been confirmed here.
