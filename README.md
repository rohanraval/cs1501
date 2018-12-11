# **CS 1501 - Intro to Robotics: Autonomy, AI, and Applications**

## **Course Description**
Introduces the basic principles of robotics, focusing on core topics in autonomy and artificial intelligence, as well as their applications in self-driving cars, drones, and other types of robots. Students will learn the fundamentals of the autonomy stack and related AI algorithms that allow robots to perform complex tasks like navigating an environment and predicting the behavior of other cars. Topics include: mapping, localization, motion planning and navigation, perception, prediction, robot control, and safety.


## **Instructors**
**Student Instructor:** Rohan Raval
* 4th year, BS Computer Science and Physics
* Interests: Autonomous Vehicle Motion Planning
* Contact: rohanraval@virginia.edu

**Faculty Advisor:** Nicola Bezzo
* Assistant Professor, ECE and Systems Engineering
* Contact: nbezzo@virginia.edu

## **Prerequisites** ##
None, although basic Computer Science coursework (at the level of CS1110) is advised.

## **Course Structure** ##

- Attendance
    - Lectures will be once a week, 50 mins each. I will try my best to have lectures be discussion-based as much as possible to foster engagement -- all your other classes are probably boring lectures, this one doesn't need to be that way as well :)
- Readings
    - There will be a list of short readings each week, from which students should pick one to write a small summary on. These readings will expand on concepts talked about in class that week or connect them with work being done in industry or academia.
- As with any course, you will get out of it what you put into it! The idea behind this course is __not__ to teach you all the theory behind robotics... rather, I hope to instill an interest in robotics (possibly as a profession!), and give you a broad overview of concepts from which you can explore more about the field.

## **Schedule of Topics**

#### Week 1-2: Introduction to Robotics
- Types of Robots
    - Autonomous Vehicles and UGVs
        - Case Study: Uber ATG, Waymo, and Tesla... the "race to autonomy"!
    - Drones and UAVs
        - Case Study: Skydio
    - Industrial Robotics and Home Robotics
        - Case Study: Roomba, Boston Dynamics
- Core Concepts of Autonomy
    - Autonomy Levels: L1-L5
    - Autonomy "Stack": Perception, Planning, and Control
    - Autonomy Execution: Business Models and Research Areas
- Artificial Intelligence in Robotics
    - Role of Machine Learning, focusing on Perception and Prediction
    - What is AI? A (very) brief summary

#### Week 3-4: Mapping, Localization and Pose (MLP)
- Sensors
    - LIDAR
    - Sensor Fusion
- HD Maps and Map Building
    - Granularity - lane-level vs. road-level (e.g. Google Maps)
    - Occupancy Grid Representation
    - Challenges of mapping the real world
    - _Extra Topics to explore (if you like math):_
        - _Map Representation and Geometries - splines, curve fitting, Bresenham's algorithm, etc._
- Pose
    - Concept of Localization
    - Challenges in getting accurate pose
    - _Extra Topics to explore (if you like math):_
        - _Representation of Pose and the idea of 6 DoF_
        - _Relative Poses and Transforms_
        - _Translation and Rotation_
        - _3D Pose and SO(3)_
        - _Euler Angles_
        - _Gimbal Lock and Quaternions_
- State Estimation
    - Predict-Update cycle, and concept of Kalman Filter
- Particle Filter: key ideas and intuition
- SLAM (Simultaneous Localization and Mapping)
    - a (very) brief overview of FastSLAM
- Extra Topics (if time):
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
- Probabilistic Road Maps (PRM) -- brief
- Rapidly-exploring Random Trees (RRT) -- brief
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
- Prediction of Actors

#### Week 10: Robot Control
- Feedback: Open vs Closed-loop
- PID Controller
- _Extra Topics to explore (if you like math):_
    - _Linear Time-Invariant Control Systems (LTI)_
    - _Stability, controllability and observability_

#### Week 11-12: TBD (based on student choice)
_This week can be used to cover some extra material, chosen by students from the list below, or can be used as a buffer in case of previous lectures running over._
- Ethics and Safety
    - Designing Software for Safety
    - Human-Robot interaction
    - Trolley Problems
    - Liability concerns
    - AI Governance
    - Some Case Studies...
- Autonomy Ecosystem
    - Autonomy Businesses and Labs
    - In-depth Survey of the Autonomous Vehicle industry - challenges, leaders, opportunities and risks, business models
    - Discussion on the future of transportation, sharing economy, public infrastructure, financial and energy systems as a result of autonomy
- Drones and Unmanned Aerial Vehicles
    - Differences between UAVs and UGVs (Unmanned Ground Vehicles)
- Robot Kinematics and Dynamics
    - _Note: This is a very math-heavy topic!_
    - Forward and Inverse Kinematics
    - Equations of Motion
        - Lagrangian Formulation of Mechanics
        - Euler-Lagrange Equation, and derivation from Calculus of Variations
- Swarm Robotics
    - Challenges of Multi-Agent Systems
- Connected Autonomous Vehicles
    - V2V and V2I (V2X)
    - Communication protocols and infrastructure
- More options TBD