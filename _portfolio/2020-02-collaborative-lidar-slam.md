---
title: "Collaborative LiDAR SLAM"
excerpt: "A probabilistic collaborative LiDAR SLAM framework enabling multiple autonomous robots to jointly localise and construct a shared map using Random Finite Set theory."
collection: portfolio

type: project
identifier: collaborative-lidar-slam

pillars:
  - perception
  - estimation
  - robotic-systems

year: 2017
stage: mature
featured: true

platforms:
  - UGV
  - Multi-Robot

technologies:
  - Random Finite Sets
  - Collaborative SLAM
  - LiDAR SLAM
  - Particle Filter
  - GM-PHD
  - Velodyne VLP-16
  - ROS

video_ids:
  - sV_CzSDg5EU

locations:
  - Nanyang Technological University

collaborators:
  - Nanyang Technological University

funding:
  - ST Engineering-NTU Corporate Laboratory

related_projects:
  - rfs-visual-slam
  - cslammot
  - distributed-perception

image: collaborative-lidar-slam.jpg
---

Autonomous robot teams operating in large-scale environments require the ability to collaboratively estimate their locations while constructing a consistent representation of the surrounding environment. This project developed a **Random Finite Set (RFS) based Collaborative LiDAR SLAM framework** that enables multiple autonomous ground robots to cooperatively perform simultaneous localisation and mapping.

The framework extends probabilistic SLAM from a single robot to a collaborative multi-robot setting by allowing robots to contribute observations towards a common environmental map while maintaining consistent estimates of their individual trajectories. The work demonstrates how Bayesian estimation techniques can be used to scale localisation and mapping beyond individual robotic platforms.

---

## Research Motivation

Single-robot SLAM algorithms are limited by sensing range, computational resources, and the amount of environment that can be explored within a given time. Collaborative SLAM enables multiple autonomous robots to simultaneously explore an environment, share observations, and jointly construct a consistent global map.

This project investigated probabilistic methods for collaborative mapping using Random Finite Set theory, providing a principled Bayesian framework for handling uncertainty in both robot localisation and environmental mapping.

---

## Research Contributions

- Developed a collaborative LiDAR SLAM framework based on Random Finite Set theory.
- Extended probabilistic SLAM from single-robot to multi-robot operation.
- Integrated particle-filter-based robot localisation with GM-PHD map estimation.
- Demonstrated collaborative localisation and mapping using multiple autonomous ground robots.
- Validated the framework using real robotic platforms operating in outdoor environments.

---

## Experimental Platforms

The proposed framework was demonstrated using multiple **Clearpath Husky** unmanned ground vehicles equipped with:

- Velodyne VLP-16 LiDAR
- Wheel encoders
- Gyroscope
- Onboard computer
- ROS software framework

LiDAR point clouds were pre-processed to remove the ground plane before extracting stable environmental features for probabilistic mapping.

---

## Technologies

- Random Finite Set Theory
- Collaborative SLAM
- LiDAR-based Mapping
- Bayesian Estimation
- Particle Filtering
- GM-PHD Filter
- ROS
- Velodyne VLP-16

---

## Demonstration Video

<iframe width="560" height="315"
src="https://www.youtube.com/embed/sV_CzSDg5EU"
frameborder="0"
allowfullscreen>
</iframe>

---

## Related Research Pillars

- [Robot Perception & Localisation](/portfolio/02-robot-perception-and-localization/)
- [Probabilistic State Estimation](/portfolio/03-probabilistic-state-estimation/)
- [Autonomous Robotic Systems](/portfolio/04-autonomous-robotic-systems/)

---

## Publications

*Add related journal and conference publications.*

---

## Future Directions

This research established the foundations for collaborative probabilistic perception using multiple autonomous robots. Current research extends these concepts towards decentralised perception, distributed information fusion, and collaborative autonomous decision-making under intermittent communication.
