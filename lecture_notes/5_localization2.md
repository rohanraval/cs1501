# Lecture 5: Localization II and SLAM

## Agenda
- Housekeeping tasks
- Recap probabilistic localization (one last time...)
- Exercise on Histogram Filter
- Introduce Particle Filter
- Introduce Kalman Filter, briefly
- SLAM motivation and formulation
    - Walk through FastSLAM algorithm, high-level
- If time, ... intro to Graphs

## Notes

### Housekeeping
- Roster Attendance
  - promised to learn most people's names... sorry!
- How are the reading responses going?

---

### Recap: Prob Localization (MCL) and Histogram Filter (2-3 min)
- Last time walking through the pictorial example
- Describe histogram filter as a discretized implementation
- Histogram Filter vs general Recursive Bayes (Probabilistic) Localization
  - Why is it called a Histogram Filter?

---

### Exercise: Histogram Filter (6-8 min)
- split into teams of 2-3 (incentive? -- maybe make everyone group up and randomly call on someone?)
- Use same example as last time...
- Add in a last part (sense)

---

### Particle Filter (10-12 min)

#### Overview of Particle Filter
- state space: continuous
- belief: multimodal (like all MCL)
- efficiency: ? -- many domains scale exponentially, some domains (like tracking) is better
- easy to program!

#### Example video (complex)
- no clue where it is, need to find where it is (global loc)
- use range sensors
- each red dot is a discrete guess as to where it is (x,y,heading)... the set of guesses comprises the posterior
- particle filter makes particles survive in proportion to how consistent particle is to sensor measurement
- symmetry broken
- "Survival of the Fittest!"

#### Algorithm

0. Model Robot World
   - cyclic world, 4 landmarks, robot can sense distance to each landmark
   - 1000 random guesses (particles) as to where the robot will be -- (x,y, heading)

1. Simulate Motion
   - Each particle should move somehow

2. Distance Calculation
   - get the observed distance of **each** particle from **all** landmarks
   - some noise associated with measurement, but that's fine for now...
   - 

#### Advantages
- Can model arbitrary distributions (multimodal) vs Kalman filter, which gives a single Gaussian representing pose (unimodal)

#### Disadvantages
- Only really works well in low-dimensional spaces -- too many particles in high-dim spaces (too much memory required)
- Depends a lot on how many particles you have... the more the better!

---

### SLAM (20 min?)

What if we want to map and localize simultaneously? i.e. What if we are in an unknown environment and want to navigate it?
- Known Location, Unknown Map = Mapping
  - location is known typically by human driver or operator
- Unknown Location, Known Map = Localization
- Unknown Location, Unknown Map = SLAM!

First, an aside on two main types of mapping:
- Occupancy Mapping (covered before)
  - environment is discretized into cells
  - each cell is free (0) or occupied (1)
- Landmark-based (or Feature) Mapping
  - environment consists of isolated landmarks (points)
  - set of landmarks __is__ the map!

How to approach SLAM?
- What do we know?
  - Why was mapping so easy? ... Because we knew the location!
    - Revisit Occ Grid Mapping example to explain this
  - Well... particle filter gives us the location, but it gives us _several_ estimates of location (particles)
  - So maybe take one of them and just use that as the "true location"... and then do mapping?
    - OR... Use **all** of them! --> FAST-SLAM!

FastSLAM Procedure
- 
