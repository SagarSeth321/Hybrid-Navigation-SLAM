# Hybrid Navigation Algorithm Integrating DRL and YOLOv8 for Enhanced SLAM Performance in Mecanum-Wheeled Robot Systems

This repository contains supplementary experimental videos and results associated with the research work on a hybrid autonomous navigation framework integrating Deep Reinforcement Learning (TD3), YOLOv8, and ORB-SLAM3 for enhanced SLAM performance and autonomous navigation of a mecanum-wheeled mobile robot.

## Overview

The proposed framework combines visual SLAM, semantic perception, and deep reinforcement learning to improve localization, mapping, path planning, and autonomous navigation performance in mobile robotic environments.

The repository provides supplementary experimental videos and selected visualization results obtained from simulation and real-world experiments.

## Repository Contents

### Supplementary Videos

The supplementary videos are available in the GitHub Release:

**[Supplementary Videos – SLAM and Autonomous Navigation Results](../../releases/tag/v1.0)**

The release contains:

- 2D LiDAR SLAM result
- Proposed hybrid navigation result
- Mobile robot SLAM demonstration

### Experimental Results

The `results/` directory contains selected experimental visualizations, including:

- 2D LiDAR SLAM maps
- ORB-SLAM3 mapping results
- Visual SLAM results
- Hybrid approach mapping results
- Laboratory experimental views

## Software Framework

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

## Robot Platform

Experiments were performed using a mecanum-wheeled mobile robot platform equipped with onboard perception and sensing systems for SLAM and autonomous navigation.

## Repository Structure

```text
Hybrid-Navigation-SLAM/
│
├── README.md
├── LICENSE
│
├── videos/
│   └── README.md
│
├── results/
│   ├── README.md
│   ├── 2D-Lidar SLAM.jpg
│   ├── LAB-View 1.jpg
│   ├── LAB-View 2.jpg
│   ├── Map by Hybrid Approach.jpg
│   ├── ORB-SLAM3 Map.jpg
│   └── Visual-SLAM Map.jpg
│
└── Releases/
    └── v1.0
