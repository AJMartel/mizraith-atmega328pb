# Arduino Atmega328PB Package by mizraith

This package lets you compile your code for the Atmel Atmega328PB Microcontroller
using the Arduino build environment.  There is no additional compiler needed. 

### Requirements 
Arduino IDE 1.6.9 or higher which contains avr-gcc in Version 4.9.2

### Install
Copy this link into your Arduino IDE under Preferences:

**https://raw.githubusercontent.com/mizraith/mizraith-atmega328pb/master/package_mizraith_atmega328pb_index.json**

Run "Board Manager" -> Contributed -> Atmega328PB -> _Install_

### Hardware

This package is intended to support mizraith's boards.  Thanks amoehl for
the template!  Modify for your own use, of course.


### Gripes
Simply modifying amoehl's file set for distribution was a long process.  The
folks at Arduino made it convoluted and provided barely enough documentation
and IDE feedback to help one succeed.  What should have taken 5 minutes (since
all I was doing was modifying board names) has taken an hour.

### Notes
This file set was created on a mac. 
   The stuff was all throwin into a 1_0_0 folder then compressed.
   Macintrash was removed with  ` zip -d myzip_pack_1.0.0.zip "__MACOSX*" ` 
   and ` zip -d myzip_pack_1.0.0.zip ".DS_Store" ` 
   To calculate the SHA-256 checksum, `shasum -a 256  myzipfile.zip` was used.  This 
   shasum is then included back into the .json file.
   

