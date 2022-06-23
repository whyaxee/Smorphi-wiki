This exercise is still currently under revision. We will update the latest version soon!
## Items needed:
* An assembled Smorphi/ Smorphi2 robot
* Wefaa InfraRed (IR) sensor
* A computer
* A USB to USB-c cable
* Internet connection
* Opaque items that can be used for obstacles
## Objectives of exercise:
1. Learn about the use of IR sensor
2. Explore the different components on the IR sensor board
3. Implement an application of an IR sensor

<br />

Steps | Description
-- | --
1 | [What are IR sensors]<br />Infrared sensors are a type of **Proximity sensors**. <br /><br />Movement is a big area of robotics, whether it be an autonomous robot on mars, or a robotic arm moving to pick goods. These robots need a means to be able to avoid obstacles (for autonomous robots), or to know when an object is within reach to pick up (for robotic arms).<br /><br />**Proximity sensors enable robots to detect objects at a distance without the need of physical contact, acting as the eyes of the robot.** <br /><br />They consist of two parts; **transmitter** and **receiver**. <br /><br />The transmitter first transmits a signal, this signal is reflected off an object and returns back to the receiver alerting the robot of an object nearby. Depending on the complexity of the proximity sensor, it can calculate the exact distance of the object.<br /><br />Infrared Sensor (IR) – uses an infrared beam which is transmitted by the transmitter (it cannot calculate exact distance)<br /><br />
2 | [Smorphi's IR sensor]<br /><br />![](https://github.com/WefaaRobotics/Smorphi-Wiki/blob/main/Robot%20exercises%20images/7/7.1.PNG)<br /><br />
3 | [Library of the IR sensor]<br />To aid in your learning, we have already provided you with an IR sensor library, (name here). You can find it under ____, and call it using ____ to use the library.<br /><br />Try to read through the library and its documentation to understand how it works. If you run the library code with the IR sensor attached to the Master board, you will be able to use the IR sensor to detect the surrounding Opaque obstacles. Do remember to use your rotary tool to adjust the sensitivity of your sound sensor too.<br /><br /> Additionally, the switch toggles between the forward transmitter and receiver set, and the downwards transmitter and receiver set. Depending on your use case, you can toggle the switch accordingly. We will be using the forwards facing transmitter and receiver set for this exercise, so toggle your switch downwards.<br /><br />
4 | [Simple obstacle detection activity]<br />Your task now is to make the robot move forwards continuously, and stop only when it detects an obstacle. You can implement your code in whatever way you like.<br /><br />Other than this task, think of different scenarios where an IR sensor will be important and how should your Smorphi react in those scenarios?<br /><br />
