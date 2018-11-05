# **CS 1501 - Intro to Robotics: Autonomy, AI, and Applications**

## **Course Description**
Introduces the basic concepts of robotics, surveying core topics in autonomy, artificial intellegence in robotics, and other applications. Students will learn the fundamentals of this growing field, while emphasizing conceptual understanding, practical approaches, and algorithms used in industry as well as academia. Topics include: mapping, localization, motion planning and navigation, perception and prediction, robot control, and safety.

## **Instructors**
**Student Instructor:** Rohan Raval
* 4th year, BS Computer Science and Physics
* Interests: Autonomous Vehicle Motion Planning
* Contact: rohanraval@virginia.edu

**Faculty Advisor:** Nicola Bezzo
* Assistant Professor, ECE and Systems Engineering
* Contact: nbezzo@virginia.edu

## **Prerequisites** ##
Basic Computer Science coursework (at the level of CS1110) is ___strongly___ advised.

## **Course Structure** ##

#### Overview
Lectures will be a combination of traditional in-class lectures and discussion-based seminar. There will be 6 short assignments, which will be either short readings or coding (depending on the topic). Each assignment is intended to take no more than 30min-1hr to complete. The goal of these assignments is to solidify understanding of topics discussed in class to gain strong practical skills as well as awareness about industry implementations.

_As with any course, you will get out of it what you put into it!_ The idea behind this course is __not__ to teach you all the theory and math behind robotics... rather, I hope to instill an interest in robotics (possibly as a profession!), and give you a diving board of concepts from which you can explore more about the field.

#### Grading Policy
- Students must attend 10 out of 12 lectures to pass.
- Students must obtain a total grade of 75% or higher on the 6 short assignments.

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

#### Week 3-4: Mapping, Localization and Pose (MLP)
- HD Maps and Map Building
    - Granularity - lane-level vs. road-level (e.g. Google Maps)
    - Occupancy Grid Representation
    - Challenges of mapping the real world
    - Extra Topics to explore (if you like math):
        - Map Representation and Geometries - splines, curve fitting, Bresenham's algorithm, etc.
- Sensors
    - Intro to LIDAR
    - Sensor Fusion
- Pose
    - Concept of Localization
    - Challenges in getting accurate pose
    - Extra Topics to explore (if you like math):
        - Representation of Pose and the idea of 6 DoF
        - Relative Poses and Transforms
        - Translation and Rotation
        - 3D Pose and SO(3)
        - Euler Angles
        - Gimbal Lock and Quaternions
- State Estimation
    - Predict-Update cycle, and concept of Kalman Filter
- Particle Filter: key ideas and intuition
- SLAM
    - a (very) brief overview of FastSLAM
- Extra Topics to explore:
    - Iterative Closest Point (ICP) Algorithm

#### Week 5-8: Motion Planning and Navigation
- Intro to Graphs
- Graph Search
    - Breadth-first Search (BFS)
    - Depth-first Search (DFS)
    - Grassfire Algorithm
    - Dijkstra's Algorithm
    - A* Algorithm and Heuristics
- Navigation ~ Graph Search... some caveats
- Obstacle Avoidance
    - Bug algorithm
- Probabilistic Road Maps (PRM)
- Rapidly-exploring Random Trees (RRT)
- Artificial Potential Fields
    - Gradient Descent and Local Minima
- Real-world Motion Planning challenges
    - Occlusions, Speed Regressions, Unprotected Turns, etc

#### Week 9: Perception and Prediction
- Intution behind Deep Learning and Neural Networks
- _Basic_ Visual Odometry and Computer Vision
- Classification
    - Image Segmentation
    - Lane Finding
    - Vehicle and Pedestrian Detection

#### Week 10: Robot Control
- Feedback: Open vs Closed-loop
- PID Controller
- Extra Topics to explore (if you like math):
    - Linear Time-Invariant Control Systems (LTI)
    - Stability, controllability and observability

#### Week 11-12: TBD (based on student choice)
_This week can be used to cover some extra material, chosen by students from the list below, or can be used as a buffer in case of previous lectures running over._
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
    - Discussion on the future of transportation, sharing economy, public infrastructure, financial and energy systems as a result of autonomy
- Robot Kinematics and Dynamics
    - _Note: This is a very math-heavy topic!_
    - Forward and Inverse Kinematics
    - Equations of Motion
        - Lagrangian Formulation of Mechanics
        - Euler-Lagrange Equation, and derivation from Calculus of Variations
- Swarm Robotics
    - Challenges of Multi-Agent Systems
    - Rendezvous Problem
- Connected Autonomous Vehicles
    - V2V and V2I (V2X)
    - Communication protocols and infrastructure
- More options TBD