---
layout: post
title: System Engineering Project 1
description:  Autonomous Navigation with LIMO Robot. Developed real-time SLAM maps with RTAB-Map, implemented waypoint-based navigation, and designed a custom testing arena for evaluating path planning and obstacle avoidance. 
skills: 
  - ROS(Melodic)
  - Python

main-image: /limo.png
---

---
# Arena Design Overview
---

## Changi Airport Terminal 1/Preliminary Arena Design
{% include image-gallery.html images="t1_reference.png" height="400" %}
{% include image-gallery.html images="preliminary_arena_design.png" height="400" %}

The layout of the arena was inspired by the departure hall of Changi Airport Terminal 1, particularly the area surrounding the FAST check-in zone and boarding access gates. This environment was selected as a reference due to its structured flow, open layout, and realistic operational constraints.

This design emulates a semi-structured, real-world indoor environment, with deliberate inclusion of tight paths, sensory triggers and blind spots. which provides the ideal conditions for testing:
  - Waypoint navigation,
  - Real-time SLAM (via RTAB-Map),
  - Path planning in dynamic obstacle scenarios.

## Arena Design Visualized with 3D Modeling
{% include image-gallery.html images="solidwork_arena.png" height="400" %}

To support the physical planning and spatial validation of the robot navigation testbed, the preliminary 2D sketch was translated into a 3D model using SolidWorks.

## Finalize Arena Design
{% include image-gallery.html images="finalise_arena.png" height="400" %}

The final physical arena was constructed based on the initial conceptual layout and CAD visualization. It replicates a scaled-down version of a structured indoor environment — inspired by real-world airport terminals

  - Enclosed Room & Escalator Zone
    Simulates interactive or dynamic zones such as baggage screening or waiting lounges.

  - Pathways and Boundaries
    White boundaries help with LiDAR and depth sensor feedback, ensuring robust obstacle detection and wall-following     capabilities. 
---

## Changi Terminal 1 Kinetic Rain
<br>
{% include youtube-video.html id="NXuQnDeIyY8" autoplay= "false"%} 
<br>

## A view of Changi T1 in real-life
[Changi Terminal 1](https://www.changiairport.com/en/at-changi/terminal-guides/terminal-1.html)
