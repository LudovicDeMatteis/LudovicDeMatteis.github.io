---
title: "Optimal Control of Closed Loop Walkers"
collection: publications
permalink: /publication/OptimalControlClosedLoopWalkers
excerpt: 'In this paper, we present a method for controlling robots with closed kinematic loops (such as parallel actuation). We propose to use a serial model - for instance based on an underlying main chain - and to use additionnal constraints to account for closures. We demonstrate the advatages of this method by comparing it to a classical simplified model of the robot on several motions (walk, jump, sidewalk, and climbing stairs).'
date: 2025-05-19
venue: 'IEEE-IROS 2025'
citation: 'Ludovic De Matteis, Virgile Batto, Justin Carpentier & Nicoals Mansard. (2025, October). Optimal Control of Walkers with Parallel Actuation. In 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). Hangzhou, China.'
hal: 'https://hal.science/hal-04716938v3'
paperlink: 'https://ludovicdematteis.github.io/files/papers/Optimal_Control_of_Closed_Loop_walkers.pdf'
githublink: 'https://github.com/LudovicDeMatteis/ClosedLoopMotion'
arxiv: 'https://arxiv.org/abs/2504.00642'
---

<iframe title="Optimal Control of Walker with Parallel Actuation" width="560" height="315" src="https://peertube.laas.fr/videos/embed/4rN4nm6dmkF7uyWBMkRKCW" style="border: 0px;" allow="fullscreen" sandbox="allow-same-origin allow-scripts allow-popups allow-forms"></iframe>

# Abstract
Legged robots with complex kinematic architectures, such as parallel linkages, offer significant advancements in mobility and efficiency. However, generating versatile movements for these robots requires accurate dynamic modeling that reflects their specific mechanical structures. Previous approaches often relied on simplified models, resulting in sub-optimal control, particularly in tasks requiring the full actuator range. Here, we present a method that fully models the dynamics of legged robots with parallel linkages, formulating their motion generation as an optimal control problem with specific contact dynamics. We introduce 6D kinematic closure constraints and derive their analytical derivatives, enabling the solver to exploit nonlinear transmission and the consequent variable actuator reduction. This approach reduces peak motor torques and expands the usable range of actuator motion and force. We empirically demonstrate that fully modeling the kinematics leads to superior performance, especially in demanding tasks such as fast walking and stair climbing. Beyond serialparallel designs, our method also addresses motion generation for fully-parallel walkers.

