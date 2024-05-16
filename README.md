# Arm Controlled Robot

## Overview

This ROS package allows you to control a simulated robot using your arm movements. By using this package, you can interact with the simulated robot in a more intuitive and natural way by simply moving your arms. The system utilizes Mediapipe for gesture detection and translates these gestures into commands for the robot.

## Prerequisites

Before using this package, make sure you have the following installed:
- ROS (Robot Operating System)
- Mediapipe
- Required ROS packages for the robot simulation

## Installation

1. Clone this repository into your ROS workspace's `src` directory:
    ```bash
    git clone https://github.com/yourusername/Arm_Controlled_Robot.git
    ```

2. Install the required dependencies by navigating to the scripts directory and running:
    ```bash
    cd Arm_Controlled_Robot/scripts
    pip install -r requirements.txt
    ```

## Usage

1. Launch the robot simulation environment:
    ```bash
    roslaunch arm_controlled_robot simulation.launch
    ```

2. Run the arm control node:
    ```bash
    rosrun arm_controlled_robot main.py
    ```

## Demo

For a visual demonstration of the project, you can watch the following video:

[![Project Demo](http://img.youtube.com/vi/9owxQ1zTffA/0.jpg)](https://www.youtube.com/watch?v=9owxQ1zTffA)
