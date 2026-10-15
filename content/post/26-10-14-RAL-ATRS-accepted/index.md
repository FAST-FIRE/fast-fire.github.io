---
title: "Congratulations to Jiajun Yu: RA-L 2026 paper accepted"
date: 2026-10-14
image:
  focal_point: 'Smart'
tags: [PaperAccepted]
---

Congratulations to Jiajun Yu — our paper “ATRS: Adaptive Trajectory Re-splitting via a Shared Neural Policy for Parallel Optimization” has been accepted by **IEEE Robotics and Automation Letters (RA-L)**.

<!--more-->

Parallel trajectory optimization via the Alternating Direction Method of Multipliers (ADMM) has emerged as a scalable approach to long-horizon motion planning. However, existing frameworks decompose the problem into parallel subproblems based on a predefined fixed structure, so a few lagging segments in highly constrained regions can stall global convergence. Adaptively re-splitting these stagnating segments online is a natural remedy, yet deciding when, where, and how to split is beyond the reach of hand-crafted rules.

In this work, we introduce ATRS, a framework that embeds a shared deep reinforcement learning policy into the parallel ADMM loop, which consists of three key components.

(1) A Multi-Agent Shared-Policy MDP formulation, in which every trajectory segment acts as a homogeneous agent sharing one neural policy. This parameter-sharing design makes the policy size-invariant, so it handles the changing number of segments during re-splitting and generalizes to arbitrary trajectory lengths.

(2) A state representation built solely on the internal states of the numerical solver rather than the geometry of the environment, enabling zero-shot transfer to unseen environments without retraining.

(3) A Confidence-Based Election mechanism that re-splits only the most stagnating segment at each step to keep the solver stable.

Extensive simulations show that ATRS reduces the number of iterations by up to 26.0% and the computation time by up to 19.1%. Real-world quadrotor experiments in a forest further confirm its applicability to both large-scale offline global planning and real-time onboard replanning within 35 ms per cycle, with no sim-to-real degradation.

Our work advances learning-to-optimize from tuning solver parameters to learning the problem structure itself, paving the way for faster and more robust long-horizon parallel trajectory planning.
