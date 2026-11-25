---
title: "Congratulations to Tiancheng Lai: T-FR 2026 paper accepted"
date: 2026-11-24
image:
  focal_point: 'Smart'
tags: [PaperAccepted]
---

Congratulations to Tiancheng Lai on the acceptance of the T-FR 2026 paper.

<!--more-->

Autonomous exploration with unmanned aerial vehicles (UAVs) in large-scale, topologically complex environments often suffers from low efficiency due to suboptimal scheduling and detours. Prior maps, such as satellite imagery, construction drawings, and hand-drawn maps, are readily available in many scenarios and encode the global structure to support long-horizon decision-making. This paper presents a novel framework that leverages sparse, unaligned, and even discrepant 2D prior maps for LiDAR-based UAV exploration.

Firstly, using a binary top-down sketch map as input, it registers the prior online against accumulating LiDAR observations, and the resulting registration uncertainty is then carried through to planning. Registration begins with GeoContext, a geometric descriptor designed to retrieve single-frame candidates by capturing the spatial relationships between 3D single-frame measurements and the prior sketch across the 2D–3D modality gap, without requiring any initial alignment. These candidates are aggregated by multi-frame verification, which filters outliers and establishes coarse transformations, and a Scale-ICP process refines the results. Together, these stages tolerate map discrepancies and retain multiple hypotheses when the geometry is ambiguous.

Secondly, a hierarchical viewpoint planning strategy then acts on these hypotheses, attaching local viewpoints spatially to the prior guidepoints and sequencing those guidepoints under each hypothesis with a Monte Carlo Tree Search solver. A risk-aware selector then ranks the resulting sequences by a heuristic confidence-weighted travel cost, and a fixed-endpoint traveling salesman problem generates an efficient local coverage path under the selected prior guidance.

Benchmark evaluations reveal up to 34.2% improvement in exploration efficiency and 37.9% reduction in flight distance compared to state-of-the-art methods, while extensive simulations and field experiments further demonstrate robustness to prior map incompleteness and deformations.
