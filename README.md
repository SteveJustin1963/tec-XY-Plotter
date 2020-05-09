# tec-XY-Plotter

based on Make Arduino XY Plotter Drawing Robot

https://www.youtube.com/watch?v=T0jwdrgVBBc

## Make Arduino XY Plotter Drawing Robot

## Mert Arduino

In this tutorial we will learn how to make Arduino XY Plotter Drawing machine. With Drawing Robot you can draw images on wall, panel or A4 paper. You can print pictures or print text. All required hardware for this project are listed below. We will learn how to install and use the Polargraph program for robot control. Motor drivers - Adafruit's Motoshield v1. A modern classic. It can drive two stepper motors each drawing up to 600mA and has pinouts for a servo too, so is perfect for this project.

## Required Hardware:
- 1x Arduino UNO R3: http://bit.ly/2xt9MVk
- 1x L293D Motor Drive Shield: http://bit.ly/2H7vmy9
- 2x L293D Motor Drive IC: http://bit.ly/2J4N3jD
- 2x 17 Stepper Motor: http://bit.ly/2J0xqhf
- 1x MG90S Servo Motor: http://bit.ly/2JfGtuj
- 1x GT2 Pulley 16 Teeth Set: http://bit.ly/2H9DoXq
- 1x GT2 Rubber Belt (5M): http://bit.ly/2Lfc0tJ
- 3 in 1 Jumper Wire: http://bit.ly/2J6de9E
-1x 5V 2A Power Supply

## 3D Models:
Gondola 3D Model: https://www.thingiverse.com/thing:575487

Stepper Mounting Bracket: https://www.youtube.com/redirect?redir_token=3_P7NGl4JYxPSl7hkE1xTW2iiJ98MTU4OTA3OTc0NkAxNTg4OTkzMzQ2&q=https%3A%2F%2Fwww.thingiverse.com%2Fthing%3A2371117&event=video_description&v=T0jwdrgVBBc

## Motor Shield Upgrade for the High-Torque Stepper Motor: 
https://youtu.be/r2uwmEsIuLA

In this tutorial we will learn how to use a high-torque stepper motor with the L293D motor drive shield. I used a high torque stepper motor with the L293D motor driver, so the L293D integration overheated. The cause is high current requirement. I modified the L293D Motor driver shield to solve this problem.

* polargraphcontroller: (Polargraph controller Copyright Sandy Noble 2018.)
* Polargraph Server for Arduino UNO and MEGA compatible boards using Adafruit motorshields.
* It works fine in Arduino IDE v1.8.5 https://www.youtube.com/redirect?redir_token=3_P7NGl4JYxPSl7hkE1xTW2iiJ98MTU4OTA3OTc0NkAxNTg4OTkzMzQ2&q=https%3A%2F%2Fwww.arduino.cc%2Fen%2FMain%2FOldSoftwareReleases%23previous&event=video_description&v=T0jwdrgVBBc 

* Download the controller by going to the https://www.youtube.com/redirect?redir_token=3_P7NGl4JYxPSl7hkE1xTW2iiJ98MTU4OTA3OTc0NkAxNTg4OTkzMzQ2&q=https%3A%2F%2Fgithub.com%2Feuphy%2Fpolargraphcontroller%2Freleases%2Ftag%2F2017-11-01-20-30&event=video_description&v=T0jwdrgVBBc

* and get the most recent bundle.
* It also contains a folder called polargraph_server_a1. This is the polargraph firmware source code.
* Copy the contents of arduino-source/libraries into your Arduino/libraries/ folder
* Copy arduino-source/polargraph_server_a1 into your Arduino/ folder
* You should have created three new folders on your disk:
  * Arduino/polargraph_server_a1/
  * Arduino/libraries/Accelstepper/
  * Arduino/libraries/AFMotor/
* Start Arduino IDE:
* Go to File-Sketchbook-polargraph_server_a1
* Fourteen files will open up and be displayed as tabs in the IDE. This is the source code of the firmware.
* Press the "verify" button in the toolbar to try and compile it.
* If it compiles, press the "upload" button in the toolbar to upload it.
- Once you do that, you should confirm that it is working properly - use the serial monitor on the board, set to 57600 baud to make sure that it is issuing "READY" every couple of seconds.

* Processing v2.2.1:
- Install Processing 2.2.1: https://processing.org/download/
- Run Processing, find where your sketchbook folder is: (File-Preferences, sketchbook location).
- Download the latest code bundle: Go to https://www.youtube.com/redirect?redir_token=3_P7NGl4JYxPSl7hkE1xTW2iiJ98MTU4OTA3OTc0NkAxNTg4OTkzMzQ2&q=https%3A%2F%2Fgithub.com%2Feuphy%2Fpolargraphcontroller%2Freleases%2Flatest&event=video_description&v=T0jwdrgVBBc ... and download the zip file linked to at the bottom of that page - it'll be called something like Polargraph*.zip
- Unzip the code bundle and copy the three code library folders out of Polargraph.2017-11-01\Polargraph 2017-11-01\processing-source\Processing libraries into your C:\Users\xxxx\Documents\Processing\libraries
- Copy the whole polargraphcontroller folder from Polargraph.2017-11-01\Polargraph 2017-11-01\processing-source\ into your Processing sketchbook folder. It'll look like: C:\Users\xxxx\Documents\Processing
- Restart Processing and go file-sketchbook-polargraphcontroller to open the app source code.
- Press the run button in the toolbar to run the sketch.

* Stepper motor and pulley settings (in Polargraph):
- Set the MM Per Rev value according to the pulley and belt you are using. For example, if the belt is GT2 the lue is 2mm. If the pulley has 16 teeth, 2x16 = 32mm. So, the belt will advance 2mm each turn.
- Adjust Steps Per Rev according to the stepper motor type. For example, if te step angle of the used stepper motor is 1.8 degrees the value is 200 steps. This value is adjust to 400 because dual motor is used.

* Check out these platforms for more:

- http://www.polargraph.co.uk/

- https://www.youtube.com/redirect?redir_token=3_P7NGl4JYxPSl7hkE1xTW2iiJ98MTU4OTA3OTc0NkAxNTg4OTkzMzQ2&q=https%3A%2F%2Fwww.hackster.io%2Fmertarduino%2Fmake-arduino-xy-plotter-drawing-robot-polargraph-b4fe36&event=video_description&v=T0jwdrgVBBc

- https://www.youtube.com/redirect?redir_token=3_P7NGl4JYxPSl7hkE1xTW2iiJ98MTU4OTA3OTc0NkAxNTg4OTkzMzQ2&q=https%3A%2F%2Fwww.instructables.com%2Fid%2FXY-Plotter-Drawing-Robot-Arduino-Polargraph%2F&event=video_description&v=T0jwdrgVBBc
