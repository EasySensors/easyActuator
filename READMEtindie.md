![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_MAIN.jpg?raw=true)
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_BOTTOM.jpg?raw=true)
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_PCB_TOP.jpg?raw=true)
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_PCB_TOP_LR.jpg?raw=true)

### The easyActuator is based on TMC2208 silent stepper driver. It can control stepper motor and is capable of driving up to 2A of current from each output. The board controlled with with Lora RFM95 or RFM69-HCW radio 

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

##### easyDriver and the Kits come without power supply since AC plugs regionally dependent and we have no stock at the moment for international 3A power supplies.  3A\12 DC  LED driver power supply will work. connector type is with 5.5mm x 2.5mm Male Jack.


Beside radio type selection you  can buy on of the Kits with 3D printed parts and 2 pulleys and 10 meters GT2 belt. Also psooible to add NEMA17 motor.

### Purchase options "motor Actuator":

- only one actuator - no power supply  
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorButtons.jpg?raw=true)
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorLED.jpg?raw=true)

### Purchase options "Ikea Vidga 3D printed kit with 10 m GT2 belt and pulley":

- One actuator
- Motor pulley 16 tooth.  
- Pulley
- Tensioner for pulley.  3D printed  
- Belt lock.  3D printed   
- Oposite holder.  3D printed  
- 2 pulling straps
- GT2 belt 10 m 

The kit can turn the Vidga curtain track system into motorized curtian. Works nice and quiet.
No power supply.

![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/Ikea-Vidga-3D-printed-kit-with-10m-GT2-belt-pulley.JPG?raw=true)

### Purchase options "Ikea Vidga 3D printed kit with 10 m GT2 belt, pulley and NEMA17 stepper motor":

Same as above but with NEMA17 stepper motor. No power supply.

![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/Ikea-Vidga-3D-printed-kit-with-10m-GT2-belt-pulley-NEMA17-stepper-motor.JPG?raw=true)

### Assembly video
[![easyActuator Blinds Actuator Driver ](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorAsembly.jpg?raw=true)](https://youtu.be/Id8HyUyZ3ow)

### Travel with built in buttons
[![easyActuator Blinds Actuator Driver ](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorTrvelButtons.jpg?raw=true)](https://youtu.be/X3RquymTpSM)

### Travel setup with built in buttons
[![easyActuator Blinds Actuator Driver ](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorTrvelSetup.jpg?raw=true)](https://youtu.be/LuTreJsuO8g)

### Purchase options "Gardinia 3D printed kit with 10 m GT2 belt and pulley": 

- One actuator
- Motor pulley 16 tooth.  
- Pulley
- Tensioner for pulley.  3D printed  
- Belt lock.  3D printed   
- Oposite holder.  3D printed  
- 2 pulling straps
- GT2 belt 10 m 

The kit can turn the Gardinia curtain rail system into motorized curtian. Works nice and quiet.
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/Gardinia-3D-printed-kit-with-10m-GT2-belt-pulley.JPG?raw=true)

### Purchase options "Gardinia 3D printed kit with 10 m GT2 belt, pulley and NEMA17 stepper motor": 

Same as above but with NEMA17 stepper motor. No power supply.

![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/Gardinia-3D-printed-kit-with-10m-GT2-belt-pulley-NEMA17-stepper-motor.JPG?raw=true)


### Gardinia travel with smartphone
[![easyActuator Blinds Actuator Driver ](https://github.com/EasySensors/easyActuator/blob/master/pcs/Gardinia-domoticz-video.JPG?raw=true)](https://youtu.be/hb2mV11XRAE)


EasyblindsActuatorNodeTMC2208AccelStepper.ino (Source Code link)  is the Arduino example sketch using [MySensors 2.x ](https://www.mysensors.org/) API.
The Sketch basically is the code for controlong blinds. It memrizes 2 postions and can be controlled with buttons or with smarthone by controller like Domoticz.

Libraries used:

AccelStepper credit to airspayce http://www.airspayce.com/mikem/arduino/AccelStepper/classAccelStepper.html#a5dce13ab2a1b02b8f443318886bf6fc5 
 
TMCStepper credit to Teemu Mäntykallio 
https://github.com/teemuatlut/TMCStepper
