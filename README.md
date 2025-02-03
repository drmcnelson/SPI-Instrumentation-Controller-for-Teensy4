# SPI Instrumentation Controller using Teensy 4.0

<p align="center">
<img src="./Images/Controller_T4.jpg" alt="Controller_T4" height="260px">
<img src="./Images/Controller_T4_mounted.p400.jpg" alt="Controller_T4" height="260px">
</p>

Controller board for the SPI Instrumentation project, hosts a Teensy 4.0 and provides connectors for SPI, instrumentation control, 3.3V and 5V power, a precision voltage references, dedicated pins for trigger and gate input, sync and busy output and a set of pins that can be used for analog input or digital i/o.   The connectors are identified in images below.

## Connectors

The following shows the location of the pins for the SPI interface circled in red.

<p align="center">
<img src="Images/T4Controller_SPIPins.png" alt="Controller_T4_SPI" width="30%" height="auto">
</p>

The following shows the location of the pins for interfacing to the Linear CCD SPI boards, circled in red.

<p align="center">
<img src="Images/T4Controller_LCCDPins.png" alt="Controller_T4_LCCD" width="30%" height="auto">
</p>

The following shows the location of the pins for trigger and gate input and sync and busy output, circled in red.

<p align="center">
<img src="Images/T4Controller_SynchronizationPins.png" alt="Controller_T4_LCCD" width="30%" height="auto">
</p>

## Example use
Here is an example of how the board is used, the other two boards in this picture are the InAmp and +5V,-5V power supply.

<p align="center">
<img src="./Images/InAmpSetup.png" alt="Controller_setup" width="70%" height="auto">
</p>

## Obtaining boards

This repo includes files for FAB and assembly. 

You can [order assembled boards from PCBWAY here](https://www.pcbway.com/project/shareproject/Controller_Teensy_4_0_for_SPI_Instrumentation_boards_4b27edb1.html).

To assemble the board yourself you will need a reflow oven.  You can order bare boards from a sevice such as PCBWay or AllPCB, and use the BOM spreadsheet file to order parts from Digikey

