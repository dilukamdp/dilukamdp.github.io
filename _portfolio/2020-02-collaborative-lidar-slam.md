---
title: "Collaborative LiDAR SLAM"
excerpt: "A collaborative multi-robot LiDAR SLAM framework based on Random Finite Set theory for cooperative localisation and mapping."
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
  - Clearpath Husky UGV

technologies:
  - Velodyne VLP-16
  - ROS
  - Particle Filter
  - Random Finite Sets
  - GM-PHD Filter
---

Autonomous multi-robot systems require consistent localisation and mapping while operating cooperatively in large and uncertain environments. This project developed a collaborative LiDAR SLAM framework that enables multiple ground robots to jointly estimate their trajectories while constructing a shared map.

The system was demonstrated using multiple Clearpath Husky robots equipped with Velodyne VLP-16 LiDAR sensors. Wheel encoder and gyroscope measurements were fused to estimate odometry, while LiDAR point clouds were processed to extract stable environmental features for probabilistic mapping.

---

## Research Motivation

Collaborative mapping enables teams of autonomous robots to explore larger environments more efficiently than individual robots. This project investigated probabilistic methods for sharing mapping information while maintaining consistent state estimates.

---

## Research Contributions

- Developed collaborative multi-robot LiDAR SLAM.
- Applied Random Finite Set theory to collaborative mapping.
- Validated using multiple Clearpath Husky robots.
- Demonstrated cooperative localisation and shared mapping.

---

## Demonstration Video

<iframe width="560" height="315"
src="https://www.youtube.com/embed/sV_CzSDg5EU"
frameborder="0" allowfullscreen></iframe>

---

## Publications

*(Add journal and conference papers.)*

---

## Future Directions

Current research extends these concepts towards decentralised perception and collaborative autonomy under intermittent communication.
