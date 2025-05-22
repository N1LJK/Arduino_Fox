# Arduino_Fox
Arduino based Amateur Radio fox transmitter for fox hunts and amateur radio direction finding ADRF

This project uses an Arduino Nano to control a Baofeng HT for amatuer Radio Fox Hunting.
The entire fox can be housed in an Altoids tin. 

The project expects a basic understanding on how to flash an Arduino using Arduino IDE software and basic soldering/electronics.

Base concept from:  http://www.ne4ga.org/projects/arduinocontrolledfox
Initial program : Chris N4VDR
This fork: Damon, N1LJK with thanks to N4VDR for assistance

You will need DTMF.h which is found at https://github.com/DFRobot/DTMF/tree/master/dtmf

This fork is for a 368b processor.  The master is for 168 and would not loop (repeat CQ) 

Changes were made to schematic to include working capacitance values for DC blocking and to use the GPIO pins and not the SPI/ISCP header.  Additionally the pinout for the Kenwood/Baofeng style connector was adjusted.

In my project I leeched power off the Baofeng's (larger battery has this) style DC power barrel connector to power the Arduino.  This connector is a Alinco/Kenwood connector that is a 3.5x1.35mm.  Two cables connected to a battery-less Altoids (small box) attached to a disposable radio you can hide in the woods.

I sacrificed a Baofeng earpiece (I've never used or liked them and they are included and have the necessary Audio/PTT connector).  The rest of the parts can be had for pennies.  Total cost should be well under $5 for this controller (2025).

Happy hunting.
