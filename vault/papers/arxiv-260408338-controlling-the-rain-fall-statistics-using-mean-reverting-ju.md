---
# CSL-compatible fields
title: "Controlling the rain fall statistics using Mean-Reverting Jump Diffusion model"
author:
  - literal: "Joya GhoshDastider"
  - literal: "D. Pal"
  - literal: "Pankaj Kumar Mishra"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08338"

# Custom fields
paper_id: "2604.08338"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "mean-reverting-jump-diffusion-precipitation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-12T05:03:11Z"
created_at: "2026-04-12T05:03:11Z"
---

# Controlling the rain fall statistics using Mean-Reverting Jump Diffusion model

**Authors**: Joya GhoshDastider, D. Pal, Pankaj Kumar Mishra
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08338](https://arxiv.org/abs/2604.08338)

## Summary

This paper introduces a stochastic mean-reverting jump-diffusion model designed to simulate rainfall time series while capturing complex dynamics such as intermittency and extreme events. The framework is validated using long-term, half-hourly rainfall data from North-East India, demonstrating its ability to reproduce observed multifractal features and superdiffusive behavior. Furthermore, the authors show that adjusting model parameters enables the control of rainfall statistics, including the frequency of extreme events and dry-patch durations. The approach provides a robust, physically-interpretable tool for synthetic data generation and for investigating the underlying stochastic processes governing precipitation.

## Key Contributions

- Introduced a mean-reverting jump-diffusion model that replicates key rainfall statistical features including superdiffusive behavior (exponent ~1.8) and multifractal properties.
- Demonstrated that systematic parameter variation allows control over extreme event occurrence and dry-patch durations, alongside transitions between Log-Normal and Gamma distributions.
- Validated the model against long-term, high-frequency (half-hourly) rainfall data from North-East India, confirming spectral and wavelet alignment.

## Open Questions & Future Work

- [[spatio-temporal-rainfall-propagation-modeling]]
- [[non-stationary-stochastic-forcing-dynamics]]

## Key Concepts

- [[mean-reverting-jump-diffusion-precipitation]]: A stochastic modeling framework that uses mean-reverting jump diffusion to characterize, simulate, and control intermittency and extreme-event dynamics in rainfall time series.

## Archivist Review

I approved the mean-reverting jump-diffusion approach as a distinct concept because it provides a specific, physically-interpretable method for controlling the statistical properties (intermittency/superdiffusion) of time series, which is a key requirement for reliable synthetic data generation. I approved the two open questions because they identify clear research bottlenecks regarding the spatial extension and non-stationary adaptation of stochastic models, both of which are critical for robust long-term climate forecasting.

### Approved Concepts
- Mean-Reverting Jump Diffusion (Precipitation): Provides a parametric framework to control and replicate the non-Gaussian, intermittent, and multifractal statistics—specifically superdiffusive behavior—inherent in complex hydrological time series.

### Approved Open Questions
- Spatio-temporal rainfall propagation modeling: Transitioning from site-specific modeling to regional or global climate scales is critical for accurately simulating the propagation of extreme weather events.
- Non-stationary stochastic forcing dynamics: Understanding how non-stationary environmental shifts dynamically alter the intensity, frequency, and multifractal complexity of precipitation is a central challenge in climate-aware forecasting.

### Rejected Candidates
- [concept] Mean-Reverting Jump Diffusion Model (Rainfall) (`mean-reverting-jump-diffusion-model-rainfall`) - other: Renamed for better consistency with existing naming conventions.
- [open_question] Parameterized stochastic forcing dynamics (`parameterized-stochastic-forcing-climate-change`) - other: Renamed for better precision regarding non-stationarity.

## Links

- [Abstract](https://arxiv.org/abs/2604.08338)
- [PDF](https://arxiv.org/pdf/2604.08338)

