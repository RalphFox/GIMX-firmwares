GIMX Firmware for PS4 AND PS3
====
WARNING:This is still untested! Will test as soon as possible(within a week from the commit of this file.)

This is a hybrid firmware for GIMX both working on PS3 and PS4.

It is still in early stages, i simply merged the two sources together.

Future updates include reusing functions instead of just copypasta.

-Default is set to PS4. 

-To enable PS3 just add a pullup resistor (add a 1k resistor from + to PIN7)
 
 without anything, it will run as a PS4 joystick emulator.
 
 You can add a switch if you want too, just add it like this:
 
![connection](http://www.gammon.com.au/images/Arduino/SwitchesTutorial/switch_tutorial2.png)

On this design it is set to 8, but you should connect it to whichever pin you defined as the toggle.

TODO: change schematic to pullup instead of pulldown(a lot safer)
