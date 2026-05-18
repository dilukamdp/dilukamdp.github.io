---
title: "Collaborative SLAM with Moving Object Tracking"
excerpt: "RFS-based Collaborative Localization and Mapping with Moving Object Tracking (CSLAMMOT) using two mobile robots, and marine dataset collection at Pandan Reservoir, Singapore."
collection: portfolio
---

## Multi-Robot CSLAM with Moving Object Tracking

Random Finite Set (RFS) based Collaborative Localization and Mapping with Moving Object 
Tracking (CSLAMMOT) using two Videre Erratic mobile robot platforms fitted with 2D SICK 
LiDAR sensors and wheel encoders at Nanyang Technological University (NTU).

Data was collected and processed offline through a MATLAB implementation. Static pillars 
served as map features while moving objects (people carrying buckets) were tracked 
simultaneously. The algorithm distinguishes static and dynamic features purely from 
target behaviour — no feature type information is used. Robot trajectories are estimated 
using a particle filter; the map uses a Gaussian Mixture PHD filter.

<iframe width="560" height="315" src="https://www.youtube.com/embed/a5GTA5m1qXU" 
frameborder="0" allowfullscreen></iframe>

## Marine Dataset Collection — Pandan Reservoir, Singapore

Dataset collection for verifying SLAM algorithms at Pandan Reservoir, Singapore. 
Kayaks were fitted with computers, Doppler Velocity Logs (DVL), and 2D LiDAR sensors. 
Buoys anchored with metal rods served as static landmarks in the water.

<iframe width="560" height="315" src="https://www.youtube.com/embed/-BXgucH1zHs" 
frameborder="0" allowfullscreen></iframe>
