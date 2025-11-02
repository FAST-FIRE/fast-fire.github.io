---
title: "Universal Trajectory Optimization Framework for Differential Drive Robot Class"
authors:
- Mengke Zhang
- Nanhe Chen
- Hu Wang
- Jianxiong Qiu
- Zhichao Han
- Qiuyu Rem
- Chao Xu
- Fei Gao
- Yanjun Cao
date: "2025-05-12"
doi: "10.1109/TASE.2025.3550676"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-12"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Automation Science and Engineering (TASE)"
publication_short: 

abstract: Differential drive robots are widely used in various scenarios thanks to their straightforward principle, from household service robots to disaster response field robots. The nonholonomic dynamics and possible lateral slip of these robots lead to difficulty in getting feasible and high-quality trajectories. Although there are several types of driving mechanisms for real-world applications, they all share a similar driving principle, which involves controlling the relative motion of independently actuated tracks or wheels to achieve both linear and angular movement. Therefore, a comprehensive trajectory optimization to compute trajectories efficiently for various kinds of differential drive robots is highly desirable. In this paper, we propose a universal trajectory optimization framework, enabling the generation of high-quality trajectories within a restricted computational timeframe for these robots. We introduce a novel trajectory representation based on polynomial parameterization of motion states or their integrals, such as angular and linear velocities, which inherently matches the robots’ motion to the control principle. The trajectory optimization problem is formulated to minimize computation complexity while prioritizing safety and operational efficiency. We then build a full-stack autonomous planning and control system to demonstrate its feasibility and robustness. We conduct extensive simulations and real-world testing in crowded environments with three kinds of differential drive robots to validate the effectiveness of our approach.Note to Practitioners—The Differential drive robot, known for its simple mechanics and high maneuverability, is widely used in many applications. However, current methods have limitations in practice when high-performance motion is needed. Due to the state representation in Cartesian space, path planning makes it difficult to consider nonholonomic constraints directly. The existing trajectory optimization cannot effectively constrain the angular velocity and it is difficult to model forward and backward motion into a continuous trajectory. This paper provides a novel trajectory representation that inherently utilizes the motion performance of differential drive robots, which ensures its universality for different platforms, and reduces the time required to generate trajectories to ensure real-time performance. Based on this, we propose a robust planning and control framework to achieve efficient navigation. We release the source code at https://zju-fast-lab.github.io/DDR-opt/ facilitating expansion and deployment for practitioners. We validate this framework through extensive experiments, demonstrating its capability to navigate challenging environments.


# Summary. An optional shortened abstract.
summary: Universal Trajectory Optimization Framework for Differential Drive Robot Class

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10924228
url_code: 'https://zju-fast-lab.github.io/DDR-opt/'
url_dataset: ''
url_poster: ''
url_project: 'https://zju-fast-lab.github.io/DDR-opt/'
url_slides: ''
url_source: ''
url_video: 'https://www.bilibili.com/video/BV1gJxveMEm8'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**FAST-FIRE**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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



