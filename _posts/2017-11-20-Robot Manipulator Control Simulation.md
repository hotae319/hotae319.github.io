---
layout: post
title: "Control robot manipulator named ABB IRB-1200-5 to accomplish the given task such as picking up, removing rust and polishing"
featured-img: manipulator
---

# What I did

- ***Skill*** : Matlab, Simulink, Robotic Toolbox from Peter Corke

- ***Keywords*** : Computed Torque Control, Robust/Adaptive Passivity based Control, Torque Control, Hybrid force-position control

# Sum up 

In the graduate lecture named "robot mechanics and control", I learned the overall robotics dynamics, control and some of optimal control.
This lecture required the final project about simulation of robot manipulator controller. The required tasks to ABB IRB 1200-5 manipulator are i) picking up a steel workpiece with cylindrical shape; ii) removing rust by locating the workpiece in front of the mounted laser; and iii) polishing it using a sanding belt. 
I learned how to simulate the robot’s task as close to reality as possible. I simulated an IRB 1200 manipulator of ABB which can complete various tasks while considering the update frequency and the encoder’s error. Furthermore, I applied a lot of control algorithm such as kinematic control, robust and adaptive control, even hybrid position-force control with some holonomic constraints. 

<p align="center">
  <img src="/assets/img/posts/manipulator.jpg">
</p>

It described the kinematics and dynamics of robot model. It was resolved by robotic toolbox.

<p align="center">
  <img src="/assets/img/posts/mani1.jpg">
</p>

These figures showed how the manipulator moves and accomplishes the tasks.

You can read my [final report paper](https://hotae319.github.io/assets/Hotae_Lee_FinalProject_Robot%20Mechanics.pdf). It was not complete form but you can check what I did and how I did. 
