## Items needed:
* An assembled Smorphi/ Smorphi2 robot
* Wefaa InfraRed (IR) sensor
* A computer
* A USB to USB-c cable
* Internet connection
* Black tape (?)
## Objectives of exercise:
1. Learn about another use of IR sensor
2. Using an IR sensor, make Smorphi follow a line drawn on the ground

<br />

Steps | Description
-- | --
1 | [Alternate uses of IR sensors]<br /><br />Not only can IR sensors detect obstacles, as we have done in the previous exercise, IR sensors are also able to be programmed to allow robots to follow a line. IR sensors are able to pick up reflected infrared radiation on surfaces, which in this case is your floor and, based on its intensity, determines the reflectivity of the surface in question. Light-coloured surfaces will reflect more light than dark surfaces, resulting in their appearing brighter to the sensor. This allows the sensor to detect a dark line on a pale surface, or a pale line on a dark surface<br /><br />
2 | [Diagram of IR Sensor recap]<br /><br />![](https://github.com/WefaaRobotics/Smorphi-Wiki/blob/main/Robot%20exercises%20images/8/8.1.PNG)<br /><br />These 2 downward facing diodes are the ones that will differentiate between the line and the floor.<br /><br />
3 | [Setting up the line following course]<br /><br />Set up the line for the following course as below using your black tape:<br /><br />![](https://github.com/WefaaRobotics/Smorphi-Wiki/blob/main/Robot%20exercises%20images/8/8.2.PNG)<br /><br />Then, install 2 IR sensors to the front bottom plate of your Smorphi. Make sure your IR sensor switch is flipped up to use the downward facing transistor and receiver for line following. Place your Smorphi on the floor and make sure to adjust the trimport so that the sensor detects the floor. The light on the sensor should indicate detected object (light up) over the floor and not detect any object (not light up) when it is over the black line.<br /><br />
4 | [Get the robot to do line following]<br /><br />Now let’s get your Smorphi to follow the line. <br /><br /> First think of the logic that you would require for your Smorphi to remain following the line. What are the checks and balances that should be put in place for Smorphi to remain following the line? How should Smorphi react when its IR sensor is over the line? What about when the IR sensor is not over the line? As you are figuring out the answers to the above questions, keep implementing that logic and testing out your code on the line.<br /><br />Adjust and fine tune your code until your Smorphi can successfully complete the line!<br /><br />Extra credit: <ul><li>How fast can your Smorphi complete the line? Try to optimse your Smorphi speed and accuracy </li><li>Can you make up another course and let your Smorphi follow it? </li><li> Would your Smorphi be able to tackle sharp corners?</li></ul><br /><br /> When you are done with your code, you can [compare your solution with ours](https://github.com/WefaaRobotics/Smorphi/blob/main/exercise/line_following/line_following.ino) and compare performance!
5 | [Challenge yourself]<br /><br />Are you able to do line following with 1 IR sensor only?<br /><br />