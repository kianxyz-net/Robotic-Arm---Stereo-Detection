# Robotic Arm - Stereo Object Detection

Stereo vision system for robotic pick-and-place.

Two webcams detect objects, estimate their 3D position, and send the coordinates to a robot arm for automated picking and placing.

## Features

* YOLOv8 object detection
* HSV color detection
* Stereo camera depth estimation
* Camera-to-robot coordinate transformation
* Modbus TCP communication with the robot arm

## Demo

https://github.com/user-attachments/assets/669c72b2-5368-461d-bfe5-e33cc4eea0b0

## How It Works

1. Capture images from two cameras
2. Detect the object in both images
3. Use stereo vision to calculate its 3D position
4. Convert the position into the robot's coordinate system
5. Send the coordinates to the robot arm
6. Robot picks and places the object

## Tech Stack

* C#
* .NET
* OpenCV / OpenCvSharp
* YOLOv8
* Modbus TCP
* Stereo vision

## Author

Kian Entezari
