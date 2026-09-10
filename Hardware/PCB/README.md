# PCB

PCB documentation for the BatteryCharger_12V hardware.

## Hardware Origin

The PCB was originally developed under the project name
**WoMo-SolarMainCharge**.

During further development, the charger concept was reorganized and
BatteryCharger_12V became the first consolidated version of the new
charger project family.

For traceability, the original PCB document filenames have been retained.

## Board Structure

The hardware is divided into two PCBs:

### Control / Display Board

The board identified as **Display** in the original PCB filenames contains
the controller, display interface and control electronics.

### Power Board / Mainboard

The board identified as **PCB** in the original filenames contains the
main power path and the DC/DC power stage.

### Board Connection

Both boards are connected by a ribbon cable.

The ribbon cable carries:

- control and measurement signals
- supply voltage to the Control / Display Board
- supply voltage to the Power Board / Mainboard

This separation keeps the control electronics physically separated from
the high-current power section.

## PCB Documents

### Power Board / Mainboard

- WoMo-SolarMainCharge-PCB-TOP.pdf
- WoMo-SolarMainCharge-PCB-Bottom.pdf

### Control / Display Board

- WoMo-SolarMainCharge_Display-PCB-TOP.pdf
- WoMo-SolarMainCharge_Display-PCB-Bottom.pdf
