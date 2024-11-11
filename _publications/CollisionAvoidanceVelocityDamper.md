---
title: "Collision Avoidance in Model Predictive Control using Velocity Damper"
collection: publications
permalink: /publication/CollisionAvoidanceVelocityDamper
excerpt: 'In this paper, we propose a method to include collision avoidance in the control of a manipulator robot based on a velocity damper model. This allows to account for approach velocity and permits collision avoidance for a wider spectrum of applications than classical avoidance methods. We implemented our method on a Panda robot to perform several comparisons. In this paper, I mainly contributed to writing the derivatives of the collision avoidance constraint with respect to the robot state and controls in order to use it in a DDP setting.'
date: 2025-05-19
venue: 'IEEE-ICRA - Submitted, in review'
paperurl: 'https://gepettoweb.laas.fr/articles/haffemayer2025.html'
citation: 'Arthur Haffemayer, Armand Jordana, Ludovic de Matteis, Krzysztof Wojciechowski, Florent Lamiraux, et al.. Collision Avoidance in Model Predictive Control using Velocity Damper. 2024.'
---
# Abstract
We propose an advanced method for controlling the motion of a manipulator robot with strict collision avoidance in dynamic environments, leveraging a velocity damper constraint. Unlike conventional distance-based constraints, which tend to saturate near obstacles to reach optimality, the velocity damper constraint considers both distance and relative velocity, ensuring a safer separation. This constraint is incorporated into a model predictive control framework and enforced as a hard constraint through analytical derivatives supplied to the numerical solver. The approach has been fully implemented on a Franka Emika Panda robot and validated through experimental trials, demonstrating effective collision avoidance during dynamic tasks and robustness to unmodeled disturbances. An efficient open-source implementation along examples are provided

[Download paper here](http://academicpages.github.io/files/paper2.pdf)

Recommended citation: Arthur Haffemayer, Armand Jordana, Ludovic de Matteis, Krzysztof Wojciechowski, Florent Lamiraux, et al.. Collision Avoidance in Model Predictive Control using Velocity Damper. 2024.
