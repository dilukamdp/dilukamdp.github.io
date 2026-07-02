---
title: "3D RFS-SLAM with Handheld Stereo Camera"
excerpt: "Real-time Random Finite Set based 3D SLAM using a handheld ZED Stereo Camera at Nanyang Technological University (NTU)."
collection: portfolio
type: project
---

Real-time Random Finite Set (RFS) based 3D Simultaneous Localization and Mapping (SLAM) 
using a handheld ZED Stereo Camera at Nanyang Technological University (NTU).

The robot trajectory (shown in white) is estimated using a particle filter, and the map 
(shown in red) is estimated using a Gaussian Mixture implementation of a PHD filter. 
Inputs to the algorithm are triangulated 3D feature positions (shown in yellow) and 3D 
Visual Odometry. The 3D map is visualized using the ROS OctoMap package.

## Demo Videos

<iframe width="560" height="315" src="https://www.youtube.com/embed/oYNl-0hB4HI" 
frameborder="0" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Gm9HyggRZy4" 
frameborder="0" allowfullscreen></iframe>
