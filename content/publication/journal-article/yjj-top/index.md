---
title: "TOP: Trajectory Optimization via Parallel Optimization towards Constant Time Complexity "
authors:
- Jiajun Yu
- Nanhe Chen
- Guodong Liu
- Chao Xu
- Fei Gao
- Yanjun Cao
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-10-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Robotics and Automation Letters (RAL)"
publication_short: ""
abstract: Optimization has been widely used to generate smooth trajectories for motion planning. However, existing trajectory optimization methods show weakness when dealing with large-scale long trajectories. Recent advances in parallel computing have accelerated optimization in some fields, but how to efficiently solve trajectory optimization via parallelism remains an open question. In this paper, we propose a novel trajectory optimization framework based on the Consensus Alternating Direction Method of Multipliers (CADMM) algorithm, which decomposes the trajectory into multiple segments and solves the subproblems in parallel. The proposed framework reduces the time complexity to \(O(1)\) per iteration with respect to the number of segments, compared to \(O(N)\) of the state-of-the-art (SOTA) approaches. Furthermore, we introduce a closed-form solution that integrates convex linear and quadratic constraints to speed up the optimization, and we also present a numerical solution for general convex inequality constraints. A series of simulations and experiments demonstrate that our approach outperforms the SOTA approach in terms of efficiency and smoothness. Especially for a large-scale trajectory, with one hundred segments, achieving over a tenfold speedup. To fully explore the potential of our algorithm on modern parallel computing architectures, we deploy our framework on a GPU and show high performance with thousands of segments.

# Summary. An optional shortened abstract.

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2507.10290
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



