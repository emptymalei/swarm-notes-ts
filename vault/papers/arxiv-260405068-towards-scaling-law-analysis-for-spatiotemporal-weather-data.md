---
# CSL-compatible fields
title: "Towards Scaling Law Analysis For Spatiotemporal Weather Data"
author:
  - literal: "Alexander Kiefer"
  - literal: "Prasanna Balaprakash"
  - literal: "Xiao Wang"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.05068"

# Custom fields
paper_id: "2604.05068"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "train-to-test-scaling-laws"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:57:56Z"
created_at: "2026-04-08T04:57:56Z"
---

# Towards Scaling Law Analysis For Spatiotemporal Weather Data

**Authors**: Alexander Kiefer, Prasanna Balaprakash, Xiao Wang
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.05068](https://arxiv.org/abs/2604.05068)

## Summary

This paper addresses the gap in scaling law analysis for autoregressive weather forecasting by moving beyond single-step training objectives. The authors investigate how prediction error evolves across different forecast horizons and physical channels, revealing significant heterogeneity that is often obscured by global test metrics. They establish a framework to analyze scaling behaviors jointly across parameters, data, compute, horizon, and output channels, providing insights into the limitations of current model training strategies.

## Key Contributions

- Extends neural scaling analysis frameworks to account for autoregressive error accumulation and long-horizon forecast degradation.
- Demonstrates that global test metrics mask critical cross-channel performance decay in autoregressive weather models.
- Quantifies joint power law scaling dependencies for parameter, data, and compute-based axes across varying forecast horizons and physical channels.

## Open Questions & Future Work

- [[scaling-laws-for-probabilistic-weather-emulation]]

## Key Concepts

- [[train-to-test-scaling-laws]]: An extension of compute-optimal scaling analysis to account for autoregressive rollout errors and heterogeneous channel metrics in spatiotemporal weather forecasting.

## Archivist Review

I approved the concept of 'train-to-test-scaling-laws' as it addresses a critical shift in how we analyze scaling in spatiotemporal settings, and defined an open question concerning the scaling laws for probabilistic weather emulation. The review process was selective, focusing on frameworks that move beyond standard single-step evaluation and identifying specific gaps in the theoretical scaling of autoregressive models. Other candidates were deemed duplicative or overly specific to the paper's current scope.

### Approved Concepts
- train-to-test-scaling-laws: The paper provides a necessary extension of classical neural scaling laws to the complex, multi-modal, and long-horizon setting of weather forecasting.

### Approved Open Questions
- Scaling Laws for Probabilistic Weather Emulation: This is essential because the current findings are conditioned on a specific model family and deterministic objective, and verifying whether these insights hold at larger scales and with more advanced probabilistic methods is critical for the long-term reliability of neural surrogates.

## Links

- [Abstract](https://arxiv.org/abs/2604.05068)
- [PDF](https://arxiv.org/pdf/2604.05068)

