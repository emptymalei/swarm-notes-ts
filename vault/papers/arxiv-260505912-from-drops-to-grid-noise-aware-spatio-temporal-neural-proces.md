---
# CSL-compatible fields
title: "From Drops to Grid: Noise-Aware Spatio-Temporal Neural Process for Rainfall Estimation"
author:
  - literal: "Rafael Pablos Sarabia"
  - literal: "Joachim Nyborg"
  - literal: "Morten Birk"
  - literal: "Ira Assent"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05912"

# Custom fields
paper_id: "2605.05912"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "uncertainty-quantification"
  - "spatio-temporal"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dropstogrid"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:11:38Z"
created_at: "2026-05-09T05:11:38Z"
---

# From Drops to Grid: Noise-Aware Spatio-Temporal Neural Process for Rainfall Estimation

**Authors**: Rafael Pablos Sarabia, Joachim Nyborg, Morten Birk, Ira Assent
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05912](https://arxiv.org/abs/2605.05912)

## Summary

DropsToGrid is a neural process-based framework designed to generate high-resolution, dense rainfall fields by integrating sparse, noisy weather station data with spatial radar context. The model employs multi-scale feature extraction and temporal attention mechanisms to fuse these multi-modal sources while providing continuous, stochastic estimates with quantified uncertainty. Empirical evaluations demonstrate that the method achieves superior accuracy and uncertainty calibration compared to established operational and deep learning benchmarks, particularly in data-scarce and cross-regional settings.

## Key Contributions

- Introduces DropsToGrid, a neural process-based architecture for high-resolution rainfall field reconstruction from heterogeneous, noisy input sources.
- Demonstrates superior performance over operational and deep learning baselines in generating high-resolution rainfall maps with calibrated uncertainty.
- Validates robustness in sparse-station and cross-regional scenarios, addressing the limitations of existing rainfall densification techniques.

## Open Questions & Future Work

- [[extending-np-for-multivariable-assimilation]]

## Key Concepts

- [[dropstogrid]]: A neural process-based framework for generating dense, uncertainty-quantified rainfall fields from sparse, noisy point observations and radar data.

## Archivist Review

I approved the DropsToGrid architecture as a specialized application of neural processes for irregular, noisy spatial-temporal data, which is a reusable pattern in environmental modeling. I also approved the open question regarding multi-variable data assimilation, as it addresses a fundamental limitation in applying generative neural processes to complex, multi-modal climate systems. Other proposed items were rejected as they did not meet the stringent criteria for permanent vault inclusion or were specific to the paper's implementation.

### Approved Concepts
- DropsToGrid: Central architectural contribution combining neural processes for spatio-temporal densification of noisy, irregular rainfall data.

### Approved Open Questions
- Multi-variable probabilistic data assimilation: This represents a significant architectural bottleneck for general-purpose meteorological data assimilation using deep generative models.

## Links

- [Abstract](https://arxiv.org/abs/2605.05912)
- [PDF](https://arxiv.org/pdf/2605.05912)

