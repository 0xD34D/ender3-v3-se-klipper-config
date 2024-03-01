# ender3-v3-se-klipper-config
---
## What works
- X, Y, Z and extruder steppers
  - TMC2209 UART control for X, Y, and Z
- X, Y endstops
- CR touch probe
- Heated bed & temp sensor
- Hotend & temp sensor
- Heatsink fan
- Parts cooling fan
- Beeper

## What doesn't work
- Load cell for auto Z-offset calibration
  - Works with a custom fork of klipper, see https://github.com/0xD34D/klipper_ender3_v3_se
- TFT display
- ???? Did I miss anything?
