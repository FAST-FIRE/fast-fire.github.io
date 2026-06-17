---
title: "Congratulations to Juncheng Chen: IROS 2026 paper accepted for oral presentation"
subtitle:
date: 2026-06-17
image:
  focal_point: 'Smart'
tags: [PaperAccepted]
---

Congrats to Juncheng Chen — our IROS 2026 paper was accepted for an **oral presentation**.

<!--more-->

Image matching is fundamental to visual reconstruction or robotic perception, while learning-based semi-dense matching provides advantages in accuracy, robustness, and efficiency. However, semi-dense matcher's zero-shot generalization remains limited, as existing data paradigms rarely provide both sufficient viewpoint diversity and accurate dense annotations. In addition, pure reliance on 2D image features without explicit 3D geometric awareness weakens robustness under large viewpoint changes. In this work, we introduce MatchGS, the first systematic 3DGS-based training framework for zero-shot semi-dense image matching, which consists of two key components. (1) A geometrically faithful data generation pipeline that produces dense annotations and photorealistic data with expansive viewpoint diversity. Our pipeline reduces epipolar error by up to 40 times compared to existing datasets and enables supervision under extreme viewpoint changes. (2) A patch-voxel representation alignment strategy that injects explicit 3DGS knowledge into image matching, guiding 2D semi-dense matchers to learn viewpoint-invariant 3D representations via Gaussian features. Experiments validate semi-dense matchers trained solely on our data achieve significant zero-shot performance gains on public benchmarks, with improvements of up to 17.7%. Our work demonstrates that 3DGS can be refined as an accurate, structurally-rich, and scalable data source, paving the way for more robust zero-shot image matchers. Code and dataset will be released soon.