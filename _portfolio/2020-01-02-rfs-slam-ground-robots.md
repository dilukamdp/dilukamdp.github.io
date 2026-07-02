---
title: "3D RFS-SLAM on Ground Robots (Clearpath Husky)"
excerpt: "RFS-based 3D SLAM and Collaborative SLAM using Clearpath Husky robots fitted with ZED Stereo Camera and Velodyne VLP-16 LiDAR at NTU."
collection: portfolio
type: project
---

Random Finite Set (RFS) based 3D Simultaneous Localization and Mapping (SLAM) and 
Collaborative SLAM (CSLAM) performed by Clearpath Husky robots at Nanyang Technological 
University (NTU).

Two sensor configurations were tested:
- **ZED Stereo Camera**: trajectory estimated using particle filter; map estimated using 
  Gaussian Mixture PHD filter; 3D point cloud visualized in ROS rviz.
- **Velodyne VLP-16 LiDAR**: point cloud pre-processed to remove ground plane; bounding 
  box centroids used as 3D features with 2D SLAM; odometry fused from wheel encoders 
  and gyroscope. CSLAM was implemented as a centralized offline solution in ROS.

## Demo Videos

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZV9A8iAtelU" 
frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Qrg5CQAu61U" 
frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/sV_CzSDg5EU" 
frameborder="0" allowfullscreen></iframe>
