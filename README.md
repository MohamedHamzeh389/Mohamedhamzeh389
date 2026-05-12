## Hi there, I'm Mohamed  👋
 
EE student at the University of Windsor with a thing for autonomous systems, control theory, and building software that does something real. I care less about which stack and more about whether the problem is interesting.
 
Currently a Powerhouse Engineering Intern at Highbury Canco - interpreting electrical schematics, updating CAD blueprints, and supporting capital projects across a large-scale manufacturing facility. On the side I spend most of my time on autonomous vehicle research and embedded projects.
 
---
 
## what I'm building
 
**🔁 Roundabout MPC** *(going public end of summer)*
Autonomous vehicle trajectory planner built from the ground up. Real satellite imagery processed with a custom OpenCV pipeline, reference path generated via parametric spline fitting, and a full Model Predictive Control implementation using a bicycle kinematic model. Includes jerk minimization, speed-dependent steering limits, lateral acceleration constraints referenced against ISO passenger comfort thresholds, and a pure pursuit comparison controller. The whole thing runs on a real aerial map of a real roundabout.
 
**🚗 CACC Reinforcement Learning** 
Custom RL physics engine in Python simulating Cooperative Adaptive Cruise Control. Trained a PPO agent over 500k timesteps on real NGSIM I-80 highway telemetry with dynamic reward functions optimizing time headway, collision avoidance, and leader behaviour smoothing.
 
---
 
## tech I use
 
```
Languages    Python · C++
ML / RL      Stable-Baselines3 · PPO · custom physics engines
Control      MPC · CVXPY · bicycle kinematic models · pure pursuit
CV           OpenCV · satellite image processing · spline fitting
Embedded     Arduino · circuit prototyping · sensor integration
Tools        AutoCAD · MATLAB · Simulink · Git
