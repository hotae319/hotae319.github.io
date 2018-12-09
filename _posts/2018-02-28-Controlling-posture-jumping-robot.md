---
layout: post
title: "Controlling Posture of Jumping Articulated Robot for Stable Landing"
featured-img: simulation_motion
---

# What I did

***Skill : Matlab, Simulink, C ***
***Keywords : Feedback linerization, Gain optimization with Greedy Algorithm, Passive decomposition, Robust Passivity-based control ***

From March 2017 to December 2017, I researched about jumping robot's control at INROL(Interactive & Networed RObotics Lab). While I was working on this project, I focused on control for nonholonomic systems, under-actuated systems, and hybrid system. 

My first research objective was to design a control framework for a jumping robot’s stable landing to keep going. To tackle this under-actuated nonlinear system, I implemented partial feedback linearization with precise modeling and time-varying feedback control to utilize angular momentum conservation. Moreover, by considering the practical constraints of jumping, such as joint limits and short flight duration, I suggested optimal control algorithms via the gradient descent method. 

Finally, my findings proposed a stable posture control frame that takes into account features of jumping such as the limit of joint angle range or the short duration of a flight.

# Sum up Slides

<p align="center">
<img src="/assets/jumping/poster1.jpg"  alt="poster1" width="400" height="280">  <img src="/assets/jumping/poster2.jpg" width="400" height="280">


<img src="/assets/jumping/poster3.jpg"  alt="poster3" width="800" height="250"> 

<img src="/assets/jumping/poster456.jpg" width="800" height="500">
</p>

With this topic, I published a conference paper for the 2018 IEEE Conference on Ubiquitous Robots (UR) and presented it as a spotlight talk at the conference. After this work, I continued further to study passive configuration decomposition and passivity based stabilization control for nonholonomic systems. 

<p align="center">
<img src="/assets/jumping/ur.jpg" width="800" height="350"> 
</p>


After this work, I continued to study a decomposition method and robust/adaptive passivity-based control further to tackle the complicated model easily and robustly. 
