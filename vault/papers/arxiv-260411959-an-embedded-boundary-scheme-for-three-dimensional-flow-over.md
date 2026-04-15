---
# CSL-compatible fields
title: "An Embedded Boundary Scheme for Three-Dimensional Flow Over Terrain on a Staggered Mesh"
author:
  - literal: "Soonpil Kang"
  - literal: "Ann S. Almgren"
  - literal: "Mahesh Natarajan"
  - literal: "Aaron M. Lattanzi"
  - literal: "Jeffrey D. Mirocha"
  - literal: "Katie Lundquist"
  - literal: "Jordan Musser"
  - literal: "Weiqun Zhang"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11959"

# Custom fields
paper_id: "2604.11959"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:05:42Z"
created_at: "2026-04-15T05:05:42Z"
---

# An Embedded Boundary Scheme for Three-Dimensional Flow Over Terrain on a Staggered Mesh

**Authors**: Soonpil Kang, Ann S. Almgren, Mahesh Natarajan, Aaron M. Lattanzi, Jeffrey D. Mirocha, Katie Lundquist, Jordan Musser, Weiqun Zhang
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11959](https://arxiv.org/abs/2604.11959)

## Summary

This paper presents a novel embedded boundary (EB) approach for simulating 3D fluid flow on staggered grids, where velocity and thermodynamic variables are stored at different locations. By maintaining distinct geometric representations for cell-centered and face-centered quantities, the method effectively integrates complex boundaries into the staggered framework. Furthermore, the authors adapt the weighted state redistribution (WSRD) technique to address the stability challenges associated with small boundary-intersected cells. The framework is implemented in the Energy Research and Forecasting (ERF) model and validated against traditional terrain-following coordinate methods.

## Key Contributions

- Introduces an embedded boundary (EB) formulation specifically designed for staggered meshes in 3D fluid simulations.
- Extends the weighted state redistribution (WSRD) scheme to staggered grids to mitigate small-cell numerical instabilities.
- Validates the method within the Energy Research and Forecasting (ERF) model by demonstrating consistency with terrain-following coordinate approaches.

## Links

- [Abstract](https://arxiv.org/abs/2604.11959)
- [PDF](https://arxiv.org/pdf/2604.11959)

