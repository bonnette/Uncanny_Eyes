# Uncanny Eyes
 Modification of Adafruit Uncanny Eyes for the SSD1331 display <br/>
![Client Photo](https://github.com/bonnette/Uncanny_Eyes/blob/master/photos/eye_teensy.jpg)
<br/>
This is a modification of the Adafruit Uncanny Eyes sketch Written by Phil Burgess <br/>
https://github.com/adafruit/Uncanny_Eyes <br/>
My modification allows you to use the Adafruit 0.96 inch mini color OLED (using the Adafruit_SSD1331 driver)<br/>
This repository contains a defaultEyes1.h file that modifies the graphics table so the eye fits into the smaller (96X64) display.<br/>
The newest version works with the Teensy 3.2 and the Trinket M0 and has a config.h file like the original one from Adafruit. It works with two eyes and doesn't step on code from the original author <br/>
The "convert" directory contains the modified "tablegen.py" file that I modified to allow any size graphics to be used to create the HEX ".h" files.<br/>
I have also included my graphic files that I modified from the original to fit the 96X64 display (defaultEye only). They are the files with the "1" appended to the end of each file name.
<br/><br/>I want to thank Adafruit for providing the code and drivers for this modification and would encourage everyone to show your support for their efforts by making purchases of the hardware necessary to complete this project from Adafruit.
