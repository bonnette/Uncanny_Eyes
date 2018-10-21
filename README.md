# Uncanny Eyes
Adafruit Uncanny Eyes modification for SSD1331<br/>
![Client Photo](https://github.com/bonnette/Uncanny_Eyes/blob/master/photos/eye_teensy.jpg)
<br/>
This is a modification of the Adafruit Uncanny Eyes sketch Written by Phil Burgess <br/>
https://github.com/adafruit/Uncanny_Eyes <br/>
My modification allows you to use the Adafruit 0.96 inch mini color OLED (using the Adafruit_SSD1331 driver)<br/>
This modification removes the need for a config.h file. It also contains a defaultEyes1.h file that is used to modify<br/>
the graphics table so the eye fits into the smaller (96X64) display.<br/>
I stripped out the code for the Trinket M0 so it only works with a teensy. I am sorry I did that. I may go back and add it back in later.<br/>
It only works with one eye at this time. I will try to fix that as well. <br/>
Additionally I modified the tablegen.py file to allow conversion of non 128X128 displays.<br/>
The modifications to the png files that I used to creat the new defaultEyes1.h file are also included in this repository<br/>
I want to thank Adafruit for providing the code and drivers for this modification and would encourage everyone to show your support  for their effort by making purchases of the hardware necessary to complete this project from Adafruit. 
