---
layout: single
permalink: "/schedule"
title:  "Schedule"
---

#### Week 1: Introduction to Robotics [[slides][lec1]]
- What is a Robot?
- Types of Robots
- A Brief History of Robotics
- Core Concepts of Autonomy
    - See, Think, Act... AKA Perception, Planning, Control

#### Week 2: Sensors [[slides][lec2]]
- Types of Sensors
- Camera
- LiDAR
- Radar
- Ultrasonic
- GPS
- IMU
- Tradeoffs
- Sensor Fusion

#### Week 3: Mapping [[slides][lec3]]
- What are Maps? Why Maps?
- Types of Maps
- Occupancy Grid Mapping
- Reference Frames and Representations
- HD Maps and Map Building
    - Challenges of mapping the real world
    - Lyft Level5 Case Study
        - Mapping Principles and Goals
        - Layered Mapping
    - Storage and Retrieval, geometric considerations
- Sneak peek into localization...

#### Week 4: Localization I [[slides][lec4]]
- What is Localization?
  - Motivation and Definitions
- How to Represent Localization
    - Pose and Degrees of Freedom
- Challenges of Localization
- Dead Reckoning
- Probabilistic Map-based Localization
- Histogram Filter
- Predict-Update Cycle

#### Week 5: Localization II [[slides][lec5]]
- Histogram Filter Activity
- Landmark-based Mapping for Localization Algorithms
- Particle Filter (MCL)
- Kalman Filter (briefly)
- Summary of Localization Algorithms

#### Week 6: SLAM, Motion Planning I [[slides][lec6]]
- SLAM Motivation
- Graph SLAM
- Fast SLAM
- Motion Planning Motivation
  - General AI Search Problem
- Cost Functions
- Grassfire Algorithm

#### Week 7: Motion Planning II [[slides][lec7]]
- Recap of Grassfire Algorithm
- Intro to Graphs
- Depth-First Search (DFS)
- Breadth-First Search (BFS)
- Dijkstra's Algorithm

#### Week 8: Motion Planning III [[slides][lec8]]
- Motivation for Search Heuristics
- Greedy Heuristic Algorithm
- A* Algorithm
- Comparing Graph Search Algorithms
- Artificial Potential Fields
    - Gradient Descent and Local Minima

#### Week 9: Motion Control [[slides][lec9]]
- Motivation for Control
- Open-loop Control
- Closed-loop (Feedback) Control
- Control Theory
  - Objectives and Building Blocks
  - Control Signal
  - Example: Cruise Control
- Bang-Bang Controller
- P-Controller
- PID Controller
- Parameter Optimization (Tuning)

#### Week 10: Perception
- Recap of Motion Control and PID
- Basic intro to Deep Learning and Neural Networks
- Basic Computer Vision and Visual Odometry
- Common Classification Problems
    - Image Segmentation, Lane Finding, Vehicle and Pedestrian Detection
- Prediction of other actors

#### Week 11-13: TBD (based on student choice)
_These weeks can be used as a buffer or to cover some extra material, chosen by students from the list below._
- Software Engineering for Robotics
    - Intro to ROS
    - Relevant Languages, Libraries, and Packages
    - Simulators
    - Intro to Matlab
- Safety and Ethics
    - Designing Software for Safety
    - Human-Robot interaction
    - Trolley Problems
    - Liability concerns
    - AI Governance
    - Some Case Studies...
- Autonomy Ecosystem
    - Autonomy Businesses and Labs
    - Survey of the Autonomous Vehicle industry - challenges, opportunities, leaders, business models
    - Future of transportation
    - Role of Government and Standardization
    - Career opportunities
- Drones and Unmanned Aerial Vehicles
- Robot Kinematics and Dynamics (note: This is a _very_ math-heavy topic!)
- Swarm Robotics
    - Challenges of Multi-Agent Systems
- Connected Autonomous Vehicles
    - V2V and V2I (V2X)
    - Communication protocols and infrastructure
- More options TBD

<!-- lectures -->
[lec1]: https://github.com/rohanraval/cs1501/raw/master/lectures/1_intro.pdf
[lec2]: https://github.com/rohanraval/cs1501/raw/master/lectures/2_sensors.pdf
[lec3]: https://github.com/rohanraval/cs1501/raw/master/lectures/3_mapping_localization0.pdf
[lec4]: https://github.com/rohanraval/cs1501/raw/master/lectures/4_localization1.pdf
[lec5]: https://github.com/rohanraval/cs1501/raw/master/lectures/5_localization2.pdf
[lec6]: https://github.com/rohanraval/cs1501/raw/master/lectures/6_slam_planning1.pdf
[lec7]: https://github.com/rohanraval/cs1501/raw/master/lectures/7_planning2.pdf
[lec8]: https://github.com/rohanraval/cs1501/raw/master/lectures/8_planning3.pdf
[lec9]: https://github.com/rohanraval/cs1501/raw/master/lectures/9_control.pdf