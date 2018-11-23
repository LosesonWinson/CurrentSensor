
# CurrentSensor
# Repository
https://github.com/LosesonWinson/CurrentSensor
# Week 1 
* I first chose my sensor for the hardware project for semester 5 of this course. It was the INA219 High-Side DC Current/Voltage sensor
* Created my repository to store my files in
# Week 2
* I created and submitted my proposal this week
* Start working on my project plan for week 3
# Week 3 
* Completed my proposal
* Continue my research for the project
![ProjectPlan](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/WinsonProjectSchedule.pdf)
# Week 4
* Figured out what I need to purchase for the project
* Submitted my budget proposal to the instuctor
* Buy all the needed Items
# Week 5 
* Bought my parts and here is my proof of purchase
![Sensor+Cable](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/parts%20list.PNG)
![RaspberryPi](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/RPI.PNG)

# Week 6 
* The parts came in and now im ready to begin the assignment
* Met with my psuedo code assignment group and, completed the assignment
![sensor](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/sensor.jpg)

# Week 7
* I soldered on the heads on my sensor and I will start creating the breadboard for the project
![solderedhead](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/soldered.jpg)

# Week 8
* I was not able to complete my raspberry pi setup in time, but I used one of my classmates raspberry pi to show that my sensor is properly working
* At first the address that was being displayed was not the one that is required. The address on the sensor was 0x40 instead of 0x4C. I needed to change the address on the sensor, and you can achieve this by connecting A0 to GND and A1 to SCL. A0 and A1 are GND by default so all I needed to do was connect A1 to SCL.
![image1](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/week8img2.jpg)
![image2](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/week8img1.jpg)
![image3](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/week8img4.jpg)
![image4](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/week8img5.jpg)
![image5](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/week8img3.jpg)
# Week 9
* Today we completed our PCB creation on Fritzing, and now we need to email the gerber files to the Prototype Lab to get it created
* Currently I'm on a decent track for the completion of project. I have at least submited something every single week so far, but I'm still having problems with completely setting up my raspberry pi.
* My current financial situation is ok currently, because I'm still living with my parents
* Here is my breadboard, schematic and pcb
![breadboard](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/inabreadboard_bb.png)
![schematic](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/inabreadboard_schem.png)
![pcb](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/inabreadboard_pcb.png)
# Week 10 (November 6, 2018)
We just hit our PCB Soldering Milestone today, that was need to be completed. I was able to get my PCB created after sending the gerber files to the prototype lab. After soldering my reciprocal headers onto my PCB, and have filled the vias on my board, I found out it was not working as it did not detect the sensor after connecting it to a raspberry pi. I'm not exactly sure what the issue is but I assume it is a soldering problem that I need to fix as soon as possible, but because of the PCB not working it delay's my project schedule by a week.Lastly, after getting the PCB create I found a small error with the design of the board. The PCB board that I created does not fit with the Raspberry Pi with the case on, but I could just take off the case.   ![PCBreal](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/PCB.jpg)
# Week 11 (November 13, 2018)
Today was the hardware demostration milestone for the project. I was able to show my sensor was reading data and last week my PCB was not working and I managed to get the problem resolved by resoldering the headers of the PCB. Now that I got my sensor working with my PCB im on track for completing the project on time. The schedule noted that I was suppose to complete my PCB on November 13, 2018, and I managed to finish it on time. The next step for the project is to complete the enclosure for the Raspberry Pi, and that is due on November 20, 2018. I noticed a with the PCB design after some testing with the Raspberry Pi. The PCB does not fit inside the Raspberry Pi with the case attached and there is no real fix for this problem so I have to attach my PCB to a caseless Raspberry Pi. 
![pcbonpi](https://raw.githubusercontent.com/LosesonWinson/CurrentSensor/master/pcbonpi.jpg)

Last week I was given some headers from the Prototype Lab to use on my PCB, because of the Canada Post strike my order on the headers were and still are delayed. I did not think I needed to purchase some headers when I created my budget proposal, but it was only $8 dollars for the whole order.

A problem I did not anticipate occured when I started the program. I could not properly read the voltage values, but the current values are completely fine and I'm not sure how to resolve this issue.

# Week 12
I messed up my case so i would need to get a new one completed on monday. This blog will be updated by then
