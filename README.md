![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_MAIN.jpg?raw=true)
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_BOTTOM.jpg?raw=true)
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_PCB_TOP.jpg?raw=true)
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/ACTUATOR_PCB_TOP_LR.jpg?raw=true)

## sold  here  https://www.tindie.com/products/18359/

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

## pinout

- A3  Connected to ATSHA204A - Crypto Authentication chip 
- D2  RFM95\69 DIO0 
- A2  RFM95\69 Reset pin 
- D10 RFM95\69 CS/NSS
- D11 MOSI
- D12 MISO
- D13 SCK
- D4 LEDpin
- D9 // TMC2208 DIAG
- D6 DIR
- D7 STEP
- D5 ENBL
- A5 SW_RX  // TMC2208  SoftwareSerial receive pin 
- A4 SW_TX  // TMC2208  SoftwareSerial transmit pin

- D3 travel button - "closePressed" in the code
- A0 travel button - "openPressed" in the code
- A1 travel setup button "calibrationPressed" in the code

![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorButtons.jpg?raw=true)
![easyActuator Blinds Actuator Driver](https://github.com/EasySensors/easyActuator/blob/master/pcs/easyBlindsActuatorLED.jpg?raw=true)

Libraries used:

AccelStepper credit to airspayce http://www.airspayce.com/mikem/arduino/AccelStepper/classAccelStepper.html#a5dce13ab2a1b02b8f443318886bf6fc5 
 
TMCStepper credit to Teemu Mäntykallio 
https://github.com/teemuatlut/TMCStepper
