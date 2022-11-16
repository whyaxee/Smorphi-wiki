
## Items needed:
* An assembled Smorphi mini / Smorphi <sup>2</sup> robot
* Wefaa sound sensor
* A computer
* A USB to USB-C cable
* Internet connection
## Objectives of exercise:
1. Learn about the use of sound sensor
2. Explore the different components on the sound sensor board
3. Implement an application of a sound sensor

<br />

Steps | Description
-- | --
1 | [What is a sound sensor]<br />Sound sensors are typically microphones which are the ears of the robot allowing it to perceive sound. They sense sound from the surroundings and convert it into a voltage which is then sent to the control system for further processing. <br /><br />A great application of sound sensors is voice recognition. This would come in handy in scenarios where you might need to control a robot but your hands are tied up. One great example of this is in the surgery room, where a robot can assist a surgeon with an operation. The surgeon might have both hands full, but could still communicate with the robot using his or her voice.<br /><br /> Sound sensors can also be used in robotics as a means of vibration detection. The sound sensor provided in your kit acts more like a vibration detector, and is able to react to sounds detected as per your code.<br /><br />
2 | [Smorphi's sound sensor]<br /><br />![](https://github.com/WefaaRobotics/Smorphi-Wiki/blob/main/Robot%20exercises%20images/6/6.1.PNG)<br /><br />
3 | [Example code for the sound sensor]<br />To aid in your learning, we have already provided you with a sample sound sensor. You can find it under [testing code -> sensors -> Sound_Sensor](https://github.com/WefaaRobotics/Smorphi/blob/main/Smorphi2/Testing_code/sensors/Sound_Sensor/sketch_sep25a/sketch_sep25a.ino), and access it through the Arduino IDE.<br /><br />Try to read through the sample code to understand how it works. If you run the sample sound sensor attached to the Master board, you will be able to use the sound sensor to detect the surrounding sounds. Do remember to use your rotary tool(Trimpot) to adjust the sensitivity of your sound sensor as per need.<br /><br />
4 | [Activity]<br />Your task now is to make the robot move forwards when it detects sound. You can implement your code in whatever way you like.<br /><br />Other than this task, think of different scenarios where a sound sensor will be important and how should your Smorphi react to sound in those scenarios?<br /><br />
