# Hybrid Navigation Algorithm Integrating DRL and YOLOv8 for Enhanced SLAM Performance in Mecanum-Wheeled Robot Systems

## About

This repository contains the source code, supplementary experimental videos, and selected experimental results associated with the research work on a hybrid autonomous navigation framework integrating Deep Reinforcement Learning (TD3), YOLOv8, and ORB-SLAM3 for enhanced SLAM performance in mecanum-wheeled mobile robot systems.

The repository is provided as supplementary material for research evaluation and reproducibility.

## Repository Contents

### 1. Source Code

The `code/slam/` directory contains the ROS 2 SLAM package used in the experimental framework.

It includes:

- SLAM configuration files
- Launch files
- RViz configurations
- Mapping files
- SLAM nodes
- ROS 2 package configuration

### 2. Supplementary Videos

Supplementary experimental videos are available in the GitHub Release:

**[Supplementary Videos – SLAM and Autonomous Navigation Results](../../releases/tag/v1.0)**

The release includes:

- 2D LiDAR SLAM result
- Proposed hybrid navigation result
- Mobile robot SLAM demonstration

### 3. Experimental Results

The `results/` directory contains selected experimental visualizations, including:

- 2D LiDAR SLAM
- ORB-SLAM3 mapping
- Visual SLAM
- Hybrid approach mapping
- Laboratory experimental results

## Software

The experimental framework uses:

- ROS 2 Humble
- ORB-SLAM3
- YOLOv8
- Deep Reinforcement Learning (TD3)
- Nav2
- Gazebo
- RViz
- OpenCV
- Python

## Hardware

The experimental evaluation was performed using a mecanum-wheeled mobile robot equipped with onboard sensing and perception systems for SLAM and autonomous navigation.

## Repository Structure

```text
Hybrid-Navigation-SLAM/
│
├── README.md
├── LICENSE
│
├── code/
│   └── slam/
│       ├── config/
│       ├── launch/
│       ├── maps/
│       ├── resource/
│       ├── rviz/
│       ├── slam/
│       ├── test/
│       ├── package.xml
│       ├── setup.cfg
│       └── setup.py
│
├── results/
│   ├── README.md
│   └── Experimental Results
│
└── videos/
    └── README.md
