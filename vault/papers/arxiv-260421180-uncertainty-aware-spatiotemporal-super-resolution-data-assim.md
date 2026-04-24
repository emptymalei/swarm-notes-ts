---
# CSL-compatible fields
title: "Uncertainty-Aware Spatiotemporal Super-Resolution Data Assimilation with Diffusion Models"
author:
  - literal: "Aditya Sai Pranith Ayapilla"
  - literal: "Kazuya Miyashita"
  - literal: "Yuki Yasuda"
  - literal: "Ryo Onishi"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21180"

# Custom fields
paper_id: "2604.21180"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "uncertainty-aware-trajectory-prediction"
  - "physics-spatiotemporal-masked-autoencoder"
  - "generative-super-resolution-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "diffsrda"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:08:29Z"
created_at: "2026-04-24T05:08:29Z"
---

# Uncertainty-Aware Spatiotemporal Super-Resolution Data Assimilation with Diffusion Models

**Authors**: Aditya Sai Pranith Ayapilla, Kazuya Miyashita, Yuki Yasuda, Ryo Onishi
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21180](https://arxiv.org/abs/2604.21180)

## Summary

This paper presents DiffSRDA, a probabilistic data assimilation framework that utilizes denoising diffusion models for efficient spatiotemporal super-resolution of chaotic systems. By conditioning on low-resolution forecast time series and sparse observations, the model generates high-resolution analysis ensembles that provide robust point estimates and physically meaningful uncertainty quantification. Experiments on barotropic ocean jet instability show that DiffSRDA achieves EnKF-level performance with reduced computational costs and offers a training-free strategy for adapting to changing sensor configurations.

## Key Contributions

- Introduces DiffSRDA, a diffusion-based framework for probabilistic spatiotemporal super-resolution data assimilation that leverages low-resolution forecast inputs.
- Demonstrates reconstruction performance comparable to high-resolution Ensemble Kalman Filter (EnKF) benchmarks while requiring only computationally inexpensive low-resolution forecasts.
- Proposes a training-free observation-consistency guidance mechanism using the score-based structure of diffusion models to handle sensor-layout shifts.

## Open Questions & Future Work

- [[calibrating-generative-da-uncertainty]]

## Key Concepts

- [[diffsrda]]: A probabilistic spatiotemporal super-resolution data assimilation framework that conditions diffusion models on low-resolution forecast time series and sparse high-resolution observations.

## Archivist Review

I approved the DiffSRDA framework as it introduces a novel approach for integrating low-resolution forecast inputs with diffusion-based data assimilation. I also approved the open question regarding the calibration of generative DA because it highlights a critical barrier to deploying diffusion models for high-stakes physical state estimation. I rejected no candidates because the initial submission provided only one concept and one open question, both of which met the standards.

### Approved Concepts
- DiffSRDA: DiffSRDA provides a specific, reusable paradigm for integrating low-resolution model forecasts with sparse high-resolution observations using diffusion models for data assimilation.

### Approved Open Questions
- Calibration of Generative Data Assimilation: Reliable uncertainty quantification is critical for the application of generative models in high-stakes geophysical and environmental forecasting; uncalibrated ensembles can lead to overconfident or misleading state estimates.

## Links

- [Abstract](https://arxiv.org/abs/2604.21180)
- [PDF](https://arxiv.org/pdf/2604.21180)

