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
  - "time-series"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "joint-dtw-alignment"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:54:26Z"
created_at: "2026-04-18T04:54:26Z"
---

# Irregularly Sampled Time Series Interpolation for Binary Evolution Simulations Using Dynamic Time Warping

**Authors**: Ugur Demir, Philipp M. Srivastava, Aggelos Katsaggelos, Vicky Kalogera, Santiago L. Tapia, Manuel Ballester, Shamal Lalvani, Patrick Koller, Jeff J. Andrews, Seth Gossage, Max M. Briel, Elizabeth Teng
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13604](https://arxiv.org/abs/2604.13604)

## Summary

This paper addresses the computational bottleneck of binary stellar evolution simulations by proposing a novel interpolation method for binary tracks. By employing Dynamic Time Warping (DTW) to compute a single shared warping path across multiple physical parameters, the method effectively aligns irregularly sampled data and preserves underlying physical relationships. This joint-alignment strategy overcomes the limitations of standard interpolation in capturing the non-linear, interaction-driven discontinuities inherent in binary stellar systems. Evaluated across diverse binary configurations, the approach demonstrates superior accuracy and efficiency for stellar population synthesis applications.

## Key Contributions

- Introduces a joint Dynamic Time Warping (DTW) approach to align multiple physical parameters of binary stellar evolution tracks onto a consistent temporal grid.
- Demonstrates that preserving temporal alignment through joint-alignment maintains physical consistency, such as the Stefan-Boltzmann law, during interpolation.
- Achieves higher accuracy in binary population synthesis compared to traditional interpolation methods that fail to handle the complex, interaction-induced discontinuities of binary stars.

## Open Questions & Future Work

- [[neighbor-selection-in-sparse-parameter-spaces]]

## Key Concepts

- [[joint-dtw-alignment]]: A multi-variate alignment strategy that uses a shared warping path computed via DTW to synchronize and interpolate irregularly sampled temporal processes.

## Archivist Review

I approved the joint alignment concept because it provides a robust, reusable method for handling multi-variable, irregularly sampled time series, which is a common challenge in scientific forecasting. I also approved the open question regarding neighbor selection as it highlights a fundamental limitation of local interpolation techniques in sparse, high-sensitivity parameter spaces. I renamed the primary concept to a more general term to ensure its utility in the vault beyond this specific application.

### Approved Concepts
- Joint Dynamic Time Warping Alignment: Addresses the core challenge of interpolating irregularly sampled multi-variable systems with non-linear, interaction-driven discontinuities by enforcing temporal and causal alignment.

### Approved Open Questions
- Neighbor Selection in Sparse Spaces: This question is central to the scalability and fidelity of interpolation in complex scientific simulations where representative samples are computationally expensive to generate.

### Rejected Candidates
- [concept] Dynamic Time Warping for Binary Track Alignment (`dtw-binary-track-alignment`) - other: The concept was renamed to a more general and reusable title (Joint Dynamic Time Warping Alignment) to better reflect its application beyond stellar tracks.

## Links

- [Abstract](https://arxiv.org/abs/2604.13604)
- [PDF](https://arxiv.org/pdf/2604.13604)

