---
# CSL-compatible fields
title: "Trajectory-Agnostic Asteroid Detection in TESS with Deep Learning"
author:
  - literal: "Brian P. Powell"
  - literal: "Jorge Martinez-Palomera"
  - literal: "Amy Tuson"
  - literal: "Christina Hedges"
  - literal: "Jessie Dotson"
  - literal: "Jordan Caraballo-Vega"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12391"

# Custom fields
paper_id: "2605.12391"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "w-net"
  - "adaptive-normalization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:22:59Z"
created_at: "2026-05-13T05:22:59Z"
---

# Trajectory-Agnostic Asteroid Detection in TESS with Deep Learning

**Authors**: Brian P. Powell, Jorge Martinez-Palomera, Amy Tuson, Christina Hedges, Jessie Dotson, Jordan Caraballo-Vega
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12391](https://arxiv.org/abs/2605.12391)

## Summary

This paper introduces a trajectory-agnostic deep learning approach for detecting asteroids in TESS time-series imagery without the limitations of traditional shift-and-stack algorithms. The method utilizes a W-Net architecture, consisting of stacked 3D U-Nets, and incorporates a novel Adaptive Normalization technique to learn optimal data scaling parameters. The authors also provide a publicly available framework, tess-asteroid-ml, for generating training masks, ensuring the approach is applicable to future missions like the Roman Space Telescope.

## Key Contributions

- Introduced W-Net, a stacked 3D U-Net architecture for trajectory-agnostic moving object detection in time-series imagery.
- Developed Adaptive Normalization, a learned data scaling technique that enhances model robustness to varying input intensities.
- Released tess-asteroid-ml, an open-source dataset creation framework for training asteroid detection models in TESS data.

## Open Questions & Future Work

- [[mitigating-label-noise-in-asteroid-ml]]

## Key Concepts

- [[w-net]]: A stacked 3D U-Net architecture designed for spatiotemporal background filtering and object detection.
- [[adaptive-normalization]]: A learned data scaling technique that allows neural networks to determine the optimal input distribution for processing.

## Archivist Review

I approved W-Net and Adaptive Normalization as they are novel, reusable mechanisms for spatiotemporal data processing. I approved the open question regarding label noise because it is a fundamental, well-defined bottleneck in astronomical supervised learning that persists across survey missions. The dataset creation framework was rejected as it is a project-specific tool rather than a reusable dataset itself.

### Approved Concepts
- W-Net: The architecture provides a robust, trajectory-agnostic pattern for spatiotemporal segmentation in time-series image cubes.
- Adaptive Normalization: It allows the neural network to learn the optimal scaling distribution rather than relying on manual, fixed, or heuristic normalization.

### Approved Open Questions
- Mitigating Training Label Noise: Label incompleteness is a foundational problem for supervised learning in astronomy and time-domain surveys, directly affecting the scalability and accuracy of future detection pipelines.

## Links

- [Abstract](https://arxiv.org/abs/2605.12391)
- [PDF](https://arxiv.org/pdf/2605.12391)

