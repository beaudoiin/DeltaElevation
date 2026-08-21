# DeltaElevation
Model Elevator System. 
This device makes use of an arduino nano micro controller for logical control, a ESP32 HMI screen for Scada control. It is mamufactured with 3D printing, which features a 3-floor elevator shaft with elecator car and model floors. Electronic componenets employed are: DFMini player, Shift Registers, RTC, IIC leveler, SD reader, BT_2 motor driver and other various componenets.

#Progress as of August 20th, 2026
The current state of development for the summer of 2026 is as follows:
#Physical 
* Model car made and tested. Key issues identified.
* Load cell, elevator buttons, cabling system installed.
* Elevator car 608 bearings attached and guide rails positioned.
* Elevator shafts created and assembled.
* Limit switches installed.
* Motor mount designed and installed.
* Counterweiggt designed and installed.
* Motor movement tested

#Electronic
* Arduino core logic programmed.
* HMI screen core logic and display management programmed.
* Shift registered wired and interfaced.
* 7-Segment displays (x4) installed and functioning.
* Load cell functioning.
* DfMini player working.
* SD card working.
* Real-Time clock working.
* Power loss detector system working.
* EStop system working.
* Service mode switch working. (code to be tested).

#Next Steps (Light overview)
* Reduce wire count int cabling system
* create a wire management system to keep wires out of the way of objects jn the shaft.
* Redisgn limit switches ornother methods for checking floor locations. (Halleffect most ideal)
* Improve shaft walls with stronger interconnection and door slots.
* Itterate door frame that is connected to elevator, and the other to the floor with vigorous reating.
* Change Motor mount 10:1 ration, to 18:1 ratio.
* Create proper parametric designs by refactoring parts made quickly.
* Produce engineering drawings.
* Uodate HMI to have touch capabilities for settings. and properly display messages received via IIC.
* Addnsecondary power to allow for full power required if a bottleneck is discovered.
* Add function to discover if Motor has lost power.
* produce mechanical stop when power is lost using linear actuator and some sort of two state mechanical stop.
* Produce demonstration videos of the process and iteration process.
* Produce documentation on how yo replicate the system.
* Update this git repository
