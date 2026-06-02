---
# CSL-compatible fields
title: "ProbRes: Volatility Learning for Probabilistic Time-Series Forecasting"
author:
  - literal: "Tingting Wang"
  - literal: "Yunyi Zhang"
  - literal: "Benyou Wang"
issued:
  date-parts:
    - [2026, 6, 1]
url: "https://arxiv.org/abs/2606.02117"

# Custom fields
paper_id: "2606.02117"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "probres"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-02T05:41:22Z"
created_at: "2026-06-02T05:41:22Z"
---

# ProbRes: Volatility Learning for Probabilistic Time-Series Forecasting

**Authors**: Tingting Wang, Yunyi Zhang, Benyou Wang
**Date**: 2026-06-01
**Paper ID**: [arxiv:2606.02117](https://arxiv.org/abs/2606.02117)

## Summary

ProbRes is a post-hoc calibration method designed to enhance probabilistic time-series forecasting by explicitly modeling conditional volatility. Unlike standard methods that assume homoskedastic noise, ProbRes uses two separate modules to decouple the conditional mean and volatility, enabling robust handling of complex, heteroskedastic data. By resampling normalized residuals at inference, the framework produces well-calibrated prediction intervals applicable to both univariate and multivariate settings, even under non-Gaussian error conditions.

## Key Contributions

- Introduces ProbRes, an architecture-agnostic post-hoc calibration framework that explicitly models volatility dynamics to handle heteroskedasticity.
- Enables the generation of robust predictive distributions by resampling normalized residuals, effectively addressing non-Gaussian innovations.
- Provides theoretical validity for the proposed calibration method and demonstrates superior performance in capturing well-calibrated prediction intervals on synthetic and real-world benchmarks.

## Key Concepts

- [[probres]]: A post-hoc probabilistic calibration method that incorporates learned volatility dynamics to improve prediction interval accuracy for heteroskedastic time-series.

## Archivist Review

I approved ProbRes as a standalone concept because it provides a specific, architecture-agnostic post-hoc calibration mechanism for heteroskedastic time-series forecasting. Other potential candidates were either generic tasks or redundant. The review applied a conservative standard for what constitutes a reusable methodology versus standard statistical practice.

### Approved Concepts
- ProbRes: It introduces a novel architecture-agnostic post-hoc calibration approach specifically designed to incorporate volatility dynamics for improved uncertainty quantification in time-series.

### Rejected Candidates
- [concept] Volatility dynamics modeling (`volatility-dynamics-modeling`) - generic: This is a general task in time series analysis rather than a novel method/contribution.

## Links

- [Abstract](https://arxiv.org/abs/2606.02117)
- [PDF](https://arxiv.org/pdf/2606.02117)

