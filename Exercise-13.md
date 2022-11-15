## Items needed:
* An assembled Smorphi mini / Smorphi <sup> 2</sup> robot
* Wefaa InfraRed (IR) sensor
* A computer
* A USB to USB-C cable
* Internet connection
* Cardboard sheets or Vanguard paper (you will require this to make the maze)
## Objectives of exercise:
1. Experiment with obstacles
2. Train your coding logic

<br />

Steps | Description
-- | --
1 | [Template of a maze to build]<br /><br />For this exercise, for ease of movement, lets put your Smorphi into its ‘O’ shape configuration. <br /><br />Then, install an IR sensor on all 4 sides of the ‘O’ shape configured Smorphi. Make sure the IR sensor has been switched to obstacle detection mode. Then, with some pieces of paper and cardboard, build the maze shown below. Make sure the paper and cardboard are high enough to be detected by the IR sensor, and that the Maze is wide enough for your ‘O’ Shape Smorphi to move through.<br /><br />![](https://github.com/WefaaRobotics/Smorphi-Wiki/blob/main/Robot%20exercises%20images/10/10.1.PNG)<br /><br />
2 | [Hard code to get out of the maze]<br /><br />By analysing the maze, you can first program your Smorphi to navigate through without using the sensor.<br /><br />If you are struggling to figure out the code, you can try this: First code out all the functions, distance and timings required line by line.<br /><br />Afterwards, try using the conditionals and loops that you have learned to get your Smorphi to complete the maze.<br /><br />What is the least number of lines of code you are able to get your program down to? Challenge yourself!
3 | [Use your IR sensor to get out of the maze]<br /><br />After you have gotten the baseline of the path through the maze, lets now try to get through the maze using the IR sensor. <br /><br />The IR sensor in this case acts as your Smorphi’s eyes and the program you write should receive information from your IR sensor that will trigger a response in your Smorphi, allowing your smorphi to navigate through the maze without knocking down any walls.<br /><br />Like in the previous step, after you have gotten a base code that works, try optimising your code by using conditionals and loops and challenge yourself to see how short you can make your code.<br /><br />If you are having trouble, here’s the hint: _Smorphi is able to move holonomically in all directions._<br /><br />
4 | [Extra challenge]<br /><br />Just as an opportunity to explore more complex mazes, if you wish to challenge yourself, you can try out the maze below, and get Smorphi to navigate through the maze using your IR sensors.<br /><br />![](https://github.com/WefaaRobotics/Smorphi-Wiki/blob/main/Robot%20exercises%20images/10/10.2.PNG)<br /><br />Try and see if your existing code is able to work for this maze. If not, what should you change about the code? Just like the previous 2 steps, you can first try to hard code the path for Smorphi to move from start to finish, before attempting to make Smorphi more intelligent and reactive to its surroundings.<br /><br />
5 |<br /> You can also design your own mazes and try out your code in those mazes.<br /><br />
 
