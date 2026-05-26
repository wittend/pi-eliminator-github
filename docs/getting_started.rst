Getting Started
===============

This section guides you through setting up and using the Pi-Eliminator hardware and software.

System Setup
------------

The Pi-Eliminator is designed to work with Raspberry Pi-compatible setups, but it is specifically intended to enable the use of NUC-style computers (like Beelink) and standard laptops with existing data collection hardware.

Prerequisites
-------------

To work with the design files, you will need:

* KiCad 7.0 or newer.
* Manufacturing files (located in the `production/` directory).

Hardware Assembly
-----------------

1. **PCB Fabrication**: Use the provided Gerber files in `production/` to order your PCBs.
2. **Component Sourcing**: Refer to the `production/bom.csv` for the Bill of Materials.
3. **Assembly**: Solder the components following the schematic and PCB layout.

Software Setup
--------------

1. **Installation**: Follow the platform-specific instructions to install the necessary drivers and interface software.
2. **Configuration**: Configure the software to recognize the Pi-Eliminator and connected magnetometer hardware.

Connection
----------

The Pi-Eliminator features a 2x20 pin header, allowing it to interface with devices that typically connect to a Raspberry Pi's GPIO header.
