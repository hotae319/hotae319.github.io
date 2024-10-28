---
layout: post
title: Stochastic MPC with Realization-Adaptive Constraint Tightening
summary: Proposed a novel and efficient offline sampled based approach to design a stochastic MPC for constrained linear systems with an additive disturbance
featured-img: smpc_intuition

---

# What I did

- ***Skill*** : MATLAB
- ***Keywords*** : Stochastic MPC, Uncertainty, Offline Sampling, Chance Constraints

In this research, I want to use offline sampling approach to make scenario approach style practically tractable and want to propose a new reformulation of chance constraints, where the constraint tightening is computed by adjusting the offline computed sets based on the previously realized disturbances along the trajectory.

Therefore, this paper presents a stochastic model predictive controller (SMPC) for linear time-invariant systems in the presence of additive disturbances. The distribution of the
disturbance is unknown and is assumed to have a bounded support. A sample-based strategy is used to compute sets of disturbance sequences necessary for robustifying the state chance
constraints. These sets are constructed offline using samples of the disturbance extracted from its support. 

For online MPC implementation, we propose a novel reformulation strategy of the chance constraints, where the constraint tightening is computed by adjusting the offline computed sets based on the
previously realized disturbances along the trajectory.
The proposed MPC is recursive feasible and can lower conservatism over existing SMPC approaches at the cost of higher offline computational time. Numerical simulations demonstrate
the effectiveness of the proposed approach.

The performance increase compared to the existing method is described as below in terms of ROA and average costs.
<p float="left">
  <img src="/assets/smpc/roa_smpc.png" width="45%" />
  <img src="/assets/smpc/smpc_table.png" width="45%" />
</p>
