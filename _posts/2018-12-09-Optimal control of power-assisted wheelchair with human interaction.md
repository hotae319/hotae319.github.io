---
layout: post
title: Optimal Control of Power-Assisted Wheelchair with Human Interaction
summary: Developed the adaptive optimal controller of power-assisted wheelchair with human-interaction and Integrated whole system from sensors and controller to communications
featured-img: wheelchair

---

# What I did

- ***Skill*** : C/C++, Arduino, System Integration(MCU, IMU, BLDC Motor, Motor Driver etc.)

- ***Keywords*** : Power-Assisted, Disturbance Observer, Dynamics and Kalman Filter Observer, Constrained Optimal Control, Model Predicitve Control, Human-Interaction 

Let's say how and why I started my project in `NAVER LABS`.

I seriously wondered about the practicality of using theories in real robotic applications because my projects were mainly simulation based. 
To explore this curiosity, I worked at <font color='dodgerblue'> NAVER LABS Robotics group </font>. I seized the opportunity to develop a human-interaction wheelchair controller. 
While I integrated all parts from sensors to communications, I became equipped with more practical skills. 
I also developed a robust force compensation control algorithm with pose estimation so the wheelchair could be driven freely on slopes. 
The unmeasured external force problem, a challenging obstacle for force control, was solved by my novel method of combining the reaction torque observer and extended Kalman filter. I realized how much the real-implementation performance depends on control and optimization algorithms. Additionally, I am developing constrained optimal algorithms for robust estimation to cover uncertain impacts from ground bumps. 

**Note** I cannot post all parts of the project because it belongs to the company's asset. So, I sum up my work briefly.

# Figure about our project

<p align="center">
  <img src="/assets/wheelchair/wheelchair.jpg">
</p>

These two figures are our prototypes. The left thing is the first prototype which was renovated from the original manual wheelchair.
The right thing is the second prototype which focused on the driving performance such as suspension, wheel type and motor power.

<p align="center">
  <img src="/assets/wheelchair/control2.jpg">
</p>

This is a fundamental power-assisted control diagram. It includes the basic system of this wheelchair platform. After this control diagram, I developed the constrained optimal control algorithms with Disturbance Observer and Dynamic equation based Kalman filtering Observer. 

<p align="center">
  <img src="/assets/wheelchair/field_test.jpg">
</p>

This is the our contextual field test design. We had experiments with this sequence and physical model.
