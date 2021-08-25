# Robotics & Automation Project Work (Line Follower)

https://user-images.githubusercontent.com/56788338/130749228-9228286f-b84c-4a32-b554-2760d1642cd6.mp4

Environment: LEGO NXT using NXC.

Introduction: Line follower robot is a free wheel mobile robot that designed to follow a reference line.
The line or define path may be simple or complex for example magnetic marker, embedded lines or laser guide marker. 
Based on type of line or markers various type of sensor are used. Choose of sensor scheme mostly depends on the accuracy and flexibility requirement.
Line follower robot is now widely used in different sophisticated field like large industries, manufacturing company to minimize production time as well cost.

Components Description: In this line follower project, the robot has been built to follow black line as reference line.
To sense the reference path, reflected light sensor has been used. Basically our line follower robot consists of major four parts- Moto, Wheel, Sensor, Controller.

![image](https://user-images.githubusercontent.com/56788338/130749447-2508c995-9dc2-4aa3-96de-f739b9cc942b.png)

Motor: There are two motors are used in the robot one for left side and another for right side. Both motors are placed horizontally parallel for getting same turn ratio from two wheels.Motors are connected tightly for better performance.

![image](https://user-images.githubusercontent.com/56788338/130749631-36e62cc1-0964-48de-a5b7-f905724b69e5.png)

Wheel: The robot has three wheels for better movement. Left and right wheel only for forward or reverse movement which is powered by left motor and right motor respectively. 
Another free wheel is connected in back side lower part for guiding the robot to desire direction. 
This wheel is smaller compare to other two wheels due to compatible robot design.

![image](https://user-images.githubusercontent.com/56788338/130749808-eb06c84d-f426-45d2-8388-0d97ecdb6fd2.png) ![image](https://user-images.githubusercontent.com/56788338/130749864-e769d56b-361e-4f31-8147-1cd0843aef4d.png)



Sensor: To follow the reference black line, reflective light sensor has been used. 
The sensor works based on comparing emitted light and received reflected light value. White surface reflect more light than black line. 
Robot chose the direction based on sensor value. 

![image](https://user-images.githubusercontent.com/56788338/130749982-a09e832f-71d0-42c8-9bb4-7ccebbccdb41.png)

Design argument and solutions: The line follower robot model was designed based on some features that are given bellows:

* Balancing: There are three wheels are used in this robot which helps to balancing robot during movement. 
* Smooth movement: Large two front wheels were chosen due to get smooth movement though the motor power was lower. 
* Smooth turning: One free wheel was chosen instead of two wheels in rare side of the robot due to smooth turning and to minimize complexity.
* Precise sensor reading: Sensor was placed in the middle position in-between two front wheel also as much as possible near to the surface due to minimize environmental light interferences.
* Robust and reliability: Controller and motor platform were jointed together tightly for making robot robust during sharp turning.

###Code file-1.

![image](https://user-images.githubusercontent.com/56788338/130750383-7aba5bc5-9935-4508-83a6-9d7ac785b44a.png)

###Flow Chart-1.

![image](https://user-images.githubusercontent.com/56788338/130750505-dffebfa4-827f-4b31-87b7-513a0bb87eff.png)

###Code file-2.

![image](https://user-images.githubusercontent.com/56788338/130750610-a7cc0b5f-8138-40ee-bd24-d9242a067c5d.png)

###Flow Chart-2.

![image](https://user-images.githubusercontent.com/56788338/130750726-18c2d3e5-c0e0-4433-98b7-620bca3b6d46.png)




