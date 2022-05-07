# Patrolling-Bot
Embedded System based project for B.Tech Semester 3

This is a group project in which we have designed a movable robot named as patrolling bot. Purpose of the bot is mainly to do survillance in high security jails. The bot can perform real time video capturing and is user operated, thus requires a official to monitor the bot.
The vehicle is entirely controlled using a Raspberry Pi (RPi 3B) and STM32-Nucleo F446RE. RPI serves as a main control system which communicates with controller(govt. official) using SSH and thus is remotely controlled using control system's keyboard input.
The actuation is done using STM32 which gets signals from RPi and thus controls the motor drivers and servo accordingly. The entire System is powered using power bank that can be detached from the bot and gives a backup forupto 2 hours. THe motors are independently controlled usig two 3.7V 5000mAh Li-ion 18650 cells.
It also has got a camera with Field of View 90 degrees which is extended using a 180 degrees rotating Servo motor. This help the controller to monitor all jail cells without entering into them in real time with minimum latency.
Entire system is controlled and monitored using a website which has a login system that is used to authenticate operator. Further the real time images captured by camera are shown in this feed. The website also has attendence capturing system, which takes user input as cell number, name, and presenty.
- - - -

System Architecture:
![image](https://user-images.githubusercontent.com/81175552/167258987-d9e1c985-c3ff-46aa-b145-7633a17509f1.png)
- - - -

Flowchart: 
![image](https://user-images.githubusercontent.com/81175552/167258961-a143bf42-d9b5-4b52-b9be-8f033bda5008.png)

- - - -
Connection Diagram:
![image](https://user-images.githubusercontent.com/81175552/167259016-07785893-7911-4cc1-9d63-f4ea90e02757.png)
