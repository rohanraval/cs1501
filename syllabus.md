# **CS 1501 - Intro to Robotics: Autonomy, AI, and Applications**

## **Topic List**

#### Introduction to Robotics
- Types of Robots and Applications
    - Autonomous Vehicles and UGVs
        - Case Study: Uber ATG, Waymo, and Tesla... the race to level 5!
    - Drones and UAVs
        - Case Study: Skydio
    - Industrial Robotics and Home Robotics
        - Case Study: Roomba
        - Case Study: Boston Dynamics
- Core Concepts of Autonomy
    - Autonomy "Stack": Perception, Planning, and Control
    - Autonomy Execution: Business Models and Research Areas
    - Autonomy Levels: L1-L5
- Artificial Intelligence
    - Role of Machine Learning, focusing on Perception and Prediction
    - Concepts of AI - optimization and constraints

#### Mapping, Localization and Pose (MLP)
- HD Maps and Map Building
    - Granularity - lane-level vs. road-level (e.g. Google Maps)
    - Geometry - splines, curve fitting, etc.
    - Occupancy Grid Representation
    - Challenges of mapping the real world
- Sensors
    - Intro to LIDAR
    - Sensor Fusion
- Pose
    - Concept of Localization and current challenges (highways, sensor inaccuracies, etc)
    - For the more mathematically inclined, ...
        - Translation and Rotation
        - SE(2) and SO(3)
        - Euler Angles and Quaternions
- State Estimation: Kalman Filter as a way to illustrate Predict-Update cycle
    - Brief discussion on Gaussian and Bayes Rule
- __*Particle Filter*__
- SLAM - a brief overview
- If time permits.. Iterative Closest Point (ICP)... maybe?

#### Motion Planning
- Intro to Graphs
- Graph Search
    - Breadth-first Search (BFS)
    - Depth-first Search (DFS)
    - Dijkstra's Algorithm
    - ___A* Algorithm and Heuristics___
- Navigation ~ Graph Search... some caveats
- Obstacle Avoidance
- Bug algorithm
- Probabilistic Road Maps (PRM)
- Rapidly-exploring Random Trees (RRT)
- __*Artificial Potential Fields*__
    - Gradient Descent and Local Minima

#### Perception and Prediction
- Basic Visual Odometry and Computer Vision
- Intution behind Deep Learning and Neural Networks
- Lane Finding
- Vehicle and Pedestrian Detection

#### Robot Control
- Feedback Control: Open vs Closed-loop
- PID Control and Parameter Tuning
- Very high-level conceptual overview of stability, controllability and observability

#### Extra Topics
- Robot Kinematics and Dynamics
    - Forward and Inverse Kinematics
    - For the more mathematically inclined, ...
        - Euler-Lagrange Equation
        - Lagrangian Formulation
        - Netwon-Euler Equations
- Swarm Robotics
    - Multi-agent systems
    - Rendezvous Problem
