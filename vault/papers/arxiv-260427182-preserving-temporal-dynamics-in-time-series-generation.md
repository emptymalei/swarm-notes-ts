---
# CSL-compatible fields
title: "Preserving Temporal Dynamics in Time Series Generation"
author:
  - literal: "Ci Lin"
  - literal: "Futong Li"
  - literal: "Tet Yeap"
  - literal: "Iluju Kiringa"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.27182"

# Custom fields
paper_id: "2604.27182"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "generative-models"
  - "data-augmentation"
  - "forecasting"
  - "time-series-generation"
  - "mcmc"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mcmc-based-temporal-dynamics-correction"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:09:05Z"
created_at: "2026-05-02T05:09:05Z"
---

# Preserving Temporal Dynamics in Time Series Generation

**Authors**: Ci Lin, Futong Li, Tet Yeap, Iluju Kiringa
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.27182](https://arxiv.org/abs/2604.27182)

## Summary

This paper addresses the common issue of temporal drift and distribution shift in GAN-based time series generation, where models fail to preserve sequential dynamics. The authors introduce a model-agnostic MCMC-based framework that enforces consistency with empirical transition laws during generation to mitigate these discrepancies. By correcting the transition statistics between neighboring time points, the proposed approach significantly enhances the fidelity and utility of synthetic time series as measured by autocorrelation, skewness, and predictive performance.

## Key Contributions

- Proposes a model-agnostic MCMC-based framework that corrects cumulative deviations and temporal drift in synthetic time series.
- Provides a theoretical analysis of how conditional generative models accumulate errors during sequential generation.
- Demonstrates significant improvements in autocorrelation alignment and predictive metrics across multiple datasets (Lorenz, Licor, ETTh, and ILI) when integrated with existing GAN models.

## Open Questions & Future Work

- [[mcmc-integration-with-diffusion-models]]
- [[end-to-end-mcmc-training]]

## Key Concepts

- [[mcmc-based-temporal-dynamics-correction]]: A model-agnostic MCMC framework that enforces consistency with empirical transition statistics to improve temporal fidelity in synthetic time series.

## Archivist Review

The approved concepts and open questions address a fundamental issue in time-series generation: the tendency of generative models to suffer from temporal drift and error accumulation. The MCMC-based correction framework is identified as a reusable mechanism, and the open questions prioritize the investigation of how these consistency constraints can move from post-hoc correction to native integration and diffusion-based generation. I rejected the proposed datasets as they are standard benchmarking datasets rather than novel contributions central to the paper's identity.

### Approved Concepts
- MCMC-based temporal dynamics correction: It provides a principled, model-agnostic method to correct cumulative temporal drift in synthetic time series generation, which is a major bottleneck in existing generative approaches.

### Approved Open Questions
- MCMC-diffusion model integration: Diffusion models represent a state-of-the-art approach to generative modeling; understanding if post-hoc correction mechanisms apply to them is essential for future synthetic data reliability.
- End-to-end MCMC training integration: End-to-end integration would potentially eliminate post-processing overhead and allow generators to learn native temporal consistency, representing a significant shift in training methodology.

## Links

- [Abstract](https://arxiv.org/abs/2604.27182)
- [PDF](https://arxiv.org/pdf/2604.27182)

