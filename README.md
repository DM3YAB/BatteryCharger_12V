# BatteryCharger_12V

12 V DC battery charger with configurable charge profile, power-source management and protected DC/DC control.

## Project Overview

BatteryCharger_12V is a microcontroller-controlled DC battery charger developed as the base project of a modular battery charger family.

The charger is designed for stationary integration into a battery system. Charging parameters are defined directly in the firmware and can therefore be adapted to different battery types without requiring a configuration menu during normal operation.

The project combines battery charging, source management, DC/DC converter protection and thermal management in one controller.

## Main Features

- 12 V battery charging
- Configurable battery charging parameters
- Bulk, absorption, full and optional float charging
- Three DC power inputs:
  - Low Power: up to 3 A
  - Mid Power: up to 10 A
  - High Power: up to 30 A
- Automatic input priority: High → Mid → Low
- Maximum DC/DC converter power: 350 W
- DC/DC pre-charge and output verification
- Reverse-current detection
- Temperature monitoring of MOSFETs and inductor
- Temperature-dependent power reduction
- Active cooling during charging with temperature-controlled fan run-on
- UART monitoring and diagnostics

## Project Status

Development and testing in progress.

This repository starts the consolidated development line of the charger family.  
Further variants, including 24 V and MPPT chargers, will follow based on the experience gained with this version.
