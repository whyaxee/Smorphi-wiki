
This exercise is still currently under revision. We will update the latest version soon!
## Items needed:
* An assembled Smorphi/ Smorphi robot
* Wefaa temperature sensor
* A computer
* A USB to USB-c cable
* Internet connection
## Objectives of exercise:
1. Learn about the various commonly used sensors
2. Learn about the use of temperature sensor
3. Explore the different components on the temperature sensor board
4. Implement an application of a temperature sensor

Steps | Description
-- | --
1 | [Brief introduction on commonly used sensors for robots]<br />Sensors are devices that give robots the ability to make ‘sense’ of the real world (the same way our five senses help us). Below are some of the most common sensors used in robotics: <ul><li>Light sensors</li><li>Proximity sensors</li><li>Sound sensors</li><li>Temperature sensors</li><li>Acceleration sensors</li><li>Magnetic sensors</li><li>Force sensors</li></ul> https://electronicguidebook.com/common-sensors-used-in-robotics/
2 | [Brief intro on what is a temperature sensor]<br />Temperature sensors has the ability to measure the temperature of the air (ambient), a solid, or a liquid. They can have many uses in robotics and can be used internally in the robot, or for external purposes.<br /><br />When used internally, temperature sensors are used to ensure the temperature of the robotic system is within the safe working limits. Robots will employ a lot of electronics and motors that can get hot very fast. Temperature sensors are used to alert the control system when things get too heated. <br /><br />When used externally, temperature sensors in robotics are used to measure the ambient air temperature, temperature of objects or of a liquid. For example, a robot might be used to travel to depths of the ocean where measuring and recording temperature information would be vital for scientists or researchers. <br /><br />Common temperature sensors used in robotics include;<ul><li>Thermocouples</li><li>Resistance Temperature Detectors (RTDs)</li><li>Thermistors</li><li> Semiconductor based IC sensors</li></ul><br />
3 | [Smorphi's Temperature sensor]<br /><br />![](https://github.com/WefaaRobotics/Smorphi-Wiki/blob/main/Robot%20exercises%20images/5/5.1.PNG)<br /><br />The temperature sensor is the simplest sensor among the various sensors provided in the kit. It only has one active component, which is the temperature sensor component that can detect the temperature of the surroundings. This temperature sensor provided can only ambient air temperature or surface temperature of solids.<br /><br /> _Do not submerge the sensor in water or any type of liquid._<br /><br />
4 | [Introduction to the library of the temperature sensor]<br />To aid in your learning, we have already provided you with a temperature sensor library example which you can find [here](https://github.com/WefaaRobotics/Smorphi/blob/main/Smorphi2/Testing_code/sensors/Temperature_Sensor/Temperature_Sensor.ino). Try to read through the code and its comments to understand how it works. Once you upload the provided temperature sensor code to the Master board. with the temperature sensor attached to the Master board, you will be able to use the temperature sensor to detect the surrounding temperature. Just ensure that your robot is still connected to your computer and open the serial monitor to view the temperature measured by the temperature sensor.<br /><br /> NOTE: The temperature sensor can only work if plugged onto the Master board. It will not work if plugged onto the slave board. You can choose which sensor port to use on the Master board by editing the example Temperature sensor code provided.<br /><br />
5 | [Activity]<br />Your task now is to make the robot run faster as the temperature detected by the sensor goes higher. You can implement your code in whatever way you like.<br />Other than that, think of different scenarios where a temperature sensor will be important and how should your Smorphi react to different temperatures?<br /><br />
