# PiCamera
Camera that takes pictures with a set interval a set amount of minutes after detecting movement
Used in conjunction with a PIR sensor and the mqtt library to receive on and off signals when movement is detected
4 parameters are needed: 
[1] - Location where the PIR sensor will publish the message
[2] - Name of Location for picture to be stores, must end in "0001.jpg" for program to work
[3] - Amount of time after movement is detected where the camera will take photos
[4] - Interval between photos
            
