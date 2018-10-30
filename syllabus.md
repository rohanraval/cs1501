# **CS 1501 - Intro to Robotics: Autonomy, AI, and Applications**

## **Course Description**
Introduces the basic concepts of robotics, surveying autonomous robots, artificial intellegence in robotics, and other applications. Students will learn the fundamentals of this growing field, while emphasizing practical approaches and algorithms used in industry as well as academia. 

Topics include: mapping, localization, motion planning and navigation, perception and prediction (including basic computer vision), robot control, and more.

## **Instructors**
**Student Instructor:** Rohan Raval
* 4th year, BS Computer Science and Physics
* Interests: Autonomous Vehicle Motion Planning
* Contact: rohanraval@virginia.edu

**Faculty Advisor:** Nicola Bezzo
* Assistant Professor, ECE and Systems Engineering
* Contact: nbezzo@virginia.edu

## **Prerequisites** ##
Basic Computer Science coursework (at the level of CS1110) and familiarity with Python, are ___strongly___ advised.

## **Course Structure** ##

#### Overview
This course will be a combination of traditional in-class lectures, and hands-on activities. There will be coding assignments, sometimes during class and sometimes outside of class, which can be completed in groups of two. Each coding assignment is intended to take no more than 2 hours to complete. The goal of these coding assignments is to simulate the robotics algorithms and techniques being discussed in class in order to gain strong practical skills. 

_As with any course, you will get out of it what you put into it!_ The idea behind this course is __not__ to teach you all the theory behind robotics... rather, I hope to instill an interest in robotics (possibly as a profession!), and give you a diving board from which you can explore more about this field.

#### Grading Policy
- Students must attend 9 out of 12 lectures to pass.
- There will be one coding assignment per section (see below), and thus 6 coding assignments. Students must complete at least 5 out of the 6 assignments, and in all completed assignments, must obtain a grade of 75% or higher.

## **Topics and Schedule**

#### Week 1-2: Introduction to Robotics
- Types of Robots
    - Autonomous Vehicles and UGVs
        - Case Study: Uber ATG, Waymo, and Tesla... the race to autonomy!
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
    - Core Concepts of AI - optimization and constraints

#### Week 3-5: Mapping, Localization and Pose (MLP)
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
    - ___Representing Pose - general idea___
        - 6 DoF: {x,y,z, roll, pitch, yaw}
        - Relative Poses and Transforms
    - For the more mathematically inclined, ...
        - Translation and Rotation
        - 3D Pose and SO(3)
        - Euler Angles
        - Gimbal Lock and Quaternions
- State Estimation: Kalman Filter as a way to illustrate Predict-Update cycle
    - Brief discussion on Gaussians and Bayes Rule
- ___Particle Filter___
- SLAM - a brief overview
- If time permits.. Iterative Closest Point (ICP) Algorithm

#### Week 6-8: Motion Planning and Navigation
- Intro to Graphs
- Graph Search
    - Breadth-first Search (BFS)
    - Depth-first Search (DFS)
    - Grassfire Algorithm
    - Dijkstra's Algorithm
    - ___A* Algorithm and Heuristics___
- Navigation ~ Graph Search... some caveats
- Obstacle Avoidance
    - Bug algorithm
- Probabilistic Road Maps (PRM)
- Rapidly-exploring Random Trees (RRT)
- ___Artificial Potential Fields___
    - Gradient Descent and Local Minima
- ___Real-world Motion Planning challenges___
    - Occlusions, Speed Regressions, Unprotected Turns, etc

#### Week 9: Perception and Prediction
- Intution behind Deep Learning and Neural Networks
- Basic Visual Odometry and Computer Vision
- Image Segmentation
- Lane Finding
- Vehicle and Pedestrian Detection

#### Week 10: Robot Control
- Feedback Control: Open vs Closed-loop
- ___PID Controller___
- Very high-level conceptual overview of stability, controllability and observability

#### Week 11-12: Extra Topics
_This week can be used to cover some extra material, chosen by students from the list below, or can be used as a buffer in case of previous lectures running over._
- Robot Kinematics and Dynamics
    - _Note: This is a very math-heavy topic!_
    - Forward and Inverse Kinematics
    - Equations of Motion
        - Lagrangian Formulation of Mechanics
        - Euler-Lagrange Equation, and derivation from Calculus of Variations
- Swarm Robotics
    - Challenges of Multi-Agent Systems
    - Rendezvous Problem
- Ethics and Safety
    - Designing Software for Safety
    - Human-Robot interaction
    - Trolley Problem
    - Liability concerns
    - AI Governance
    - Some Case Studies...
- Autonomy Ecosystem
    - Autonomy Businesses and Labs
    - In-depth Survey of the Autonomous Vehicle industry - challenges, leaders, opportunities and risks, business models
    - Discussion on the future of transportation, sharing economy, urban planning and energy systems as a result of autonomy
- Connected Autonomous Vehicles
    - V2V and V2I (V2X)
    - Communication protocols and infrastructure
- More options TBD