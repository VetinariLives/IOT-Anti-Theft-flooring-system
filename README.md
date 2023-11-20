# IOT Anti-Theft Flooring System 

Project for CSC 4980 - Security in IOT (Fall'23). This project uses a Raspberry Pi to implement an Anti-Theft Flooring System over a CoAP server.

## Objective

- Developing a Theft Detection System IoT application
- Implementing multiple detection modes
- Knowledge on Raspberry Libraries for proper resource/sensor implementation
- Interfacing Raspberry Buzzer Sensor and Camera Module over CoAP
- Invoking SimpleCV in order to analyze images 


## Schematics

[![Image from Gyazo](https://i.gyazo.com/d7289e3a56fdc7bc7c7f543573394169.png)](https://gyazo.com/d7289e3a56fdc7bc7c7f543573394169)

## Raspberry Pi Modules Used

- Raspberry Pi Camera Module
- ADS 1115 Chip
- Piezo-electric sensors
- Servo motor


## Built With

* [CoAPthon](https://github.com/Tanganelli/CoAPthon) - CoAP python library
* [PiCamera](https://picamera.readthedocs.io/en/release-1.13/) - For camera module Interfacing 
* [Adafruit CircuitPython ADS1115](https://github.com/adafruit/Adafruit_CircuitPython_ADS1x15) - For interfacing with ADS chip

## Demonstration
[![Link](https://i.gyazo.com/b10ca03759024acad1e69eb6c167c56c.png)](https://www.youtube.com/watch?v=uYGOCEKzvzU&feature=youtu.be)

## Authors

* **Abdul Shoaib Mohammed**
* **Muhammad Sameer**
* **Talha Ansari**


## Acknowledgments

* Professor - Dr. Haoxin Wang

## Pi Setup
### To run pip3 commands:
```bash
sudo apt-get install python3-pip
sudo rm /usr/lib/python3.11/EXTERNALLY-MANAGED
```
### To install Adafruit CircuitPython ADS library:
```bash
pip3 install adafruit-circuitpython-ads1x15
```
```bash
raspi-config
```
