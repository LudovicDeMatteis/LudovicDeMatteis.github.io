---
# Site info
collection: publications
permalink: /publication/CollisionAvoidanceVelocityDamper
# Paper info
title: "Collision Avoidance in Model Predictive Control using Velocity Damper"
authors: "Arthur Haffemayer, Armand Jordana, Ludovic De Matteis, Krzysztof Wojciechowski, Ludovic Righetti, Florent Lamiraux, Nicolas Mansard"
excerpt: 'In this paper, we propose a method to include collision avoidance in the control of a manipulator robot based on a velocity damper model. This allows to account for approach velocity and permits collision avoidance for a wider spectrum of applications than classical avoidance methods. We implemented our method on a Panda robot to perform several comparisons. In this paper, I mainly contributed to writing the derivatives of the collision avoidance constraint with respect to the robot state and controls in order to use it in a DDP setting.'
year: "2024"
# Conference info
conference-name: "IEEE International Conference on Robotics and Automation (ICRA)"
conference-year: "2025"
conference-address: "Atlanta, USA"

# Links
githublink: "https://github.com/agimus-project/colmpc"
hal: 'https://laas.hal.science/hal-04707324v3'
paperlink: "https://ludovicdematteis.github.io/files/papers/ColMPC.pdf"
bibtex: {type: "inproceedings", authors: "Haffemayer, Arthur and Jordana, Armand and De Matteis, Ludovic and Wojciechowski, Krzysztof and Righetti, Ludovic and Lamiraux, Florent and Mansard, Nicolas", ref: "haffemayer_colisionavoidance"}
---
<div style="display: flex; justify-content: center; margin: 20px 0;">
    <iframe title="final video icra 2025" width="560" height="315" src="https://peertube.laas.fr/videos/embed/cDMChsB6WZoGjpqBVgFyko" style="border: 0px;" allow="fullscreen" sandbox="allow-same-origin allow-scripts allow-popups allow-forms"></iframe>
</div>

# Abstract
We propose an advanced method for controlling the motion of a manipulator robot with strict collision avoidance in dynamic environments, leveraging a velocity damper constraint. Unlike conventional distance-based constraints, which tend to saturate near obstacles to reach optimality, the velocity damper constraint considers both distance and relative velocity, ensuring a safer separation. This constraint is incorporated into a model predictive control framework and enforced as a hard constraint through analytical derivatives supplied to the numerical solver. The approach has been fully implemented on a Franka Emika Panda robot and validated through experimental trials, demonstrating effective collision avoidance during dynamic tasks and robustness to unmodeled disturbances. An efficient open-source implementation along examples are provided
