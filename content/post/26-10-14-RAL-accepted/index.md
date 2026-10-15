---
title: "Congratulations to Xingpeng Wang: RA-L 2026 paper accepted"
date: 2026-10-14
image:
  focal_point: 'Smart'
tags: [PaperAccepted]
---

Congratulations to Xingpeng Wang on the acceptance of the RA-L 2026 paper.

<!--more-->

Global Navigation Satellite System (GNSS) navigation is widely used to provide absolute outdoor positioning in field robotics. Advances in real-time kinematic (RTK) positioning have enabled centimeter-level accuracy, facilitating autonomous navigation tasks. However, the cost and infrastructure requirements of RTK limit its adoption, motivating more cost-effective solutions.

In this letter, we present a novel tightly coupled state estimation framework that achieves high-precision localization by combining single-frequency GNSS measurements with relative-motion observations from sensors such as wheel encoders, cameras, or LiDAR. We propose a sliding-window factor graph that integrates generic relative motion with carrier-phase difference constraints over adaptively selected temporal baselines.

To eliminate reliance on physical base stations, we introduce a *virtual anchor* mechanism: upon the initial observation of a satellite, its state is retained as a temporal reference for long-baseline phase differences. Relative-motion priors support cycle-slip detection and ambiguity recovery, enabling continued use of epoch-to-anchor constraints using only single-frequency GNSS observations.

Extensive real-world experiments on four self-collected sequences demonstrate 3D position RMSE values of 0.085–0.525 m. On two additional kilometer-scale public SLAM sequences, the proposed constraints reduce the trajectory RMSE by up to 63.6% relative to the odometry baseline.
