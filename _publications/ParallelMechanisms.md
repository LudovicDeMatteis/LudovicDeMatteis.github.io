---
title: "Control of humanoid robots with parallel mechanisms using kinematic actuation models"
collection: publications
permalink: /publication/ParallelMechanisms
excerpt: 'In this paper, we present a method for controlling robots with closed kinematic loops (such as parallel actuation). We propose demonstrate a method to take efficiently into account the closed kinematics by using analytical formulations of different mechanisms.'
date: 2025-03-28
venue: 'IEEE-ICRA'
paperurl: 'https://arxiv.org/pdf/2503.22459'
citation: 'Victor Lutz, Ludovic de Matteïs, Virgile Batto, Nicolas Mansard. Control of humanoid robots with parallel mechanisms using kinematic actuation models. 2025.'
---
# Abstract
Inspired by the mechanical design of Cassie, several recently released humanoid robots are using actuator configuration in which the motor is displaced from the joint location to optimize the leg inertia. This in turn induces a non linearity in the reduction ratio of the transmission which is often neglected when computing the robot motion (e.g. by trajectory optimization or reinforcement learning) and only accounted for at control time. This paper proposes an analytical method to efficiently handle this non-linearity. Using this actuation model, we demonstrate that we can leverage the dynamic abilities of the non-linear transmission while only modeling the inertia of the main serial chain of the leg, without approximating the motor capabilities nor the joint range. Based on analytical inverse kinematics, our method does not need any numerical routines dedicated to the closed-kinematics actuation, hence leading to very efficient computations. Our study focuses on two mechanisms widely used in recent humanoid robots; the four bar knee linkage as well as a parallel 2 DoF ankle mechanism. We integrate these models inside optimization based (DDP) and learning (PPO) control approaches. A comparison of our model against a simplified model that completely neglects closed chains is then shown in simulation.

[Download paper here](https://arxiv.org/pdf/2503.22459)

Recommended citation: Victor Lutz, Ludovic De Matteis, Virgile Batto & Nicolas Mansard. Control of Humanoid Robots with Parallel Mechanisms using Differential Actuation Models. In 2026 IEEE International Conference on Robotics and Automation (ICRA). Vienna, Austria.
