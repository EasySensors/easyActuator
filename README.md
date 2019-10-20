![enter image description here](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_MAIN.jpg?raw=true)
![enter image description here](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_BOTTOM.jpg?raw=true)
![enter image description here](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_PCB_TOP.jpg?raw=true)
![enter image description here](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_PCB_TOP_LR.jpg?raw=true)

### The easyActuator is based on TMC2208 silent stepper driver. It can control stepper motor and is capable of driving up to 2A of current from each output. The board controlled with with Lora RFM95 or RFM69-HCW radio 

[![Blinds Actuator Driver ](https://github.com/EasySensors/BlindsActuatorNode/blob/master/photos/youTube.jpg?raw=true)](https://youtu.be/Nq-V5lzM5DM)

EasyblindsActuatorNodeTMC2208AccelStepper.ino  is the Arduino example sketch using [MySensors 2.x ](https://www.mysensors.org/) API.  
Libs used. The Sketch basically is the code for controlong blinds. It memrizes 2 postions and can be controlled with buttons or by controller like Domoticz.

AccelStepper credit to airspayce http://www.airspayce.com/mikem/arduino/AccelStepper/classAccelStepper.html#a5dce13ab2a1b02b8f443318886bf6fc5 
 
TMCStepper credit to Teemu Mäntykallio 
https://github.com/teemuatlut/TMCStepper
  
Comes with some useful stuff like STL files for printing belt and pulley holders. Can be used for driving ikea vidga track rails and gardina rails. works nice and quiet.

  ------------------------------------------------------------------------

## Specification: ##

 - LoRa RFM 95 or RFM69 HCW 915/868/433 MHz radios
 - Dimensions 96mm x 61mm x 30mm
 - Supply voltage up to 9-25 Volts 3A with 5.5mm x 2.5mm Male Jack
 - FTDI  header for programming
 - Any NEMA17 4-wire motor
 - TMS2208 silent motor driver up to 2A motor current  
 - Software setup for speed and current control
 - Authentication security - Atmel ATSHA204A Crypto Authentication Chip
 - Dualoptiboot bootloader. Implements over the air (OTA) firmware update ability
 - The Digital and Analog pins are 3.3 volts

------------------------------------------------------


![enter image description here](https://github.com/EasySensors/BlindsActuatorNode/blob/master/photos/setMotor.JPG?raw=true)

![enter image description here](https://github.com/EasySensors/BlindsActuatorNode/blob/master/photos/set1.JPG?raw=true)

![enter image description here](https://github.com/EasySensors/BlindsActuatorNode/blob/master/photos/setPulley.JPG?raw=true)

[**The board schematics Pdf link**](https://github.com/EasySensors/BlindsActuatorNode/blob/master/KiCad/blindsActuator.pdf)



