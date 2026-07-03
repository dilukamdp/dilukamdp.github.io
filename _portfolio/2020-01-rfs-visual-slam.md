---
title: "Random Finite Set Based 3D Visual SLAM"
excerpt: "A probabilistic 3D Visual SLAM framework based on Random Finite Set theory for robust localisation and mapping in GPS-denied environments."
collection: portfolio

type: project
identifier: rfs-visual-slam
pillars:
  - perception
  - estimation
  - robotic-systems

year: 2020
stage: mature
featured: true

platforms:
  - Handheld stereo camera
  - UAV
  - Ground robot

technologies:
  - Random Finite Sets
  - 3D Visual SLAM
  - Stereo Vision
  - Particle Filter
  - GM-PHD Filter
  - ROS
  - OctoMap

video_ids:
  - oYNl-0hB4HI
  - Gm9HyggRZy4
  - vCci49uM8Uc
  - OWYgYwvoNMs
  - ZV9A8iAtelU
  - Qrg5CQAu61U

locations:
  - Nanyang Technological University
  - Indoor laboratory
  - Outdoor campus

collaborators:
  - Nanyang Technological University

funding:
  - ST Engineering-NTU Corporate Laboratory

related_projects:
  - collaborative-lidar-slam
  - cslammot
  - distributed-perception
---

Autonomous robots operating in GPS-denied environments require reliable localisation and mapping capabilities to navigate safely and build useful representations of their surroundings. This project developed a Random Finite Set (RFS) based 3D Visual SLAM framework that combines probabilistic state estimation with stereo vision to jointly estimate robot trajectory and construct three-dimensional maps.

The framework uses a particle filter to estimate the robot trajectory and a Gaussian Mixture Probability Hypothesis Density (GM-PHD) filter to estimate the map. Stereo visual odometry and triangulated 3D feature positions are used as inputs, while the resulting 3D map is visualised in ROS using OctoMap and RViz.

---

## Research Motivation

SLAM in real-world environments is challenging because robots must estimate their own motion while simultaneously building a map from noisy, uncertain, and sometimes incomplete sensor observations. Random Finite Set theory provides a principled Bayesian framework for representing uncertainty in the number and state of environmental features, making it well suited to probabilistic SLAM and mapping problems.

---

## Research Contributions

- Developed an RFS-based framework for 3D Visual SLAM.
- Integrated particle-filter-based robot trajectory estimation with GM-PHD map estimation.
- Used stereo vision and visual odometry for localisation and 3D mapping.
- Demonstrated the approach across handheld, aerial, and ground robotic platforms.
- Implemented and visualised the system using ROS, RViz, and OctoMap.

---

## Experimental Platforms

This work was demonstrated using several robotic and sensing platforms:

- Handheld ZED stereo camera connected to a laptop.
- ZED stereo camera mounted on an AscTec Pelican UAV.
- Clearpath Husky ground robot fitted with a ZED stereo camera.

---

## Demonstration Videos

### Handheld ZED Stereo Camera Demonstration

<iframe width="560" height="315" src="https://www.youtube.com/embed/oYNl-0hB4HI" frameborder="0" allowfullscreen></iframe>

### Additional Handheld Demonstration

<iframe width="560" height="315" src="https://www.youtube.com/embed/Gm9HyggRZy4" frameborder="0" allowfullscreen></iframe>

### UAV Indoor Laboratory Demonstration

<iframe width="560" height="315" src="https://www.youtube.com/embed/vCci49uM8Uc" frameborder="0" allowfullscreen></iframe>

### UAV Outdoor Campus Demonstration

<iframe width="560" height="315" src="https://www.youtube.com/embed/OWYgYwvoNMs" frameborder="0" allowfullscreen></iframe>

### Clearpath Husky Ground Robot Demonstration

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZV9A8iAtelU" frameborder="0" allowfullscreen></iframe>

### Additional Husky Demonstration

<iframe width="560" height="315" src="https://www.youtube.com/embed/Qrg5CQAu61U" frameborder="0" allowfullscreen></iframe>

---

## Related Research Pillars

- [Robot Perception & Localisation](/portfolio/02-robot-perception-and-localization/)
- [Probabilistic State Estimation](/portfolio/03-probabilistic-state-estimation/)
- [Autonomous Robotic Systems](/portfolio/04-autonomous-robotic-systems/)

---

## Publications

- *(Add related journal/conference publications here.)*

---

## Future Directions

This work forms part of a broader research direction in probabilistic perception and localisation for autonomous robotic systems. Future extensions include tighter integration with multi-robot perception, semantic mapping, robust field deployment, and decision-making under uncertainty.
