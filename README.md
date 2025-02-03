# SPI Instrumentation Controller using Teensy 4.0

<p align="center">
<img src="./Images/Controller_T4_mounted.p400.jpg" alt="Controller_T4" width="50%" height="auto">
</p>

This is a controller tfor boards in the SPI Instrumentation project.

This board hosts a Teensy 4.0 and provides connectors for SPI, instrumentation control, 3.3V and 5V power, a precision voltage references, dedicated pins for trigger and gate input, sync and busy output and a set of pins that can be used for analog input or digital i/o.

In this repo there is a directory with FAB and BOM.   You can send the FAB files to a service such as AllPCB or PCBWay to obtain bare PCB and order parts from Digikey, and assemble with a reflow oven.   Or you can order assembled boards from either of the above.

You can order an assembled board [here at PCBWay](https://www.pcbway.com/project/shareproject/Controller_Teensy_4_0_for_SPI_Instrumentation_boards_4b27edb1.html)

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


Here is an example of how the board is used, the other two boards in this picture are the InAmp and +5V,-5V power supply.

<p align="center">
<img src="./Images/InAmpSetup.png" alt="Controller_setup" width="70%" height="auto">
</p>
