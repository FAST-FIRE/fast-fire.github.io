---
title: 'Trajectory optimization for 3d shape-changing robots with differential mobile base'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mengke Zhang
  - Chao Xu
  - Fei Gao
  - Yanjun Cao

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-05-29'
doi: '10.1109/ICRA48891.2023.10160911'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-29'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2023 IEEE International Conference on Robotics and Automation (ICRA 2023)
publication_short: 

abstract: Service robots have attracted extensive attention due to specially designed functions, such as mobile manipulators or robots with extra structures. For robots that have changing shapes, autonomous navigation in the real world presents new challenges. In this paper, we propose a trajectory optimization method for differential-drive mobile robots with controllable changing shapes in dense 3D environments. We model the whole-body trajectory as a polynomial trajectory that satisfies the nonholonomic dynamics of the base and dynamics of the extra joints. These constraints are converted into soft constraints, and an activation function for dense sampling is applied to avoid nonlinear mutations. In addition, we guarantee the safety of full shape by limiting the system's distance from obstacles. To comprehensively simulate a large extent of height and width changes, we designed a novel Shape-Changing Robot with a Differential Base (SCR-DB). Our global trajectory optimization gives a smooth and collision-free trajectory for SCR-DB at a low computational cost. We present vast simulations and real-world experiments to validate our performance, including coupled whole-body and independent differential-driven vehicle motion planning.

# Summary. An optional shortened abstract.
summary: Trajectory optimization for 3d shape-changing robots with differential mobile base

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10160911'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.bilibili.com/video/BV1RW4y1v7ba'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**FAST-FIRE**](https://pages.fast-fire.space)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---



