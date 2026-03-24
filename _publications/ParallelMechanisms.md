---
title: "Control of humanoid robots with parallel mechanisms using kinematic actuation models"
collection: publications
permalink: /publication/ParallelMechanisms
excerpt: 'In this paper, we present a method for controlling robots with closed kinematic loops (such as parallel actuation). We propose demonstrate a method to take efficiently into account the closed kinematics by using analytical formulations of different mechanisms.'
venue: 'IEEE-ICRA'
citation: 'Victor Lutz, Ludovic de Matteïs, Virgile Batto, Nicolas Mansard. Control of humanoid robots with parallel mechanisms using kinematic actuation models. 2025.'
arxiv: "https://arxiv.org/abs/2503.22459"
hal: "https://laas.hal.science/hal-04984842v1"
paperlink: "https://ludovicdematteis.github.io/files/papers/Differential_Actuation_Models.pdf"
---
<div style="display: flex; justify-content: center; margin: 20px 0;">
    <iframe title="Control of Humanoid Robots with Parallel Mechanisms using Differential Actuation Models" width="560" height="315" src="https://peertube.laas.fr/videos/embed/mqFnxkVPswa1CTP6hS5Z7S" style="border: 0px;" allow="fullscreen" sandbox="allow-same-origin allow-scripts allow-popups allow-forms"></iframe>
</div>

# Abstract
Inspired by the mechanical design of Cassie, several recently released humanoid robots are using actuator configuration in which the motor is displaced from the joint location to optimize the leg inertia. This in turn induces a non linearity in the reduction ratio of the transmission which is often neglected when computing the robot motion (e.g. by trajectory optimization or reinforcement learning) and only accounted for at control time. This paper proposes an analytical method to efficiently handle this non-linearity. Using this actuation model, we demonstrate that we can leverage the dynamic abilities of the non-linear transmission while only modeling the inertia of the main serial chain of the leg, without approximating the motor capabilities nor the joint range. Based on analytical inverse kinematics, our method does not need any numerical routines dedicated to the closed-kinematics actuation, hence leading to very efficient computations. Our study focuses on two mechanisms widely used in recent humanoid robots; the four bar knee linkage as well as a parallel 2 DoF ankle mechanism. We integrate these models inside optimization based (DDP) and learning (PPO) control approaches. A comparison of our model against a simplified model that completely neglects closed chains is then shown in simulation.

