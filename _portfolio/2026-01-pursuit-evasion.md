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

The following video accompanies our paper submitted to the **Australasian Conference on Robotics and Automation (ACRA) 2026**.

[![TD3 vs Pure Pursuit for Multi-Agent Pursuit-Evasion](https://img.youtube.com/vi/cNTVuF9-6zU/hqdefault.jpg)](https://www.youtube.com/watch?v=cNTVuF9-6zU)

[Watch the video on YouTube](https://www.youtube.com/watch?v=cNTVuF9-6zU)

This video compares a parameter-sharing TD3 policy with a Pure Pursuit baseline for communication-free multi-agent pursuit-evasion.

A key feature of the proposed TD3 controller is that the learned policy jointly controls both the angular velocity and linear velocity of each pursuer. Thus, the pursuers learn not only how to steer toward and coordinate around evaders, but also how to regulate their forward speed as part of the cooperative pursuit strategy. In contrast, the Pure Pursuit baseline turns toward its assigned evader while moving at the maximum pursuer speed.

Three configurations are demonstrated at an evader speed of \(V_e = 20\), while the maximum pursuer speed is \(v_{p,\max} = 10\):

- 3 pursuers / 1 evader
- 6 pursuers / 2 evaders
- 9 pursuers / 3 evaders

For each configuration, five TD3 evaluation episodes are shown first, followed immediately by five Pure Pursuit episodes under the corresponding evaluation conditions. The same random seed is used to generate reproducible randomized evaluation sequences for comparison.

Both controllers use the same decentralized arrival-time-based target-assignment mechanism. The TD3 controller executes a shared deterministic policy using only locally available observations and independently determines both turning rate and forward speed for every pursuer, without inter-agent communication.

The policy was trained only on single-evader scenarios, making the 6P/2E and 9P/3E demonstrations examples of zero-shot generalization to multi-evader pursuit.
