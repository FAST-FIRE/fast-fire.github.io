---
title: "Congratulations to Zhenyu Hou: IROS 2025 paper accepted for oral presentation"
subtitle:
date: 2025-10-23
image:
  focal_point: 'Smart'
tags: [PaperAccepted]
---

Congrats to Zhenyu Hou — our IROS 2025 paper was accepted for an **oral presentation**.

<!--more-->

Terrain analysis is critical for deploying ground mobile robots in real-world tasks, especially in outdoor, unstructured environments. In this paper, we propose a novel **spatio-temporal traversability assessment** method that enables autonomous robots to navigate complex terrains effectively. Our approach uses **sparse Gaussian processes (SGP)** to extract geometric features (curvature, gradient, elevation, etc.) directly from point-cloud scans, which are then fused into a high-resolution local traversability map. We further design a **spatio-temporal Bayesian Gaussian kernel (BGK)** inference method to dynamically evaluate traversability scores by integrating historical and real-time data while accounting for slope, flatness, gradient, and uncertainty. With GPU-accelerated feature extraction, the system achieves real-time performance. Extensive simulation studies across diverse terrain scenarios show that our method outperforms **state-of-the-art (SOTA)** baselines in both accuracy and computational efficiency. Finally, we build an autonomous navigation framework around the traversability map and validate it on a differential-drive platform in complex outdoor environments. Our code will be open-sourced at [github.com/ZJU-FAST-Lab/FSGP_BGK](https://github.com/ZJU-FAST-Lab/FSGP_BGK).



