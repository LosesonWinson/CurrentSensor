# Build instructions for the Current Sensor

## Table of Contents
1. [Record Progress of the Project](#Record-Progress-of-the-Project)
2. [Introduction using a system diagram](#Introduction-using-a-system-diagram)
3. [Creating a Budget](#Creating-a-Budget)
4. [Total Time Commitment](#Total-Time-Commitment)
5. [Mechanical Assembly](#Mechanical-Assembly) 
6. [PCB/Soldering](#PCB/Soldering)
7. [Power Up](#Power-Up)
8. [Unit Testing](#Unit-Testing)
9. [Production Testing](#Production-Testing)
10. [Reproducible?](#Reproducible?)

### Record Progress of the Project
Building this project will require time and commitment and I believe the best way to keep track of this progress is to write it to a blog. 
In other words, to set up a website and using GitHub to host it. 

### Introduction using a system diagram
![Schematic Diagram](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/sysdia.png)
This schematic diagram will help assist in replicating CurrentSensor. The purpose of this project is to detect current.

### Creating a Budget
The total budget to create this project will cost $127.30 if I already had the breadboard and the jumper wires. If you don't have a breadboard and jumper wires it would cost $146.30.
1. Raspberry Pi 3, $112.99 - <https://www.amazon.ca/CanaKit-Raspberry-Complete-Starter-Kit/dp/B01CCF6V3A/ref=sr_1_5?s=pc&ie=UTF8&qid=1516324581&sr=1-5&keywords=Raspberry+Pi+3>

2. Devantech Pixel 8 Thermal Array Sensor, $13.32 - <https://www.adafruit.com/product/904>

3. Breadboard, $5.99 - <https://www.amazon.ca/OSEPP-Breadboard-400-Points-Components-LS-00018/dp/B00EFZV2CG/ref=sr_1_5?ie=UTF8&qid=1516329412&sr=8-5&keywords=breadboard>

4. Jumper Wires, $13.99 - <https://www.amazon.ca/Foxnovo-Multicolored-40-pin-Female-Breadboard/dp/B00NPZO7CY/ref=sr_1_29?s=electronics&ie=UTF8&qid=1516329536&sr=1-29&keywords=jumper+wires>

### Total Time Commitment
This project can be completed quickly if the schematic diagram is followed. 
I would approximate 3 hours daily for 2-3 days should be required. 
Throughout this project, PCB creation, soldering, connecting wires, and testing the code will be needed to test if the sensor successfully reads data. 
At the end of the project the sensor will be able to sense current. 

### Mechanical Assembly

1. Use jumper wires to connect vcc on the sensor to the 5v on the Raspberry Pi
2. Use jumper wires to connect GND on the sensor to the GND on the Raspberry Pi
3. Use jumper wires to connect SCL on the sensor to the SCL on the Raspberry Pi
4. Use jumper wires to connect SDA on the sensor to the SDA on the Raspberry Pi
### PCB/Soldering
You can you use a PCB to replace a breadboard. If you use my PCB Schema as a guide you can easily create a PCB. But you can easily replicate a PCB with just a breadboard. ![PCB](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/inabreadboard_pcb.png) You need to solder some headers to the PCB. You need a 20-pin and a 6-pin headers for this.

### Power Up
Insert the SD card to the SD card reader from the Raspberry Pi package. If the OS is installed insert the SD card into the SD slot of the Raspberry Pi and plug in the power. The Raspberry Pi will boot up however, since this is the first boot up. Users are required to set up the operating system and configure their settings. An important step is to sign in to the Wi-Fi network so it can have internet connection. Go to Start> Raspberry Pi configuration > Interfaces and ensure I2C is enabled.

### Unit Testing
First you need to download the INA219 library, open a terminal and type
```
sudo pip3 install adafruit-circuitpython-ina219
```
To check if the project is connected and detecting the sensor, open a terminal and type 
```
sudo i2cdetect –y 1
``` 

### Production Testing
Once the program has successfully ran the output will display the current from the load.
### Reproducible?

If you follow my build instructions and my schematic diagram you will be able to reproduce my project. 
I have provided a GitHub, budget, instructions, diagram, code, and instructions on how to run the code.  
