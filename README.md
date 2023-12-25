# ROS Robotic Arm Control via Hand Movement

## Overview

This GitHub repository houses a ROS (Robot Operating System) package designed for controlling a robotic arm simulation in Rviz using hand movements captured from a camera. The robotic arm model used in this project was sourced from [GrabCAD](https://grabcad.com/library/robotic-arm-163). The package leverages the MediaPipe library for hand location recognition and advanced computer vision techniques to interpret hand gestures, translating them into precise commands for the robotic arm.

## Features

- **Hand Gesture Recognition:** The system employs the MediaPipe library for accurate hand location recognition and advanced computer vision algorithms to interpret hand gestures from a camera feed.
- **Real-time Control:** The robotic arm can be controlled in real-time, responding to dynamic hand movements with high accuracy.
- **Rviz Integration:** The simulation is visualized in Rviz, providing a comprehensive and interactive environment for testing and development.
- **Modular Architecture:** The ROS package is built with a modular structure, allowing for easy integration with other robotic systems and sensors.

## Dependencies

- ROS Kinetic/Melodic/Noetic (adjustable based on your ROS version)
- OpenCV
- MoveIt! (for motion planning)
- Rviz (for visualization)
- [MediaPipe](https://mediapipe.dev/): A library for hand tracking and pose estimation.

## Robotic Arm Model

The 3D model of the robotic arm used in this project was sourced from [GrabCAD](https://grabcad.com/library/robotic-arm-163). Make sure to comply with the licensing terms provided by the model's creator.
