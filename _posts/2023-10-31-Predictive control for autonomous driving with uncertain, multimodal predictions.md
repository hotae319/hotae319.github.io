---
layout: post
title: Predictive control for autonomous driving with uncertain, multimodal predictions
summary: Proposed a Stochastic MPC formulation for autonomous driving with multi-modal predictions of surrounding vehicles

---

# What I did

- ***Skill*** : Python, ROS2, CARLA 

- ***Keywords*** : Autonomous Vehicle, Connected Vehicles, Motion Planning, Stochastic MPC 

We proposed a Stochastic MPC formulation for autonomous driving with multi-modal predictions of surrounding vehicles. We provide a convex formulation for simultaneously (1) optimizing over parameterized feedback policies and (2) allocating risk levels to each mode for multi-modal chance constraint satisfaction. This enhances the feasibility and closed-loop performance of the SMPC algorithm, as demonstrated by our simulations and hardware experiments.

The experiment videos can be accessed at [here](https://drive.google.com/file/d/1EQJmVHb3AExu1rs3Mw4PRdML_TmWqSpW/view?usp=sharing)

Those are the two scenarios we addressed. (Turn left at the intersection, Lane change) 
<p align="center">
  <img src="/assets/rfs/carla.png" width="45%">
</p>

<p align="center">
  <img src="/assets/rfs/lane_change.png" width="45%">
</p>

This is our hardware/software setup for vehicle in the loop simulation.
<p align="center">
  <img src="/assets/rfs/harware_setup_phev.png">
</p>
<p align="center">
  <img src="/assets/rfs/RFS_simvsreal_horz.png">
</p>

This is our control/planning architecture.

<p align="center">
  <img src="/assets/rfs/planner_arch.png" width="45%">
</p>
<p align="center">
  <img src="/assets/rfs/diagram_control_arch_fix.png" width="45%">
</p>
