---
layout: page
title: exScooter
categories: Projects
permalink: /projects/exScooter
---

//----------------- Stages of project: -----------------//  
--- level 1 ---  
Hardware:  
1. Arduino Mega as ArduinoMain  
2. Arduino NANO as ArduinoRPM
3. Arduino NANO as ArduinoSpeed
4. rct time  
5. SD card reader
6. OLED
7. Atmega Fuel
8. Out temp sensor
9. Oil temp sensor
10. Button  
11. Speed sensor(magnet switch)

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
2. Cruise
 * time, date, temp
3. Sport
 * RPM, speed, oil temp
4. Drag
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
2. Cruise
 * time, date, temp
3. Sport
 * RPM, oil temp
4. Drag
 * RPM, acceleration, Speed
5. Flight
 * x angle, y angle, acceleration, break
 
 #### level 3  

Functions:  
* calculate the average of fuel consumptions from distance and fuel tank level logs
