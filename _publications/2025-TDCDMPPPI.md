---
# Site info
collection: publications
permalink: /publication/TDCDMPPI
# Paper info
title: "TD-CD-MPPI: Temporal-Difference Constraint-Discounted Model Predictive Path Integral Control"
authors: "Pietro Noah Crestaz, Ludovic De Matteis, Elliot Chane-Sane, Nicolas Mansard and Andrea Del Prete"
excerpt: 'In this paper, we present a extension of the Model Predictive Path Integral (MPPI) method to first accounts for constraints in the optimization problem through a discount modulation strategy and second allow longer horizon while avoiding the curse of dimensionality by temporal-difference learning. The method is applied to locomotion on a quadrupedal robot.'
year: "2025"

# Conference info
journal-name: 'IEEE Robotics and Automation Letters (RA-L)'
journal-year: "2026"

# Links
hal: 'https://hal.science/hal-05213269v2'
paperlink: 'https://ludovicdematteis.github.io/files/papers/TD_CD_MPPI.pdf'
weblink: "https://pietronoah.github.io/td-cd-mppi/"
bibtex: {type: "article", authors: "Crestaz, Pietro Noah and De Matteis, Ludovic and Chane-Sane Elliot and Mansard Nicolas and Del Prete, Andrea", ref: "crestaz_tdcdmppi_2026"}
---
# Abstract
Path Integral methods have demonstrated remarkable capabilities for solving non-linear stochastic optimal control problems through sampling-based optimization. However, their computational complexity grows linearly with the prediction horizon, limiting long-term reasoning, while constraints are merely enforced through handcrafted penalties. In this work, we propose a unified and efficient framework for enabling long-horizon reasoning and constraint enforcement within Model Predictive Path Integral (MPPI) control. 
First, we introduce a practical method to incorporate a terminal value function, learned offline via temporal-difference learning, to approximate the long-term cost-to-go. This allows for significantly shorter rollouts while enabling infinite-horizon reasoning, thereby improving computational efficiency and motion performance. 
Second, we propose a discount modulation strategy that adjusts the return of sampled trajectories based on constraint violations. This provides a more interpretable and effective mechanism for enforcing constraints compared to traditional cost shaping. Our formulation retains the flexibility and sampling efficiency of MPPI while supporting structured integration of long-term objectives and constraint handling. 
We validate our approach on both simulated and real-world robotic locomotion tasks, demonstrating improved performance, constraint-awareness, and generalization under reduced computational budgets.

