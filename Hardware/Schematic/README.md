# Schematic

Circuit diagrams for the BatteryCharger_12V hardware.

## Hardware Origin

The schematics were originally developed under the project name
**WoMo-SolarMainCharge**.

During further development, the charger concept was reorganized and
BatteryCharger_12V became the first consolidated version of the new
charger project family.

For traceability, the original schematic document filenames have been retained.

## Hardware Structure

The charger electronics are divided into two interconnected boards.

### Control / Display Board

The board identified as **Display** in the original documentation contains
the controller, display interface and control electronics.

It is responsible for measurement processing, charger control,
user interface and communication.

### Power Board / Mainboard

The board identified as **PCB** or Mainboard contains the high-current
power path and the DC/DC converter.

This includes the power inputs, switching elements, current and voltage
measurement and the connection to the battery.

### Board Connection

The Control / Display Board and the Power Board / Mainboard are connected
by a ribbon cable.

The connection carries:

- control signals
- measurement signals
- supply voltage to the Control / Display Board
- supply voltage to the Power Board / Mainboard

The two-board design separates the controller and user interface from
the high-current power section.

## Schematic Documents

The PDF files in this directory contain the original circuit diagrams.

The original filenames are intentionally retained so that the relationship
between the earlier WoMo-SolarMainCharge development and the current
BatteryCharger_12V project remains traceable.
