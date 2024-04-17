# AutonomousRCCar

## Overview
This project encompasses the creation of an autonomous RC car capable of navigating on its own while detecting stop signs, obstacle detection and user detection. Built with a Raspberry Pi at its core, it combines technologies such as OpenCV, PyCharm, and Arduino to mimic real-world self-driving functionalities.

## Key Features

- **Stop Sign Detection**
  - Uses a convolutional neural network (CNN) to recognize stop signs.
  - Automatically stops when a stop sign is detected.

- **Obstacle Detection**
  - Implements OpenCV and CNN for real-time obstacle detection.
  - Adjusts the car's trajectory and speed to safely avoid obstacles.

- **Self-Driving Functionality**
  - Navigates through various environments using sensor data and image processing.
  - Capable of route planning and obstacle avoidance.

- **User Interface**
  - Provides real-time diagnostics, sensor data, and video feeds.
  - Allows manual override and control when necessary.

## Technical Specifications

### Hardware Components
- **Raspberry Pi**: Manages computations and networking.
- **Arduino**: Controls motors and reads sensor data.
- **Sensors and Actuators**: Include ultrasonic sensors for distance measurement and servos for steering.

### Software and Libraries
- **OpenCV**: For image processing and object detection tasks.
- **PyCharm**: Used as the IDE for software development.
- **CNN**: Python-based network for detecting stop signs and pedestrians.
- **TCP/IP Connection**: Ensures real-time communication between the Raspberry Pi and the control interface.
