---
# CSL-compatible fields
title: "Simulation and Analysis of Multifractional Stochastic Processes with R Package Rmfrac"
author:
  - literal: "Andriy Olenko"
  - literal: "Nemini Samarakoon"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.01580"

# Custom fields
paper_id: "2604.01580"
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
processed_at: "2026-04-03T05:20:21Z"
created_at: "2026-04-03T05:20:21Z"
---

# Simulation and Analysis of Multifractional Stochastic Processes with R Package Rmfrac

**Authors**: Andriy Olenko, Nemini Samarakoon
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.01580](https://arxiv.org/abs/2604.01580)

## Summary

This paper introduces the Rmfrac R package, a comprehensive toolkit for simulating and analyzing multifractional stochastic processes. These models extend classical fractional Brownian motion by enabling time-varying regularity through Gaussian Haar-wavelet representations. The package includes robust estimation techniques for Hurst functions and local fractal dimensions, alongside advanced visualization and geometric analysis tools to support applications in fields like finance and network traffic analysis.

## Key Contributions

- Introduces the Rmfrac R package for simulation and analysis of multifractional stochastic processes based on Gaussian Haar-wavelet representations.
- Implements estimation tools for time-varying Hurst functions and local fractal dimensions in non-stationary time series.
- Provides functionality for clustering and computing geometric statistics of multifractional realizations to aid in real-world time series modeling.

## Open Questions & Future Work

- [[multidimensional-multifractional-processes-extension]]
- [[robust-inference-hurst-estimators]]

## Archivist Review

I approved two open questions concerning the advancement of multifractional process theory (extending to multidimensional domains and formalizing statistical inference for Hurst estimators), as these represent substantial research challenges in time-series modeling. I rejected the concept candidate for the R package itself as it is a software tool/library rather than a fundamental scientific concept. I renamed the open questions for better clarity and alignment with vault naming conventions.

### Approved Open Questions
- Multidimensional Multifractional Processes Extension: Expanding from 1D time series to 2D/3D random fields is a critical bottleneck for applying multifractional models to spatial, image, or terrain data.
- Robust Inference for Hurst Estimators: The absence of formal statistical testing and confidence interval estimation limits the ability to draw rigorous conclusions about the time-varying roughness of observed processes in practical applications.

### Rejected Candidates
- [open_question] Generalization to Multidimensional Processes (`multidimensional-multifractional-processes`) - duplicate_existing: Renamed for consistency and clarity in the vault.
- [open_question] Inference for Hurst Estimates (`statistical-inference-hurst-estimates`) - duplicate_existing: Renamed for clarity and uniqueness in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.01580)
- [PDF](https://arxiv.org/pdf/2604.01580)

