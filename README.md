# **CS 1501**
# **Intro to Robotics: Autonomy, AI, and Applications**

## **Course Description**
Introduces the basic principles of robotics, focusing on core topics in autonomy and artificial intelligence and their applications in self-driving cars, drones, and other types of robots. Students will learn the fundamentals of the autonomy stack and related AI algorithms that allow robots to perform complex tasks like navigating an environment and detecting pedestrians. Topics include: mapping, localization, motion planning and navigation, perception, prediction, motion control, and safety.

#
## **Instructors**
**Student Instructor:** Rohan Raval
* 4th year, BS Computer Science and Physics
* Interests: Autonomous Vehicle Motion Planning
* Contact: rohanraval@virginia.edu

**Faculty Advisor:** Nicola Bezzo
* Assistant Professor, ECE and Systems Engineering
* Interests: Resiliency and Security of Robotic Systems
* Contact: nbezzo@virginia.edu

#
## **Prerequisites** ##
None, although basic Computer Science coursework (at the level of CS1110) is recommended.

#
## **Course Structure** ##

- Attendance
    - Lectures will be once a week, 50 mins each. I will try my best to make lectures discussion-based as much as possible to foster engagement.
- Readings
    - There will be a list of short readings each week, from which students should pick one to write a small summary on. These readings will expand on concepts talked about in class that week or connect them with work being done in industry or academia.
- As with any course, you will get out of it what you put into it! The idea behind this course is __not__ to teach you all the theory behind robotics... rather, my goal is to present a sampling of concepts from which you can explore more about the field -- and in doing so, hopefully instill an interest in robotics (possibly as a profession!)

#
## **Schedule of Topics**

#### Week 1-2: Introduction to Robotics
- Types of Robots
    - Autonomous Vehicles and UGVs
        - Case Study: Uber ATG, Waymo, Tesla... the "race to autonomy"
    - Drones and UAVs
        - Case Study: Skydio, DJI, Zipline International
    - Industrial Robotics and Home Robotics
        - Case Study: Roomba, Boston Dynamics
- Core Concepts of Autonomy
    - Autonomy Levels
    - Autonomy Stack: Perception, Planning, and Control
    - Autonomy IRL: Research and Industry
- Artificial Intelligence in Robotics
    - What is AI? A (very) brief history
    - Role of Machine Learning, focusing on Perception and Prediction

#### Week 3-4: Mapping, Localization and Pose (MLP)
- Sensors
    - LIDAR
    - Sensor Fusion
- HD Maps and Map Building
    - Occupancy Grid Representation
    - Challenges of mapping the real world
- Pose
    - Concept of Localization
    - Representation of Pose, and Degrees of Freedom
    - Challenges in getting accurate pose
- State Estimation
    - Predict-Update cycle, and concept of Kalman Filter
- Particle Filter: key ideas and intuition
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
- Obstacle Avoidance
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

#### Week 11-12: TBD (based on student choice)
_These weeks can be used as a buffer or to cover some extra material, chosen by students from the list below._
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