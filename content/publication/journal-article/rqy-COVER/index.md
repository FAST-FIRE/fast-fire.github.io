---
title: "COVER: cross-vehicle transition framework for quadrotor control in air-ground cooperation"
authors:
- Qiuyu Ren
- Miao Xu
- Mengke Zhang
- Nanhe Chen
- Mingwei Lai
- Chao Xu
- Fei Gao
- Yanjun Cao
author_notes:
# - "Equal contribution"

date: "2025-09-12"
doi: "10.1109/LRA.2025.3597510"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-12"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Autonomous Robots (AR)"
publication_short: ""

abstract: UAV transitions across UGVs enable diverse air-ground cooperation (AGC) applications,such as cross-vehicle landing, delivery, and rescue. However, achieving precise and efficient transitions across multiple moving UGVs without prior knowledge of their trajectories remains highly challenging. This paper proposes COVER, a cross-vehicle transition frame work for quadrotor control in AGC scenarios. In COVER, the UAV is directly controlled in UGVs’ body frames as non-inertial frames, thus eliminating all dependencies in the world frame. Each transition process is divided into three stages:the initial stage, transition stage, and final stage, with pre-set stage transition points and stage-varying system states. Then,an optimal reference trajectory is generated at each stage by solving a non-linear programming (NLP) problem. The effect of the target UGV’s rotation on the initial relative velocity is eliminated to obtain a dynamically feasible and smooth transition reference trajectory. Finally, we design a stage-adaptive model predictive control (SAMPC) method, proposing a novel MPC position reference mode to avoid indirect routes at the transition stage. The SAMPC method effectively mitigates the flight instability caused by reference frame transition and eliminates the effect of reference frame rotation at the transition stage. And it can flexibly adapt to accurate requirements at the final stage by switching position reference mode and adjusting cost weights. Simulation benchmarks and extensive real-world experiments validate that our approach can achieve smooth, short-distance, and accurate cross-vehicle operations.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**FAST-FIRE**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---



