# SuperRaspi8
Autonomus Digital super 8 cartridge 

## Introduction
The SuperRaspi8 is yet another Raspberry Pi based digital super 8 cartridge, but with a Twist !
It will be the first entierly autonomous cartridge. No phone, no internet connection to control the recording of the video.
The cartridge will work directly with the buildin camera motor and trigger.


![alt text](https://github.com/quentintamar/SuperRaspi8/blob/main/whatsinside.png?raw=true)

 **1** : Custom 3d printed Super8 Cartridge that fit every super8 camera
 
 **2** : Raspberry pi Zero
 
 **3** : Raspberry Pi Zero W Camera
 
 **4** : USB key for stocking video files and quickly transfer them to a computer
 
 **5** : Battery pack
 
 **6** : Some part to make the camera autonomous that i will make public when the documentation will be ready ;)

## The Twist : 

Most of the other Raspberry powered super 8 camera uses Wireless of added button to trigger and stop the recording of the videos, my wish was to develop a cartridge that use the internal motor and trigger. So i had to use the rotation of the motor. 

i 3D printed a "wheel" (**2**) , close the the original system, that revolve from inside the cartridge with the motor of the camera (**4**)

A small but strong magnet (**1**) is attached to that wheel and revolve with it. 

On every revolution it passes by a Hall Effect sensor (magnetic sensor) (**3**) connected to the raspberry pi.

On lauch the raspberry start a script that calculate how many time the magnet trigger the Hall sensor, and if the sensor is triggered on a specified frequence, the camera start recording. if the sensor isnt triggered ( caused by the motor not moving anymore) the video recording is stopped.

Multiples variable in the script are use to define and refine the latence of the system. 




![alt text](https://github.com/quentintamar/SuperRaspi8/blob/main/motorv1.png?raw=true)



## Progression
The project is still in early developpement but the biggest feature (using the building trigger to control recording) is already in an advanced stage. 
the first draft of the Program and the first practical prototype of the systeme are already promising and show that the project is doable. 

##


