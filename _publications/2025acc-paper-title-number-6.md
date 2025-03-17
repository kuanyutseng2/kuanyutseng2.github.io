---
title: "Hybrid Gradient-Based Policy Optimization for Sample-Efficient Policy Learning in Autonomous Systems"
collection: publications
permalink: /publication/2025acc
excerpt: "<br/><img src='/images/2025acc_small.png'>"
date: 2025-7-8
venue: '2025 American Control Conference (ACC) (To appear)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 
authors: <b>Kuan-Yu Tseng</b>, Jeff S. Shamma, Geir E. Dullerud

--- 
\[[Paper](/files/2025_ACC_revised_cameraReady(equ).pdf)\] \
\[[Video](https://youtu.be/n45mqh19C6M)\]

## Abstract

This paper introduces HyGIPO, a novel gradient based iterative policy optimization technique designed for efficient policy learning in autonomous systems, especially in the presence of modeling errors. Performance of control algorithms for autonomous systems is often limited by mismatches between a simplified nominal model and a complex real system. To address this degradation, HyGIPO leverages a hybrid gradient optimization approach, combining gradients of dynamics from a nominal model with real-world data to optimize control policies. We apply this method to the quadcopter waypoint tracking problem, with the controller parameterized by a neural network, demonstrating its effectiveness in both simulation and hardware experiments. In simulation, HyGIPO rapidly learns the policy within a hundred iterations, showing orders of magnitude higher sample efficiency compared to reinforcement learning methods. The hardware experiments further validate the method, achieving successful tracking results in just tens of iterations.

![2025acc](/images/2025acc_small.png)

## Citation: 
