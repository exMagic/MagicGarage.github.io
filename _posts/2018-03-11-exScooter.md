---
layout: page
title: exScooter
categories: Projects
permalink: /project/exScooter
---

#### Stages of project:  
#### level 1  
Hardware:  
1. Arduino Mega as ArduinoMain  
* Arduino NANO as ArduinoRPM
* Arduino NANO as ArduinoSpeed
* rct time  
* SD card reader
* OLED
* Atmega Fuel
* Out temp sensor
* Oil temp sensor
* Button  
* Speed sensor(magnet switch)

Functions:  

* Read RPM of engine from coil wire and display it on oled the display.  
* Read speed from front wheel and display it on the display.  
* Read temperature from outside and display it on the display.  
* Read temperature from engine oil radiator and display it on the display.  
* Display time and date on the display.  
* Write all sensor's data with date and time as a row in txt file on the SD card at least two times per seconds.
* Display fuel level on the led bar

Dashboard screens:
1. Dashboard
 * time, date, RPM speed, temp, oil temp, fuel
* Cruise
 * time, date, temp
* Sport
 * RPM, speed, oil temp
* Drag
 * RPM


#### level 2  
Hardware:  
1. gyro sensor
2. log switch

Functions:  
* Read 2 axis swing angle plus 3 axis acceleration and display it on a display
* write acceleration an angles to the SD card
* write position of log switch to the SD card(easy way to mark part of readings)

Dashboard screens:
1. Dashboard
 * time, date, RPM speed, temp, oil temp, fuel
* Cruise
 * time, date, temp
* Sport
 * RPM, oil temp
* Drag
 * RPM, acceleration, Speed
* Flight
 * x angle, y angle, acceleration, break
