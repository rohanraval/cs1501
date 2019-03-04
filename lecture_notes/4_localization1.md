# Lecture 4: Localization I

## Agenda
- Housekeeping tasks
- Recap mapping and re-explain whatever was glossed over last time
- Reintroduce Localization
- Revisit dead-reckoning
- Revisit histogram filter example
- Understand histogram filter formally
- Particle filter algorithm
- Kalman Filter? Maybe...

## Notes

### Housekeeping
- How are the reading responses going?
- Feedback on denseness of last lecture (as compared to engaging sensors lecture)? Make more engaging or want to learn more info?
    - Goal is to help everyone logically follow and arrive at concepts themselves by building off previous concepts, not to deliver boring data (flow!)
- "I realized that last week's lecture was pretty dense; so today, I wanted to take it a little slower and reintroduce localization in a more intuitive, friendly way... I wanted to have more of a collective discussion about what it is, at its core, and how we can start approaching it... rather than start throwing theories at you! 

---

### Recap: Mapping (2min)
- Re-emphasize Layered Mapping in industry
- Re-emphasize geometric challenges

---

### Recap: Pose (3-4min)

_Question_: What do we need to know 

- What is Pose? Just a location -- goal is to represent localization in some formal way
- 6DoF pose is what we want
- Dead-reckoning -- revisit motivation
    - Loss of GPS
    - Use wheel odometry
    - Re-emphasize __cumulative errors__!

### Recap: Re-introduce Probabilistic Localization (3-5min)
- Walk through Histogram Filter example again
- ask questions and make sure everyone understands this predict-update cycle concept
    - build intuition!!

---

### State Estimation
State Estimation = __Process of determining the best value of some physical quantity from noisy measurements__
- sensors aren't perfect or deterministic
- state estimation is a fundamental process for any robot with sensors

Localization is one of the most important types of State Estimation
- Localization = The method by which we determine the position and orientation of robot in the "world"
