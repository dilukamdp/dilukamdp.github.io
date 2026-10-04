---
title: "Decentralized Multi-Robot Pursuit-Evasion"
excerpt: "A decentralized reinforcement learning framework for cooperative pursuit of evasive targets using multiple autonomous robots, funded by Central Queensland University (CQU)."
collection: portfolio
type: project
pillars:
  - decision-making
---

Development of a decentralized multi-robot pursuit-evasion framework using deep reinforcement
learning for cooperative target interception under limited communication and sensing.

The framework utilizes continuous-control reinforcement learning algorithms such as
Soft Actor-Critic (SAC) and Twin Delayed Deep Deterministic Policy Gradient (TD3) to support
cooperative multi-robot decision making. The system is designed to scale to multiple robots
operating in dynamic environments where limited sensing, communication constraints, and
collision avoidance must be considered.

The project includes a high-fidelity simulation environment featuring curriculum learning,
domain randomization, realistic robot dynamics, moving evasive targets, and cooperative
multi-agent behaviours. The developed framework forms the foundation for future deployment
on real robotic platforms including autonomous ground vehicles and aerial robots.

This research is supported by the Central Queensland University Internal Research Grant
Scheme and forms part of an ongoing research program on decentralized autonomous systems,
multi-robot coordination, and intelligent decision-making.

## Project Demonstration

The video below demonstrates the multi-robot pursuit-evasion framework across progressively
larger scenarios, including 3 pursuers/1 evader, 6 pursuers/2 evaders, and 9 pursuers/3 evaders.
It compares the learned TD3-based policy with a Pure Pursuit baseline, highlighting how the
learned approach supports coordinated interception as the number of agents increases.

<iframe width="100%" height="480"
src="https://www.youtube.com/embed/cNTVuF9-6zU"
title="TD3 vs Pure Pursuit for Multi-Agent Pursuit-Evasion"
frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
allowfullscreen></iframe>
