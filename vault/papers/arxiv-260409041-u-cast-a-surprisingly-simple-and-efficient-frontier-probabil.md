---
# CSL-compatible fields
title: "U-Cast: A Surprisingly Simple and Efficient Frontier Probabilistic AI Weather Forecaster"
author:
  - literal: "Salva Rühling Cachay"
  - literal: "Duncan Watson-Parris"
  - literal: "Rose Yu"
issued:
  date-parts:
    - [2026, 4, 10]
url: "https://arxiv.org/abs/2604.09041"

# Custom fields
paper_id: "2604.09041"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "probabilistic-forecasting"
  - "weather-forecasting"
  - "efficiency"
  - "u-net"
architectures:
  []
datasets:
  []
concept_slugs:
  - "two-stage-probabilistic-fine-tuning-tpf"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-13T05:10:11Z"
created_at: "2026-04-13T05:10:11Z"
---

# U-Cast: A Surprisingly Simple and Efficient Frontier Probabilistic AI Weather Forecaster

**Authors**: Salva Rühling Cachay, Duncan Watson-Parris, Rose Yu
**Date**: 2026-04-10
**Paper ID**: [arxiv:2604.09041](https://arxiv.org/abs/2604.09041)

## Summary

U-Cast is an efficient, probabilistic AI weather forecasting framework that demonstrates state-of-the-art performance can be achieved using standard U-Net architectures. By employing a two-stage training strategy—deterministic pre-training with Mean Absolute Error followed by short-duration probabilistic fine-tuning using CRPS—the model matches the skill of complex ensembles like GenCast and IFS ENS. This approach drastically reduces the computational barriers for training frontier-level models, achieving significant improvements in both training efficiency and inference speed.

## Key Contributions

- Introduces U-Cast, a probabilistic weather forecaster based on a standard U-Net backbone that reaches SOTA-competitive performance.
- Achieves a >10x reduction in training compute and >10x improvement in inference latency compared to current diffusion-based probabilistic SOTA models.
- Validates that a simple, efficient training curriculum using deterministic pre-training and CRPS fine-tuning can outperform specialized complex architectures.

## Open Questions & Future Work

- [[autoregressive-stability-in-weather-emulation]]
- [[polar-artifact-mitigation-in-global-models]]

## Key Concepts

- [[two-stage-probabilistic-fine-tuning-tpf]]: A two-stage training strategy combining deterministic pre-training with CRPS-based probabilistic fine-tuning and Monte Carlo Dropout to achieve competitive probabilistic performance.

## Archivist Review

The paper provides a compelling argument for modular, efficient training curricula over architectural complexity. I have approved the two-stage training framework as a reusable concept and focused the open questions on the specific technical trade-offs of stability and geometry highlighted by the authors.

### Approved Concepts
- Two-stage Probabilistic Fine-tuning (TPF): Provides a generalized, compute-efficient framework for adapting standard deterministic architectures to probabilistic forecasting tasks without requiring complex generative backbones.

### Approved Open Questions
- Autoregressive Stability in Weather Emulation: Autoregressive stability is a central bottleneck in learned weather emulators; resolving this while maintaining efficiency is critical for long-range forecasting.
- Polar Artifact Mitigation in Global Models: Polar artifacts represent a persistent systematic failure mode that limits the physical fidelity of global forecasting models.

## Links

- [Abstract](https://arxiv.org/abs/2604.09041)
- [PDF](https://arxiv.org/pdf/2604.09041)

