# Robotics TurtleBot3 ROS 2 Humble

Dockerized ROS 2 Humble Development Environment.

## Environment

- Operating System: Ubuntu 22.04 LTS (WSL2 Windows 11)
- Docker Engine: 29.8.0
- Docker Compose: v5.5.1
- ROS Distribution: ROS 2 Humble
- Base Image: ros:humble-ros-base-jammy

## Module 1

Dockerized ROS 2 Development Environment

## Completed Experiment

### ROS 2 Workspace

Workspace:
```
~/robotics_ws
```

Package:
```
my_first_robot_package
```

Build command:
```
colcon build --symlink-install
```

Run command:
```
ros2 run my_first_robot_package hello_robot
```

## Result

ROS 2 Humble successfully runs inside Docker container.

Node output:

## Repository Structure
```
robotics-turtlebot3
├── docker
├── src
├── config
├── launch
├── maps
├── data
├── docs
└── tests
```

