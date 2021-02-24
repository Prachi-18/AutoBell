# AutoBell

Name: Prachi Modi

# Project Overview
Automatic doorbell with the following functionalities:

1)Automatic bell: Bell rings automatically for a fixed time period when someone stands at the door using Ultrasonic sensor.

2)Guest Notification: Using Blynk app, the homeowner receives notification in their mobile phone 
that a guest has arrived. 

3)Guest Picture Notification: Attached with the sensor is an esp32 camera that takes the picture of the visitor, and sends it to the Blynk app via FTP server. So the homeowner can 
also instantly check the identity of the visitor on their mobile.

# Materials used
ESP32 Cam board.
A mobile phone with a Blynk app
Servo motors 
Neopixel rings

# Setup
The code has been implemented using C .The images have been hosted using 000webhost. The blynk app then accesses the URL since it is public.

# Issues
The image captured by esp32 camera comes up corrupted some times.


