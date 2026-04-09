---
# CSL-compatible fields
title: "Physics-Informed 3D Atomic Reconstruction and Dynamics of Free-Standing Graphene from Single Low-Dose TEM Images"
author:
  - literal: "Xiaojun Zhang"
  - literal: "Shih-Wei Hung"
  - literal: "Yawei Wu"
  - literal: "Jyh-Pin Chou"
  - literal: "Angus I. Kirkland"
  - literal: "Roar Kilaas"
  - literal: "Fu-Rong Chen"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07271"

# Custom fields
paper_id: "2604.07271"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "physics-informed-atomic-reconstruction"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:53:11Z"
created_at: "2026-04-09T04:53:11Z"
---

# Physics-Informed 3D Atomic Reconstruction and Dynamics of Free-Standing Graphene from Single Low-Dose TEM Images

**Authors**: Xiaojun Zhang, Shih-Wei Hung, Yawei Wu, Jyh-Pin Chou, Angus I. Kirkland, Roar Kilaas, Fu-Rong Chen
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07271](https://arxiv.org/abs/2604.07271)

## Summary

This paper presents a physics-informed computational framework for reconstructing the 3D atomic coordinates of free-standing graphene from single, low-dose transmission electron microscopy (TEM) frames. By integrating simulated annealing with molecular dynamics regularization, the method overcomes extreme signal-to-noise limitations imposed by radiation-sensitive imaging. The framework enables real-time extraction of mechanical and electronic properties, revealing how sub-angstrom structural fluctuations drive localized electronic modulations in 2D materials.

## Key Contributions

- Introduces a physics-informed framework that reconstructs 3D atomic coordinates of single-layer graphene from individual low-dose TEM frames (8x10^3 e-/Ang^2).
- Achieves sub-angstrom out-of-plane accuracy (sigma_z < 0.45 Ang) by regularizing the reconstruction with molecular dynamics simulations.
- Quantifies the causal link between sub-angstrom geometric fluctuations and millisecond-scale electronic modulation, verified via DFT-derived electron localization functions.

## Open Questions & Future Work

- [[fast-inference-for-3d-atomic-reconstruction]]

## Key Concepts

- [[physics-informed-atomic-reconstruction]]: A computational framework for 3D atomic coordinate reconstruction that integrates simulated annealing with molecular dynamics regularization to overcome low-dose signal constraints.

## Archivist Review

I have approved the core concept of physics-informed atomic reconstruction as it provides a robust methodology for solving ill-posed inverse problems in microscopy, and I have included an open question regarding the computational efficiency of these methods, which is a common bottleneck in physical science applications. No datasets were approved as none were clearly identified as distinct, reusable benchmarks.

### Approved Concepts
- Physics-Informed Atomic Reconstruction: Addresses the fundamental challenge of reconstructing 3D structures from low-dose, high-noise transmission electron microscopy data by incorporating physics-based regularization.

### Approved Open Questions
- Accelerating 3D Atomic Reconstruction Inference: Computational efficiency is the primary bottleneck for scaling this 3D reconstruction approach to large-field-of-view dynamic studies or high-throughput material characterization tasks.

## Links

- [Abstract](https://arxiv.org/abs/2604.07271)
- [PDF](https://arxiv.org/pdf/2604.07271)

