---
title: DDR-Planner
subtitle:  Universal Trajectory Optimization Framework for Differential Drive Robot Class
date: 2025-05-01
image:
  focal_point: 'top'
summary: Universal Trajectory Optimization Framework for Differential Drive Robot Class
tags: [AutoNav]

---

<!--more-->

Differential drive robots are widely used in vari-
ous scenarios thanks to their straightforward principle, from
household service robots to disaster response field robots. The
nonholonomic dynamics and possible lateral slip of these robots
lead to difficulty in getting feasible and high-quality trajectories.
Although there are several types of driving mechanisms for real-
world applications, they all share a similar driving principle,
which involves controlling the relative motion of independently
actuated tracks or wheels to achieve both linear and angular
movement. Therefore, a comprehensive trajectory optimization
to compute trajectories efficiently for various kinds of differential
drive robots is highly desirable. In this paper, we propose
a universal trajectory optimization framework, enabling the
generation of high-quality trajectories within a restricted com-
putational timeframe for these robots. We introduce a novel
trajectory representation based on polynomial parameterization
of motion states or their integrals, such as angular and linear
velocities, which inherently matches the robots’ motion to the con-
trol principle. The trajectory optimization problem is formulated
to minimize computation complexity while prioritizing safety and
operational efficiency. We then build a full-stack autonomous
planning and control system to demonstrate its feasibility and
robustness. We conduct extensive simulations and real-world
testing in crowded environments with three kinds of differential
drive robots to validate the effectiveness of our approach.

**Related Publications:**

- [Universal Trajectory Optimization Framework for Differential Drive Robot Class](https://fast-fire.github.io/publication/journal-article/zmk-tase/)
