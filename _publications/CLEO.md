---
title: "CLEO: Closed-Loop kinematics Evolutionary Optimization of bipedal structures"
collection: publications
permalink: /publication/CLEO
excerpt: 'In this paper, we propose a general approach to assist the design of serial-parallel humanoid legs using an evolutionary optimization strategy. The optimization problem incorporates design constraints and locomotion-task requirements as objective functions. It uses parallelized trajectory evaluation for efficient exploration of the design space.'
date: 2024-10-01
venue: ''
paperurl: 'https://insa-toulouse.hal.science/hal-04717159/'
citation: 'Virgile Batto, Ludovic de Matteis, Thomas Flayols, Margot Vulliez, Nicolas Mansard. CLEO: Closed-Loop kinematics Evolutionary Optimization of bipedal structures. 2024.'
---
# Abstract
Legged robots with complex kinematic architectures, such as parallel linkages, offer significant advancements in mobility and efficiency. However, generating versatile movements for these robots requires accurate dynamic modeling that reflects their specific mechanical structures. Previous approaches often relied on simplified models, resulting in sub-optimal control, particularly in tasks requiring the full actuator range. Here, we present a method that fully models the dynamics of legged robots with parallel linkages, formulating their motion generation as an optimal control problem with specific contact dynamics. We introduce 6D kinematic closure constraints and derive their analytical derivatives, enabling the solver to exploit nonlinear transmission and the consequent variable actuator reduction. This approach reduces peak motor torques and expands the usable range of actuator motion and force. We empirically demonstrate that fully modeling the kinematics leads to superior performance, especially in demanding tasks such as fast walking and stair climbing. Beyond serialparallel designs, our method also addresses motion generation for fully-parallel walkers.

[Download paper here](https://insa-toulouse.hal.science/hal-04717159/)

Recommended citation: Virgile Batto, Ludovic de Matteis, Thomas Flayols, Margot Vulliez, Nicolas Mansard. CLEO: Closed-Loop kinematics Evolutionary Optimization of bipedal structures. 2024.
