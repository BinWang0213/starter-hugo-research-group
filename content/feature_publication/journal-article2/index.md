---
abstract: The efficient solution of large sparse saddle point systems is very
  important in computational fluid mechanics. The discontinuous Galerkin finite
  element methods have become increasingly popular for incompressible flow
  problems but their application is limited due to high computational cost. We
  describe C++ programming techniques that may help to accelerate linear solvers
  for such problems. The approach is based on the policybased design pattern and
  partial template specialization, and is implemented in the open source AMGCL
  li­ brary. The efficiency is demonstrated with the example of accelerating an
  iterative solver of a discontinuous Galerkin finite element method for the
  Stokes problem. The implementation allows selecting algorithmic com­ ponents
  of the solver by adjusting template parameters without any changes to the
  codebase. It is possible to switch the system matrix to use small statically
  sized blocks to store the nonzero values, or use a mixed precision solution,
  which results in up to 4 times speedup, and reduces the memory footprint of
  the algorithm by about 40%. We evaluate both monolithic and composite
  preconditioning strategies for 3 benchmark problems. The performance of the
  proposed solution is compared with a multithreaded direct Pardiso solver and a
  parallel iterative PETSc solver.
slides: null
url_pdf: http://arxiv.org/pdf/1512.04133v1
publication_types:
  - "2"
authors:
  - Demidov Denis
  - Lin Mu
  - and Bin Wang
author_notes: []
publication: Journal of Computational Science
summary: We describe C++ programming techniques that may help to accelerate
  linear solvers for such problems. It results in up to 4 times speedup and
  reduces the memory footprint of the algorithm by about 40%.
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Accelerating linear solvers for Stokes problems with C++ metaprogramming
doi: ""
featured: false
tags:
  - Source Themes
projects: []
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"
  focal_point: ""
  preview_only: false
  filename: amgcl.jpg
date: 2021-02-01T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/).



