---
title: Implementation of streamline simulation based on finite element method in
  FEniCS
abstract: Understanding flow and transport behaviors in subsurface porous rock
  is extremely important for various applications such as oil/gas reservoirs,
  groundwater, geothermal energy explorations, and CO2 sequestration. However,
  the relevant calculation is never an easy task because of the large areal
  extend and high heterogeneity of subsurface system. Although streamline-based
  simulations are suitable for solving large, geologically complex, and
  heterogeneous systems, they still present difficulties while working with the
  finite element method. This paper introduces a new algorithm to trace
  streamlines based on the underlying flow field in unstructured triangular mesh
  systems. The new solution procedure only requires velocities on each element
  vertex but not on cell facets, and therefore it does not rely on conservative
  fluxes. The algorithm is based on coupled ODEs derived from shape functions as
  well as the transformation formula between the actual and master elements. The
  analytical solution describing the trajectory of a streamline segment in the
  master element is derived so that the time-offlight and exit coordinate
  (leaving the element) can be determined accurately and efficiently.
  Additionally, the presented algorithm allows the implementation of
  streamline-based methods in the programming framework, FEniCS, so as to extend
  the technique to other research areas.
slides: null
url_pdf: http://arxiv.org/pdf/1512.04133v1
publication_types:
  - "2"
authors:
  - Feng Yin
  - Erxiu Shi
  - Yi Luo
  - Bin Wang
  - Liehui Zhang
  - and Yulong Zhao
publication: ""
featured: false
tags:
  - Source Themes
projects:
  - internal-project
summary: This paper introduces a new algorithm to trace streamlines based on the
  underlying flow field in unstructured triangular mesh systems. The new
  solution procedure only requires velocities on each element vertex but not on
  cell facets, and therefore it does not rely on conservative fluxes.
url_dataset: "#"
url_project: ""
publication_short: ""
url_source: "#"
url_video: "#"
date: 2020-02-01T02:40:49.258Z
url_slides: ""
links:
  - name: Custom Link
    url: http://example.org
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)"
  focal_point: ""
  preview_only: false
  filename: ctfracstress.jpg
publishDate: 2017-01-01T00:00:00.000Z
url_poster: "#"
url_code: "#"
doi: ""
---

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/).
