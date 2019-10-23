![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_MAIN.jpg?raw=true)
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_BOTTOM.jpg?raw=true)
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_PCB_TOP.jpg?raw=true)
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_PCB_TOP_LR.jpg?raw=true)

### The easyActuator is based on TMC2208 silent stepper driver. It can control stepper motor and is capable of driving up to 2A of current from each output. The board controlled with with Lora RFM95 or RFM69-HCW radio 

Assembly video
[![easyActuator Blinds Actuator Driver ](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorAsembly.jpg?raw=true)](https://youtu.be/Id8HyUyZ3ow)

Travel with built in buttons
[![easyActuator Blinds Actuator Driver ](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorTrvelButtons.jpg?raw=true)](https://youtu.be/X3RquymTpSM)

Travel setup with built in buttons
[![easyActuator Blinds Actuator Driver ](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorTrvelSetup.jpg?raw=true)](https://youtu.be/LuTreJsuO8g)

![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorButtons.jpg?raw=true)

![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorLED.jpg?raw=true)

EasyblindsActuatorNodeTMC2208AccelStepper.ino  is the Arduino example sketch using [MySensors 2.x ](https://www.mysensors.org/) API.
The Sketch basically is the code for controlong blinds. It memrizes 2 postions and can be controlled with buttons or with smarthone by controller like Domoticz.

AccelStepper credit to airspayce http://www.airspayce.com/mikem/arduino/AccelStepper/classAccelStepper.html#a5dce13ab2a1b02b8f443318886bf6fc5 
 
TMCStepper credit to Teemu Mäntykallio 
https://github.com/teemuatlut/TMCStepper
  
Comes with some useful stuff like STL files for printing belt and pulley holders. Can be used for driving ikea vidga track rails and gardina rails. works nice and quiet.

  ------------------------------------------------------------------------

## Specification: ##

 - LoRa RFM 95 or RFM69 HCW 915/868/433 MHz radios
 - Dimensions 96mm x 61mm x 30mm
 - Power supply voltage up to 9-25 Volts 3A with 5.5mm x 2.5mm Male Jack
 - FTDI  header for programming
 - Any NEMA17 4-wire motor
 - TMS2208 silent motor driver up to 2A motor current  
 - Software setup for speed and current control
 - Authentication security - Atmel ATSHA204A Crypto Authentication Chip
 - Dualoptiboot bootloader. Implements over the air (OTA) firmware update ability
 - The Digital and Analog pins are 3.3 volts
 - Enclosure with travel and setup buttons

------------------------------------------------------

## Ikea Vidga rail kit
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorIkeaVidga.jpg?raw=true)


## Gardinia rail kit

![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/Gardinia-rail-kit.jpg?raw=true)

### Gardinia motor holder
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/setMotor.jpg?raw=true)





