# Firmware

Firmware for the BatteryCharger_12V controller.

## Development Environment

The firmware is developed for the ATmega328P using the
Arduino / VisualMicro development environment.

## Main Firmware

- BatteryCharger_12V.ino

The charging parameters and hardware limits are defined in parameter
blocks at the beginning of the source code.

No EEPROM-based configuration menu is used. The charger is intended
for fixed installation, and charging parameters are adapted in the
firmware when required for a different battery type or application.

## Diagnostics

The UART interface remains available for monitoring and diagnostics.

Available commands:

- `D0` - Disable continuous debug output
- `D1` - Enable continuous debug output
- `P`  - Print current charger status once
- `?`  - Show command help
- `R`  - Reboot the controller

Diagnostic warnings do not automatically stop the charger.
Protection functions may interrupt charging when required to protect
the battery or DC/DC converter.
