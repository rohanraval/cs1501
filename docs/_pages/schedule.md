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
    - Exterocetive vs Propriocetpive
    - Active vs Passive
- Camera
- LiDAR
- Radar
- Ultrasonic
- GPS
- IMU
- Tradeoffs
- Sensor Fusion

#### Week 3-4: Mapping and Localization
- HD Maps and Map Building
    - Occupancy Grid Representation
    - Challenges of mapping the real world
- Pose
    - What is Localization?
    - Representation of Pose, and Degrees of Freedom
    - Challenges in getting accurate pose
- State Estimation Algorithms
    - Recursive Bayes and Predict-Update cycle
    - Histogram Filter
    - Kalman Filter
    - Particle Filter
- SLAM (Simultaneous Localization and Mapping)
- (if time) Iterative Closest Point (ICP) Algorithm

#### Week 5-7: Motion Planning and Navigation
- Intro to Graphs
- Graph Search
    - Breadth-first Search (BFS)
    - Depth-first Search (DFS)
    - Grassfire Algorithm
    - Dijkstra's Algorithm
    - A* Algorithm and Heuristics
- Navigation as a Graph Search problem
- Obstacle Avoidance and C-Space
- Probabilistic Road Maps (PRM), briefly
- Rapidly-exploring Random Trees (RRT), briefly
- Artificial Potential Fields
    - Gradient Descent and Local Minima
- Real-world Motion Planning challenges
    - Occlusions, Speed Regressions, Unprotected Turns, etc

#### Week 8-9: Perception and Prediction
- Basic intro to Deep Learning and Neural Networks
- Basic Computer Vision and Visual Odometry
- Common Classification Problems
    - Image Segmentation, Lane Finding, Vehicle and Pedestrian Detection
- Prediction of other actors

#### Week 9-10: Motion Control
- Feedback: Open vs Closed-loop
- PID Controller

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
