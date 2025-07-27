---
layout: post
title: System Engineering Project 1
description: 
  Autonomous Navigation with LIMO Robot. Developed real-time SLAM maps with RTAB-Map, implemented waypoint-based navigation, and designed a custom testing arena.
  
skills:
  - ROS(Melodic)
  - Python

main-image: /limo.png
---
---
For source code and program details, visit [Team 7 SEP GitHub Repo](https://github.com/pokohroh/ros-portfolio).
<br>

---
# LIMO Overview
---
{% include image-gallery.html images="limo_robot.png" height="400" %}
<br>

LIMO is an advanced multi-modal mobile robot platform developed by AgileX Robotics. It is designed for robotics education, research, and autonomous navigation projects.
<br>
The robot features:
- A modular chassis with four-wheel differential drive.
- Multiple sensor integration including LiDAR, depth camera, IMU, and wheel encoders.
- Support for autonomous navigation with ROS 1 and ROS 2.
- Compact design suitable for indoor environments and testing arenas.
<br>

---
# Arena Design Overview
---

## Changi Airport Terminal 1/Preliminary Arena Design
<br>
{% include image-gallery.html images="limo_robot.png" height="400" %}
<br>

The layout of the arena was inspired by the departure hall of Changi Airport Terminal 1, particularly the area surrounding the FAST check-in zone and boarding access gates. This environment was selected as a reference due to its structured flow, open layout, and realistic operational constraints.

This design emulates a semi-structured, real-world indoor environment, with deliberate inclusion of tight paths, sensory triggers and blind spots. which provides the ideal conditions for testing

 - Waypoint Navigation,
 - Real-time SLAM(via RTAB-Map),
 - Path planning in dynamic obstacle scenarios.

## 3D Model to Physical Arena Design
{% include image-gallery.html images="3d_to_physical.png" height="400" %}

<br>To support the physical planning and spatial validation of the robot navigation testbed, the preliminary 2D sketch was translated into a 3D model using SolidWorks.

The final physical arena was constructed based on the initial conceptual layout and CAD visualization. It replicates a scaled-down version of a structured indoor environment of Terminal 1. Walls and setpieces like the Kinetic Rain and escalator 
  - **Enclosed Room & Escalator Zone** <br>
    Simulates interactive or dynamic zones such as baggage screening or waiting lounges.

  - **Pathways and Boundaries** <br>
    White boundaries help with LiDAR and depth sensor feedback, ensuring robust obstacle detection. 
<br>

---
# Mapping And Navigation
---
## Full Arena Overview
{% include image-gallery.html images="full_arena_plot.png" height="400" %}
<br>
This is the full arena that includes 7 other plots made by other teams. Each plot is 1500 mm by 1300 mm. Mapping the full arena will produce a 4500 mm by 3900 mm map.
<br>

---
## Rtab Mapping 
{% include image-gallery.html images="complete_map_with_inflation.png" height="400" %}
<br>
The map on the left is the 2D map done by LiDar sensor using RTab-Map displayed on Rviz. The top right corner is plot 1 which belongs to my team. <br>
The map on the right shows the inflation zone or buffer zone for the obstacles. This information is crucial to avoid hitting obstacle that are shaped unevenly.


---
## Live Demo of LIMO Robot Autonomous Navigation
<br>
{% include youtube-video.html id="j3m7Y_IHGFs" autoplay= "true"%} 


---
## Changi Terminal 1 Kinetic Rain
<br>
{% include youtube-video.html id="NXuQnDeIyY8" autoplay= "false"%} 


## A view of Changi T1 in real-life
[Changi Terminal 1](https://www.changiairport.com/en/at-changi/terminal-guides/terminal-1.html)
