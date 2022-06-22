# Exercise 2

## Items needed:
* An assembled Smorphi/ Smorphi2 robot
* A computer
* A USB to USB-c cable
* Internet connection

## Objectives of exercise:
1. Setting up of Smorphi for coding to customise functionality
2. Learn some simple debugging skills
3. Learn how to look up information on Google
4. Learn how to use the Arduino IDE

<br />

Steps | Description
-- | --
1 | [Download the Arduino IDE] Go to https://www.arduino.cc/en/Guide to download Arduino IDE. Choose the correct version of Arduino IDE according to the type of computer you are using. Eg. If you are using Windows, download the version meant for Windows. Integrated development environment (IDE) is software for building applications that combines common developer tools into a single graphical user interface (GUI). An IDE typically consists of:Source code editor: A text editor that can assist in writing software code with features such as syntax highlighting with visual cues, providing language specific auto-completion, and checking for bugs as code is being written.Local build automation: Utilities that automate simple, repeatable tasks as part of creating a local build of the software for use by the developer, like compiling computer source code into binary code, packaging binary code, and running automated tests.Debugger: A program for testing other programs that can graphically display the location of a bug in the original code.The Arduino IDE makes it easy to write code and upload into the Arduino based board we are using for Smorphi
2 | [Setup the Arduino IDE] Follow the link below for the tutorial to set up the ESP32 board for the Arduino IDE https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/#:~:text=Installing%20ESP32%20Add%2Don%20in%20Arduino%20IDE&text=Open%20the%20Boards%20Manager.,installed%20after%20a%20few%20seconds This is so that the ESP32 will be recognised by the Arduino IDE. Usually, if you are using an Arduino board directly, there is no need to do this step.
3 | [Download the Smorphi libraries] Go to https://github.com/WefaaRobotics/Smorphi on Github to download the latest version of our user code via the download zip button. It can be found in the drop down after clicking on the green Code button. Make sure you are downloading from the Main Branch.
4 | [How to include Smorphi library into Arduino IDE] In your Arduino IDE, go to Sketch -> Include Library -> Add .ZIP Library…Then, navigate to the directory that you have downloaded the Smorphi library to, and select the zip file in the next screen. The contents of the zip file will automatically be added to your Arduino IDE library folder. To double check this step, check the ‘Include Library’ Menu, you should be able to see the newly added library under the contributed libraries section. Click on the newly added library to add it to your coding space.
5 | [Add the supporting library] Try clicking the Verify button, you will need to save your file first.You will see this error message:This is because another library that the Smorphi library needs, the Adafruit_Motor_Shield_V2_Library, has not been included. So let’s include that library.Go to the ‘Include Library’ menu and select ‘Manage Libraries…’In the search bar, look up the ‘Adafruit_Motor_Shield_V2_Library’ and install the latest version. You will get a pop up that says there are other dependencies that are missing. Click on the ‘Install all’ button.Close the library Manager. You can now try to Verify again. You will see another error.Like before, go to the ‘Manage Libraries…’ Menu to download the library Adafruit_MCP23017_Arduino_Library. Verify the code now. There should be no errors thrown
6 | [Test your setup] Connect your computer to the board and select the portKey in the below code into your IDEYour Smorphi should move forward for 3 seconds, stop for 3 seconds and then repeat.NOTE: Ususally, when you upload the code to the master board, the process should complete automatically. However, sometimes the upload will be stuck at ‘connecting……’There are 2 solutions for this. Before it resolves into an error, press and hold the Boot button and click the enable button on the Master board at the same time, then release and wait. The code should complete the upload to the master board. You can unplug and reconnect the USB cable from the Master board to your computer and then reupload the code.

</div><br /><br /><br /><!--EndFragment-->
</body>
</html>