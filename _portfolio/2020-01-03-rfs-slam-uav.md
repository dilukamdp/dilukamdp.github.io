---
title: "3D RFS-SLAM on UAV (Asctec Pelican)"
excerpt: "Real-time RFS-based 3D SLAM using a ZED Stereo Camera mounted on an Asctec Pelican UAV at Nanyang Technological University (NTU)."
collection: portfolio
type: project
---

Real-time Random Finite Set (RFS) based 3D Simultaneous Localization and Mapping (SLAM) 
using a ZED Stereo Camera mounted on an Asctec Pelican UAV at Nanyang Technological 
University (NTU).

The robot trajectory (shown in white) is estimated using a particle filter, and the map 
(shown in red) is estimated using a Gaussian Mixture implementation of a PHD filter. 
Inputs to the SLAM algorithm are triangulated 3D feature positions (shown in yellow) and 
3D Visual Odometry. The 3D map is built and visualized using the ROS OctoMap package in rviz.

## Demo Videos

**Indoor Lab Test (UAV hand-carried)**

<iframe width="560" height="315" src="https://www.youtube.com/embed/vCci49uM8Uc" 
frameborder="0" allowfullscreen></iframe>

**Outdoor Test near Hall 7, NTU**

<iframe width="560" height="315" src="https://www.youtube.com/embed/OWYgYwvoNMs" 
frameborder="0" allowfullscreen></iframe>
