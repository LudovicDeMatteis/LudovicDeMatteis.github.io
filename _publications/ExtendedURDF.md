---
# Site info
collection: publications
permalink: /publication/ExtendedURDF
# Paper info
title: "Extended URDF: Accounting for parallel mechanism in robot description"
authors: "Ludovic De Matteis, Virgile Batto and Nicolas Mansard"
excerpt: 'In this paper, we introduce an extension to the widely used Unified Robot Description Format (URDF) to support closed-loop kinematic structures. Our approach relies on augmenting URDF with minimal additional information to allow more efficient modeling of complex robotic systems while maintaining compatibility with existing design and simulation frameworks. '
year: "2024"
# Conference info
conference-name: "International Conference on Robotics in Alpe-Adria-Danube Region (RAAD)"
conference-address: "Belgrade, Serbia"
conference-year: "2025"

# Links
hal: "https://laas.hal.science/hal-05018529v2"
paperlink: "https://ludovicdematteis.github.io/files/papers/Extended_URDF.pdf"
githublink: "https://github.com/Gepetto/example-parallel-robots"
bibtex: {type: "inproceedings", authors: "De Matteis, Ludovic and Batto, Virgile and Mansard, Nicolas", ref: "dematteis_extendedURDF"}
---
# Abstract
Robotic designs played an important role in recent advances by providing powerful robots with complex mechanics. Many recent systems rely on parallel actuation to provide lighter limbs and allow more complex motion. However, these emerging architectures fall outside the scope of most used description formats, leading to difficulties when designing, storing, and sharing the models of these systems. This paper introduces an extension to the widely used Unified Robot Description Format (URDF) to support closed-loop kinematic structures. Our approach relies on augmenting URDF with minimal additional information to allow more efficient modeling of complex robotic systems while maintaining compatibility with existing design and simulation frameworks. This method sets the basic requirement for a description format to handle parallel mechanisms efficiently. We demonstrate the applicability of our approach by providing an open-source collection of parallel robots, along with tools for generating and parsing this extended description format. The proposed extension simplifies robot modeling, reduces redundancy, and improves usability for advanced robotic applications.
