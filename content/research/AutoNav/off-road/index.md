---
title: Off-Road Navigation
subtitle: Real-time Spatial-temporal Traversability Assessment via Feature-based Sparse Gaussian Process
date: 2025-10-23
image:
  focal_point: 'top'
summary: Real-time Spatial-temporal Traversability Assessment via FSGP-BGK 
tags: [AutoNav]

---

<!--more-->

Terrain analysis is critical for the practical application of ground mobile robots in real-world tasks, especially in outdoor unstructured environments. In this paper,we propose a novel spatial-temporal traversability assessment method, which aims to enable autonomous robots to effectively navigate through complex terrains. Our approach utilizes sparse Gaussian processes (SGP) to extract geometric features
(curvature, gradient, elevation, etc.) directly from point cloud scans. These features are then used to construct a high-resolution local traversability map. Then, we design a spatial-temporal Bayesian Gaussian kernel (BGK) inference method to dynamically evaluate traversability scores, integrating historical and real-time data while considering factors such as slope, flatness, gradient, and uncertainty metrics. GPU acceleration is applied in the feature extraction step, and the system achieves real-time performance. Extensive simulation experiments across diverse terrain scenarios demonstrate that our method outperforms SOTA approaches in both accuracy and computational efficiency. Additionally, we develop an autonomous navigation framework integrated with the traversability map and validate it with a differential driven vehicle in complex outdoor environments. Our code will be open-source for further research and development by the community,https://github.com/ZJU-FAST-Lab/FSGP_BGK.

**Related Publications:**

- [Real-time Spatial-temporal Traversability Assessment via Feature-based Sparse Gaussian Process
  ](https://fast-fire.github.io/publication/conference-paper/iros2025-hzy-traversability/)

**Video:**

- [bilibili：【Real-time Spatial-temporal Traversability Assessment via Feature-based Sparse-GP】](https://www.bilibili.com/video/BV13msgztEMX/?share_source=copy_web&vd_source=c281e29c6456ee7bc965eaf485fcb88c)
- [YouTube: Real-time Spatial-temporal Traversability Assessment via Feature-based Sparse Gaussian Process](https://youtu.be/T8aI8dNnIBk?si=45szpdyz7UMKnW7f)
