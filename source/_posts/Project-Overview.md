---
title: 'Project Overview'
date: 2024-01-01 00:00:01
index_img: '../img/final.jpg'
banner_img: '../img/final.jpg'
tags: 
---

# PIAGV: Intergating Apriltag Localization with Encoder-IMU Odometry for Path Scheduling in Multi-Robot Warehouse System

This is an university of Liverpool year 2 project.

Our project tackles path planning in unmanned warehouses with multiple vehicles, covering hardware and software aspects. Each vehicle includes actuators, a brain controller, and sensors. The brain, an onboard PC, handles tasks like location determination and image processing, while the microcontroller executes motor control and encoder reading. The camera provides absolute coordinates, the IMU measures angles for chassis orientation, and encoders record wheel rotations. Software-wise, we integrate positioning and navigation functions using sensor data processing modules and algorithms for accurate pose estimation. Integration with ROS 2's navigation stack, enables autonomous navigation in real-time for efficient path scheduling within the warehouse.

The entire project is completely open source, embedded controller source code can be found [here](https://github.com/uol2324y2p50/piagv-embedded), ros2 source code can be found [here](https://github.com/uol2324y2p50/piagv).

# Team members
- Linxuan Biao
- Ce Wang
- Chaoshuo Han
- Jingyi Liu
- Lu Chen

# Acknowlegement
- This project is supported by University of Liverpool.

# Legal Information
- The source code associated with the PIAGV project is released under the GNU General Public License version 3 (GPLv3). Any use, modification, or distribution of the source code must adhere to the terms of GPLv3.
- This document pertains to the PIAGV project and is released under the Creative Commons Attribution-NonCommercial (CC-BY-NC) license. Any use of the material within this documentation must comply with the terms of this license.