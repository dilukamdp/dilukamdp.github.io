---
title: "Robot Perception & Localisation"
excerpt: "Advancing robotic perception through simultaneous localisation and mapping (SLAM), sensor fusion, and vision-based localisation to enable reliable operation in complex and GPS-denied environments."
collection: portfolio
type: pillar
identifier: perception
---

My research in Robot Perception & Localisation focuses on probabilistic localisation, mapping, and perception algorithms that enable autonomous robots to operate reliably in complex, GPS-denied, and dynamic environments.

## Research Areas

- Simultaneous Localisation and Mapping (SLAM)
- Collaborative SLAM
- Visual SLAM
- LiDAR SLAM
- Multi-Robot Localisation
- Sensor Fusion
- GPS-Denied Navigation
- Probabilistic Mapping

## Research Projects

{% assign perception_projects = site.portfolio | where: "type", "project" %}

{% for project in perception_projects %}
  {% if project.pillars contains "perception" %}

### {{ project.title }}

{{ project.excerpt }}

[View Project]({{ project.url }})

---

  {% endif %}
{% endfor %}
