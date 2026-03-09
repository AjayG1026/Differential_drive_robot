# Differential Drive Robot (ROS2)

## Overview

This project implements a **Differential Drive Robot** using **ROS2**.
The robot can be controlled using either a **keyboard** or a **joystick**.

The system publishes velocity commands to the robot and simulates movement using ROS2 nodes.

This project demonstrates basic concepts of:

* Differential drive kinematics
* ROS2 nodes and topics
* Teleoperation using keyboard
* Teleoperation using joystick
* Robot simulation

---

## Requirements

* Ubuntu 22.04
* ROS2 Humble
* Python 3
* Colcon build system

Install required packages:

```
sudo apt update
sudo apt install ros-humble-teleop-twist-keyboard
sudo apt install ros-humble-joy
sudo apt install ros-humble-teleop-twist-joy
```

---

## Build the Workspace

Navigate to the workspace:

```
cd ~/bumperbot_ws
```

Build the project:

```
colcon build
```

Source the workspace:

```
source install/setup.bash
```

---

## Author

Ajay Gudise

mail: ajaygudise03@gmail.com
