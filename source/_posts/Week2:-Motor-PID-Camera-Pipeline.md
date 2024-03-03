---
title: 'Week2: Motor & PID & Camera Pipeline'
date: 2024-01-01 00:00:04
index_img: '../img/digram-blur.png'
banner_img: '../img/digram-blur.png'
tags:
---
We solved the problems for week 1 and this week we will focus on how to get the vehicle to move successfully.

# Documentation Progress
- Use the App called canva to design the poster.

# Hardware Part Weekly Progress
The wiring diagram of Arduino
![arduino wiring 1](../img/wiring1.png)
![arduino wiring 2](../img/wiring2.png)

# Embedded Part Weekly Progress
The framework diagram of code for Arduino
![arduino digram](../img/digram.png)

Complete the code of the car drive and basic positioning system. Connect and test the motherboard, ensuring a successful connection with the computer to confirm the proper functionality of the vehicle drive.
![](../img/week2-1.jpg)

The output from the encoder as the wheel rotates.
<video style="width:100%;height:auto;" controls>
  <source src="/video/week2-1.webm" type="video/webm">
  Your browser does not support the video tag.
</video>

Test the wheels to see if they turn properly one by one.
<video style="width:100%;height:auto;" controls>
  <source src="/video/week2-2.webm" type="video/webm">
  Your browser does not support the video tag.
</video>

Test whether all four wheels rotate properly at the same time.
<video style="width:100%;height:auto;" controls>
  <source src="/video/week2-3.webm" type="video/webm">
  Your browser does not support the video tag.
</video>

The vehicle is moving forward successfully.
<video style="width:100%;height:auto;" controls>
  <source src="/video/week2-4.webm" type="video/webm">
  Your browser does not support the video tag.
</video>

# ROS Part Weekly Progress
Using Camera calibration package to get the internal parameters of the Logitech C270 camera
![camera calibration](../img/camera_calibration.png)

Tested the apriltag detection program
![apriltag detection demo](../img/apriltag.png)

# Problems
- Wheel Installation Issue: During the testing of the four wheels, we found that one of the wheels rotates in the opposite direction compared to the other wheels. We reinstalled the wheels to ensure that all wheels rotate in the same direction.

- Code Debugging: The control code underwent thorough scrutiny and refinement to ensure seamless synchronization between software control and hardware functionality.

# Week 3 Plan
- Integration of hardware and software.

- Establish communication protocols to enable computer control of the vehicle.

- Install a camera on the top of the car.

- Complete the design of the poster and start the writing of the introduction part of the poster.