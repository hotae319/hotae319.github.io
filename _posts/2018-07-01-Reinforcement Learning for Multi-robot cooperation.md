---
layout: post
title: Reinforcement Learning for Multi-Mobile Manipulators Cooperation with Obstacle Avoidance
summary: In this research, I apply DQN(Deep Q-network) to solving the cooperative carrying object problem. To optimize the learning method for navigation problem, this work uses curriculum learning and develops revised mini-batch sampling method which always includes a success state. Also, this work uses the method which reduces the action space through allocating one step for one agent.
featured-img: multirobot
---

# What I did

- ***Skill*** : Python, Tensorflow, OpenAI gym

- ***Keywords*** : Q-learning, Deep Q-Network, Revised Mini-batch sampling method, planning based Reinforcement Learning


From March 2018 to June 2018, I researched about stochastic control and reinforcement learning at SNU graduate lecture. While I was participating in this lecture, I focused on how to apply reinforcement learning to robotics research. Therefore, I decided the project topic about application of reinforcement learning to multi-robot cooperation problem. In particular, I performed optimal planning to carry on objects for two agents while avoiding obstacles. I utilized Deep Q-Network with my revised mini-batch sampling method to solve the unevenly distributed-reward planning problem. This experience taught me the potential of RL as a breakthrough to generate the reward-maximized motion trajectory in robotics without an exact reference. With physical uncertainties, RL can also help optimize control and planning for robust and successful performance rather than conventional optimal filtering method. 

# Sum up Slides

<p align="center">
<img src="/assets/RL_project/RL1.jpg"  alt="presentation1" width="800"> 

<img src="/assets/RL_project/RL2.jpg"  alt="presentation2" width="800"> 

</p>

You can read my [final paper](https://hotae319.github.io/assets/SCRL_Project_paper_Hotae_Lee.pdf) about this work.
