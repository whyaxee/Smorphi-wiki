## Items needed:
* An assembled Smorphi mini / Smorphi<sup> 2</sup> robot
* A computer
* A USB to USB-C cable
* Internet connection
## Objectives of exercise:
1. In depth going through of the Smorphi library
2. Self-study exploration
3. Build your own version of the Smorphi library

<br />

Steps | Description
-- | -- 
1 | This process is actually a rather long, multidisciplinary and multi-step process. We might break them down into easier digestable steps in the future. But for now, for advance learners and learners that wish to have a challenge, you can look through all the header files in our Smorphi library and then see how  you can optimise and write your own version of the library.
2 | For Smorphi <sup> 2</sup> users, you can refer to the Smorphi <sup> 2</sup> library using this link: https://github.com/WefaaRobotics/Smorphi/blob/main/Smorphi2/ <br>For Smorphi mini users, you can refer to the Smorphi mini library using this link: https://github.com/WefaaRobotics/Smorphi/blob/main/Smorphi_mini/
3 | In the library, you can see C Header Source File (.h) and C++ Source Files (.cpp).<br></br>![](https://github.com/WefaaRobotics/Smorphi-Wiki/blob/main/Robot%20exercises%20images/16/16.1.png)
4 | As you scroll throught the **smorphi.h / smorphi_mini.h** header file, you can see the various functions that can be called in your code for the Smorphi. <br></br> ![](https://github.com/WefaaRobotics/Smorphi-Wiki/blob/main/Robot%20exercises%20images/16/16.2.png) <br></br> Header files are meant to show the functions available in the library. Therefore, these functions are not defined in the file.
5 | In order to know what is going on behind every function, we have to take a look at the .cpp files, specifically the **smorphi_test.cpp** file. You can see the code for the functions that are shown in the header file. <br></br>![](https://github.com/WefaaRobotics/Smorphi-Wiki/blob/main/Robot%20exercises%20images/16/16.3.png) <br></br> To have a better understanding of what each function does, you can take a look at [Smorphi Code Documentation](https://github.com/WefaaRobotics/Smorphi/wiki/Smorphi-Code-Documentation)
6 | Based on what you want Smorphi to do, you can create and add in your own functions to the .cpp files and .h files respectively.
7 | For advanced learners, you can try to optimise with regards to size of library, speed of the library, etc.
