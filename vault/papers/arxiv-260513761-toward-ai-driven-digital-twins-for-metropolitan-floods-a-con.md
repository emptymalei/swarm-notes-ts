---
# CSL-compatible fields
title: "Toward AI-Driven Digital Twins for Metropolitan Floods: A Conditional Latent Dynamics Network Surrogate of the Shallow Water Equations"
author:
  - literal: "Phillip Si"
  - literal: "Yuan Qiu"
  - literal: "Omar Sallam"
  - literal: "Jeremy Feinstein"
  - literal: "Ziang He"
  - literal: "Eugene Yan"
  - literal: "Peng Chen"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13761"

# Custom fields
paper_id: "2605.13761"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-gaussian-chain-graph-models"
  - "physics-informed-lstm-pi-lstm"
architectures:
  []
datasets:
  []
concept_slugs:
  - "conditional-latent-dynamics-network-cldnet"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:22:48Z"
created_at: "2026-05-14T05:22:48Z"
---

# Toward AI-Driven Digital Twins for Metropolitan Floods: A Conditional Latent Dynamics Network Surrogate of the Shallow Water Equations

**Authors**: Phillip Si, Yuan Qiu, Omar Sallam, Jeremy Feinstein, Ziang He, Eugene Yan, Peng Chen
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13761](https://arxiv.org/abs/2605.13761)

## Summary

The authors present the Conditional Latent Dynamics Network (CLDNet), a surrogate model designed to accelerate hydrodynamic shallow water equation (SWE) solvers for metropolitan flood forecasting. By utilizing a low-dimensional latent neural ODE conditioned on static terrain data, CLDNet reconstructs depth and discharge at arbitrary coordinates, bypassing the memory constraints of traditional grid-based methods. Experimental results on the Des Plaines River basin and a synthetic Texas benchmark demonstrate a 115x speedup over numerical solvers while maintaining superior accuracy compared to standard grid-based deep learning baselines.

## Key Contributions

- Introduces CLDNet, a latent neural ODE surrogate that accelerates hydrodynamic shallow water equation (SWE) simulation by ~115x compared to GPU-accelerated solvers.
- Enables metropolitan-scale flood forecasting on irregular watersheds without raster snapping by using a coordinate-based, terrain-conditioned decoder.
- Achieves a critical success index of ~86% at the 0.5m inundation threshold and outperforms conventional grid-based VAE-ConvLSTM and FNO models on complex flood benchmarks.

## Open Questions & Future Work

- [[real-time-data-assimilation-in-physical-surrogates]]

## Key Concepts

- [[conditional-latent-dynamics-network-cldnet]]: A low-dimensional latent neural ODE surrogate for physical simulation that uses coordinate-based, terrain-conditioned decoding to enable arbitrary point queries in irregular domains.

## Archivist Review

I approved the Conditional Latent Dynamics Network (CLDNet) as a representative concept for meshless, coordinate-based physical surrogates and one open question regarding real-time data assimilation. The discharge prediction accuracy issue was rejected as it is a specific performance gap rather than a foundational research direction. I did not include the Des Plaines River basin as a dataset, as it is a specific case study rather than a reusable benchmark dataset.

### Approved Concepts
- Conditional Latent Dynamics Network (CLDNet): CLDNet offers a novel approach to physical system emulation that avoids the limitations of grid-based discretization, which is a common bottleneck in spatio-temporal forecasting and digital twin construction.

### Approved Open Questions
- Real-time data assimilation for digital twins: Bridging the gap between static surrogate modeling and adaptive forecasting systems is essential for turning laboratory emulators into field-ready operational tools.

### Rejected Candidates
- [open_question] Improving discharge prediction accuracy (`improving-discharge-prediction-in-surrogates`) - low_impact: While important, this is an application-specific accuracy bottleneck rather than a fundamental open question about system architecture or methodology.

## Links

- [Abstract](https://arxiv.org/abs/2605.13761)
- [PDF](https://arxiv.org/pdf/2605.13761)

