---
title: An GPU-accelerated particle tracking method for Eulerian–Lagrangian
  simulations using hardware ray tracing cores
abstract: To address the high computational cost of particle tracking for
  realistic Eulerian–Lagrangian simulations, a novel efficient and robust
  particle tracking method (RT method) for unstructured meshes is presented. The
  method, for the first time, leverages both hardware ray tracing (RT) cores and
  GPU parallel computing technology to accelerate Eulerian–Lagrangian
  simulations. The method includes a hardware-accelerated hosting cell locator
  using bounding volume hierarchy tree (BVH) and a robust treatment of
  particle-wall interaction (multiple specular reflection) using an improved
  neighbor searching approach. The method is implemented in a GPU-accelerated
  open-source code, which is verified against a reference neighbor-searching
  particle-tracking method (NS method) and experimental observations. To
  evaluate the performance of our method, several numerical simulations of
  fluid-driven scalar transport problem are solved. Using a verification case,
  we show that the particle distribution simulated by our code is in a good
  agreement with an experimental observation. Tracking failures and stuck
  particles are not observed in any simulations. Benchmark results indicate that
  our RT method leads to a roughly  performance improvement compared to the
  reference NS method for large-scale simulations (millions of mesh cells and
  particles).
slides: null
url_pdf: http://arxiv.org/pdf/1512.04133v1
publication_types:
  - "2"
authors:
  - Wang
  - Bin
  - Ingo Wald
  - Nate Morrical
  - Will Usher
  - Lin Mu
  - Karsten Thompson
  - and Richard Hughes
publication: Computer Physics Communications
featured: false
tags:
  - Source Themes
projects:
  - internal-project
summary: "Tracing streamlines launched from a wellbore is important, especially
  for time-sensitive transport behaviors. An embedded grid-free approach to
  integrate near-wellbore transport behaviors into streamline simulations is
  developed. "
url_dataset: "#"
url_project: ""
publication_short: ""
url_source: "#"
url_video: "#"
date: 2022-02-01T02:24:22.224Z
url_slides: ""
links:
  - name: Custom Link
    url: http://example.org
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)"
  focal_point: ""
  preview_only: false
  filename: rtx-pt.png
publishDate: 2017-01-01T00:00:00.000Z
url_poster: "#"
url_code: "#"
doi: ""
---

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/).
