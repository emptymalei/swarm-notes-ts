---
# CSL-compatible fields
title: "A new high-order finite-volume advection scheme on spherical Voronoi grids and a comparative study in a mimetic finite-volume moist shallow-water model"
author:
  - literal: "Luan F. Santos"
  - literal: "Jeferson B. Granjeiro"
  - literal: "Pedro S. Peixoto"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07103"

# Custom fields
paper_id: "2604.07103"
paper_source: "arxiv"
domain: "climate-and-weather-forecasting"
tags:
  - "numerical-weather-prediction"
  - "finite-volume-method"
  - "geophysical-fluid-dynamics"
  - "spherical-grid-discretization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "k-exact-reconstruction-on-spherical-grids"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:54:12Z"
created_at: "2026-04-09T04:54:12Z"
---

# A new high-order finite-volume advection scheme on spherical Voronoi grids and a comparative study in a mimetic finite-volume moist shallow-water model

**Authors**: Luan F. Santos, Jeferson B. Granjeiro, Pedro S. Peixoto
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07103](https://arxiv.org/abs/2604.07103)

## Summary

This paper develops a new class of high-order advection schemes for spherical centroidal Voronoi tessellations (SCVT) based on k-exact reconstruction. By extending planar reconstruction techniques to the sphere, the proposed method provides improved accuracy and reduced numerical diffusion for atmospheric tracer transport. The performance is extensively evaluated through classical advection tests and a mimetic finite-volume moist shallow-water model, confirming robustness on locally refined grids.

## Key Contributions

- Introduces a k-exact reconstruction advection scheme for spherical centroidal Voronoi tessellations (SCVTs), enabling high-order accuracy on irregular spherical grids.
- Demonstrates that the proposed scheme reduces numerical diffusion and improves representation of tracer structures compared to existing MPAS advection methods.
- Validates grid robustness using locally refined spherical grids with Andean topography, showing that overall model performance is constrained by the underlying shallow-water discretization rather than the advection scheme alone.

## Open Questions & Future Work

- [[dynamical-core-consistency-voronoi]]

## Key Concepts

- [[k-exact-reconstruction-on-spherical-grids]]: A technique for constructing high-order accurate advection schemes on spherical Voronoi grids by extending planar k-exact reconstruction to spherical surfaces.

## Archivist Review

I have approved the k-exact reconstruction concept as a fundamental numerical technique for irregular grid discretization in geophysical fluid dynamics. I also approved the open question regarding dynamical core consistency, as it highlights a critical bottleneck in modern numerical weather prediction models where high-order tracer transport is constrained by lower-order dynamics. No datasets were approved as none were cited as primary benchmarks or novel contributions.

### Approved Concepts
- k-exact reconstruction on spherical grids: It provides a mathematically rigorous approach for achieving high-order accuracy on irregular grids, which is a fundamental requirement for atmospheric modeling.

### Approved Open Questions
- Dynamical Core-Advection Consistency: Addressing this bottleneck is essential for advancing state-of-the-art atmospheric models (like MPAS/MONAN) and ensuring numerical consistency in global circulation simulations.

## Links

- [Abstract](https://arxiv.org/abs/2604.07103)
- [PDF](https://arxiv.org/pdf/2604.07103)

