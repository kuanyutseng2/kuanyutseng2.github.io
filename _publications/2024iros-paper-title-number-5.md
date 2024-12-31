---
title: "Adaptive Trajectory Database Learning for Nonlinear Control with Hybrid Gradient Optimization"
collection: publications
permalink: /publication/2024iros
excerpt: "<br/><img src='/images/2024iros_small.png'>"
date: 2024-10-14
venue: '2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) (To appear)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://doi.org/10.1109/IROS58592.2024.10801717'
authors: <b>Kuan-Yu Tseng</b>, Mengchao Zhang, Kris Hauser, Geir E Dullerud

---
\[[Paper](https://doi.org/10.1109/IROS58592.2024.10801717)\]

## Abstract

This paper presents a novel experience-based technique, called EHGO, for sample-efficient adaptive control of nonlinear systems in the presence of dynamical modeling errors. The starting point for EHGO is a database seeded with many trajectories optimized under a reference estimate of real system dynamics. When executed on the real system, these trajectories will be suboptimal due to errors in the reference dynamics. The approach then leverages a hybrid gradient optimization technique, GRILC, which observes executed trajectories and computes gradients from the reference model to refine the control policy without requiring an explicit model of the real system. In past work, GRILC was applied in a restrictive setting in which a robot executes multiple rollouts from identical start states. In this paper, we show how to leverage a database to enable GRILC to operate across a wide envelope of possible start states in different iterations. The database is used to balance between start state proximity and recentness-ofexperience via a learned distance metric to generate good initial guesses. Experiments on three dynamical systems (pendulum, car, drone) show that the proposed approach adapts quickly to online experience even when the reference model has significant errors. In these examples EHGO generates near-optimal solutions within hundreds of epochs of real execution, which can be orders of magnitude more sample efficient than reinforcement learning techniques.

![2024iros](/images/2024iros_small.png)

## Citation: 
@INPROCEEDINGS{tseng2024adaptive,
  author={Tseng, Kuan-Yu and Zhang, Mengchao and Hauser, Kris and Dullerud, Geir E.},
  booktitle={2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)}, 
  title={Adaptive Trajectory Database Learning for Nonlinear Control with Hybrid Gradient Optimization}, 
  year={2024},
  volume={},
  number={},
  pages={11969-11976},
  keywords={Adaptation models;Databases;System dynamics;Computational modeling;Reinforcement learning;Trajectory;Nonlinear dynamical systems;Automobiles;Optimization;Quadrotors},
  doi={10.1109/IROS58592.2024.10801717}}