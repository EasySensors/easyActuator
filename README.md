![enter image description here](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_MAIN.jpg?raw=true)
![enter image description here](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_BOTTOM.jpg?raw=true)
![enter image description here](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_PCB_TOP.jpg.jpg?raw=true)
![enter image description here](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_PCB_TOP_LR.jpg?raw=true)


### The Blinds Actuator Node is actuator node for NEMA17 style steppers used in 3D printers. The board based on [The Button Size Node](https://github.com/EasySensors/ButtonSizeNode) with HopeRF RFM69-HCW radio on board and Pololu DRV8824/5 Stepper driver microcontroller (EBAN-DRV8824-5)
 
[![Blinds Actuator Driver ButtonSizeNode + DRV8825](https://github.com/EasySensors/BlindsActuatorNode/blob/master/photos/youTube.jpg?raw=true)](https://youtu.be/Nq-V5lzM5DM)

  Best suitable for automating blinds. easyBlindsActuatorNode.ino  is the Arduino example sketch using [MySensors 2.0 ](https://www.mysensors.org/) API.  This is "work in progress" project although the code and the board work nice. Will add some useful stuff like STL files for printing belt and pulley holders a bit later. 

  ------------------------------------------------------------------------

## Specification: ##

 - LoRa RFM 95 or RFM69 HCW 915/868/433 MHz radios
 - Dimensions 96mm x 61mm x 30mm
 - Supply voltage up to 9-25 Volts 3A with 5.5mm x 2.5mm Male Jack
 - FTDI  header for programming
 - Any NEMA17 4-wire motor
 - TMS2208 silent motor driver 
 - Authentication security - Atmel ATSHA204A Crypto Authentication Chip
 - Dualoptiboot bootloader. Implements over the air (OTA) firmware update ability
 - The Digital and Analog pins are 3.3 volts

------------------------------------------------------


![enter image description here](https://github.com/EasySensors/BlindsActuatorNode/blob/master/photos/setMotor.JPG?raw=true)

![enter image description here](https://github.com/EasySensors/BlindsActuatorNode/blob/master/photos/set1.JPG?raw=true)

![enter image description here](https://github.com/EasySensors/BlindsActuatorNode/blob/master/photos/setPulley.JPG?raw=true)

[**The board schematics Pdf link**](https://github.com/EasySensors/BlindsActuatorNode/blob/master/KiCad/blindsActuator.pdf)



