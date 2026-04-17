---
# CSL-compatible fields
title: "Irregularly Sampled Time Series Interpolation for Binary Evolution Simulations Using Dynamic Time Warping"
author:
  - literal: "Ugur Demir"
  - literal: "Philipp M. Srivastava"
  - literal: "Aggelos Katsaggelos"
  - literal: "Vicky Kalogera"
  - literal: "Santiago L. Tapia"
  - literal: "Manuel Ballester"
  - literal: "Shamal Lalvani"
  - literal: "Patrick Koller"
  - literal: "Jeff J. Andrews"
  - literal: "Seth Gossage"
  - literal: "Max M. Briel"
  - literal: "Elizabeth Teng"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13604"

# Custom fields
paper_id: "2604.13604"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "joint-alignment-track-averaging"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:07:52Z"
created_at: "2026-04-17T05:07:52Z"
---

# Irregularly Sampled Time Series Interpolation for Binary Evolution Simulations Using Dynamic Time Warping

**Authors**: Ugur Demir, Philipp M. Srivastava, Aggelos Katsaggelos, Vicky Kalogera, Santiago L. Tapia, Manuel Ballester, Shamal Lalvani, Patrick Koller, Jeff J. Andrews, Seth Gossage, Max M. Briel, Elizabeth Teng
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13604](https://arxiv.org/abs/2604.13604)

## Summary

This paper addresses the computational expense of generating binary stellar evolution models by proposing an interpolation framework for irregularly sampled tracks. The authors introduce a joint-alignment strategy using Dynamic Time Warping to synchronize multiple physical parameters onto a consistent grid, ensuring that underlying physical relationships remain intact. Empirical evaluation confirms that this approach effectively manages the complexities of binary interactions and outperforms standard interpolation methods in astrophysical population synthesis.

## Key Contributions

- Introduced a novel track alignment and iterative track averaging method based on Dynamic Time Warping (DTW) for irregularly sampled binary stellar evolution data.
- Demonstrated that joint-alignment across all physical parameters preserves critical physical laws like the Stefan-Boltzmann law during interpolation.
- Achieved superior interpolation accuracy on complex binary stellar tracks compared to traditional interpolation techniques.

## Open Questions & Future Work

- [[morphology-aware-neighbor-selection]]

## Key Concepts

- [[joint-alignment-track-averaging]]: An interpolation method using Dynamic Time Warping to compute a shared warping path across multivariate physical parameters, preserving causal relationships.

## Archivist Review

The approved concept represents a novel and reusable approach to multivariate alignment for irregularly sampled data, which is central to the paper's contribution. The approved open question addresses the significant challenge of neighbor selection in sparse high-dimensional parameter spaces, a bottleneck for interpolation accuracy. I have maintained a selective approach, rejecting generic or local components.

### Approved Concepts
- Joint-Alignment Track Averaging: It provides a physically-consistent way to handle misaligned multivariate temporal data by enforcing a shared warping constraint.

### Approved Open Questions
- Morphology-Aware Neighbor Selection: This is a fundamental bottleneck for improving the accuracy and reliability of interpolation in sparse regions of astrophysical model grids.

## Links

- [Abstract](https://arxiv.org/abs/2604.13604)
- [PDF](https://arxiv.org/pdf/2604.13604)

