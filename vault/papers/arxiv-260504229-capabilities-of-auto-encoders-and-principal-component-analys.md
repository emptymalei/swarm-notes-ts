---
# CSL-compatible fields
title: "Capabilities of Auto-encoders and Principal Component Analysis of the Reduction of Microstructural Images; Application on the Acceleration of Phase-Field Simulations"
author:
  - literal: "Seifallah Fetni"
  - literal: "Thinh Quy Duc Pham"
  - literal: "Truong Vinh Hoang"
  - literal: "Hoang Son Tran"
  - literal: "Laurent Duchêne"
  - literal: "Xuan-Van Tran"
  - literal: "Anne Marie Habraken"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.04229"

# Custom fields
paper_id: "2605.04229"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "time-series"
  - "dimensionality-reduction"
  - "physical-simulation"
  - "surrogate-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "fno-phase-field-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:16:40Z"
created_at: "2026-05-07T05:16:40Z"
---

# Capabilities of Auto-encoders and Principal Component Analysis of the Reduction of Microstructural Images; Application on the Acceleration of Phase-Field Simulations

**Authors**: Seifallah Fetni, Thinh Quy Duc Pham, Truong Vinh Hoang, Hoang Son Tran, Laurent Duchêne, Xuan-Van Tran, Anne Marie Habraken
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.04229](https://arxiv.org/abs/2605.04229)

## Summary

This paper introduces a data-driven framework to accelerate high-fidelity phase-field simulations of microstructural evolution. By employing auto-encoders and PCA for latent dimensionality reduction, the approach achieves a significant 1/196 reduction ratio. Long Short Term Memory (LSTM) networks are then applied to the latent space to forecast subsequent simulation states, effectively bypassing the need for computationally expensive full-field solvers.

## Key Contributions

- Proposes a data-driven framework combining auto-encoders and PCA for a 1/196 dimensionality reduction ratio in microstructural images with over 80% accuracy.
- Demonstrates that LSTM networks can predict future states in the latent space, enabling the acceleration of phase-field simulations.
- Provides a comparative analysis of dimensionality reduction and time-series methods, including AE, PCA, LSTM, and GRU, for physical simulation acceleration.

## Open Questions & Future Work

- [[long-term-microstructure-forecasting-challenges]]

## Key Concepts

- [[fno-phase-field-forecasting]]: Accelerating phase-field simulations through latent space dimensionality reduction and neural temporal forecasting.

## Archivist Review

I approved the concept 'fno-phase-field-forecasting' as it effectively captures the surrogate-modeling approach described, mapping it to an existing vault concept. The open question 'long-term-microstructure-forecasting-challenges' was approved for highlighting the specific failure mode of error accumulation in latent physical surrogate models. No datasets were approved as the simulation data is proprietary and not a canonical benchmark.

### Approved Concepts
- fno-phase-field-forecasting: This framework addresses the computational bottleneck of high-fidelity physical simulations through latent-space surrogate modeling.

### Approved Open Questions
- Challenges in Long-term Forecasting: The bottleneck of long-term predictive accuracy in surrogate models prevents their full adoption as replacements for computationally intensive high-fidelity physical simulations, particularly for applications like microstructure evolution and crack propagation.

## Links

- [Abstract](https://arxiv.org/abs/2605.04229)
- [PDF](https://arxiv.org/pdf/2605.04229)

