# Chairbot source code Rebuilt

## Goal of this repository
I merely aim to store Program.cs because it was one of my first comprehensive 
program's that I've ever written, and it demonstrates my knowledge of C#, and developing networking standards at the transport layer.

## What is chairbot
chairbot was a robot built by FIRST Robotics team 3636 Grant High School robotics 
out of parts from old first robots, but unlike your typical FIRST robot
this bot used a raspberry pi for wifi connectivity, and data decoding
that it then sent over serial to an arduino that wrote to spark motor controllers
that then operates the robot

## Architecture of This Repository
The Program.cs file was what ran on the Raspberry pi, and sent data to the 
arduino uno over the USB A-B serial port connection

Unfortunately the arduino code, as well as the joystick code that runs on the laptop that send data to the raspberry pi has been lost, though it may be fun to try and rebuild it sometime.

