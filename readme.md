pixelFrame
==================
This Arduino source code is forked from Game Frame (https://github.com/jerware), a pixel display available from LEDSEQ.COM.

The target is a blank AtMega328 IC with Arduino compatible bootloader.
16x16 pixel 24bit bitmap (BMP) images stored on an SD Card, are displayed on the matrix.

It compiles under Arduino 1.0.6 and 1.5.8, and requires the following libraries:

SPI (Distributed with Arduino IDE).
EEPROM (Distributed with Arduino IDE).
RTClite (available in this repository).
IniFileLite (available in this repository).
FastLED 3.0.1 (https://github.com/FastLED).
SdFat (The old version is no more, a copy is available in this repository).

Clock
=======

If you have "clock" firmware installed, this feature will be enabled in the menu. Once the clock is set, it will show brief, periodic animations according to the timer setting in the menu. For instance, if your timer is set to 1 minute, the clock will show an animation at the top of every minute. (Note: when not using the clock, the timer has a different function; controlling how long each animation is shown.)

The clock has additional settings that can be tuned using the clock.ini file on the microSD inside the /00system folder.
