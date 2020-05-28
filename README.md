# IoT
Controlling VLC media through ultrasonic sensors
The Arduino should be programmed to read the distance of hand from the Ultrasonic sensor.
By reading the value of distance we can arrive at certain actions to be controlled with gestures,
for example in this program I have programmed 5 actions as a demo.
Action 1: When both the hands are placed up before the sensor at a particular far distance then
the video in VLC player should Play/Pause.
Action 2: When right hand is placed up before the sensor at a particular far distance then the
video should Fast Forward one step.
Action 3: When left hand is placed up before the sensor at a particular far distance then the video
should Rewind one step.
Action 4: When right hand is placed up before the sensor at a particular near distance and then if
moved towards the sensor the video should fast forward and if moved away the video should
Rewind.
Action 5: When left hand is placed up before the sensor at a particular near distance and then if
moved towards the sensor the volume of video should increase and if moved away the volume
should Decrease.
The python program for this project is very simple. We just have to establish a serial
communication with Arduino through the correct baud rate and then perform some basic
keyboard actions. The first step with python would be to install the pyautogui module. Make
sure you follow this step because the program will not work without pyautogui module .
