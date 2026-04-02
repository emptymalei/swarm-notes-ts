---
# CSL-compatible fields
title: "Hybrid Quantum-Classical Spatiotemporal Forecasting for 3D Cloud Fields"
author:
  - literal: "Fu Wang"
  - literal: "Qifeng Lu"
  - literal: "Xinyu Long"
  - literal: "Meng Zhang"
  - literal: "Xiaofei Yang"
  - literal: "Weijia Cao"
  - literal: "Xiaowen Chu"
issued:
  date-parts:
    - [2026, 3, 31]
url: "https://arxiv.org/abs/2603.29407"

# Custom fields
paper_id: "2603.29407"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "spatiotemporal-forecasting"
  - "quantum-inspired-learning"
architectures:
  []
datasets:
  - "CMA-MESO"
concept_slugs:
  - "topology-aware-quantum-enhancement-block"
dataset_slugs:
  - "cma-meso"
skill: "TimeSeriesSkill"
processed_at: "2026-04-02T05:40:46Z"
created_at: "2026-04-02T05:40:46Z"
---

# Hybrid Quantum-Classical Spatiotemporal Forecasting for 3D Cloud Fields

**Authors**: Fu Wang, Qifeng Lu, Xinyu Long, Meng Zhang, Xiaofei Yang, Weijia Cao, Xiaowen Chu
**Date**: 2026-03-31
**Paper ID**: [arxiv:2603.29407](https://arxiv.org/abs/2603.29407)

## Summary

QENO is a hybrid quantum-inspired spatiotemporal forecasting framework designed to capture nonlocal dependencies and fine 3D structures in atmospheric cloud fields. The architecture integrates a classical encoder with a topology-aware quantum enhancement block and a dynamic fusion temporal unit to balance feature extraction with long-range dependency modeling. Evaluated on the CMA-MESO dataset, the model demonstrates superior performance over standard convolutional and attention-based baselines in both structural and pixel-level accuracy.

## Key Contributions

- Introduces QENO, a hybrid quantum-classical architecture designed for high-fidelity 3D cloud field forecasting.
- Proposes a topology-aware quantum enhancement block to explicitly model nonlocal couplings and multiscale spatiotemporal dynamics.
- Outperforms state-of-the-art spatiotemporal models (ConvLSTM, Earthformer, SimVP) on the CMA-MESO dataset across MSE, MAE, and SSIM metrics.

## Open Questions & Future Work

- [[quantum-computational-overhead-scalability]]

## Key Concepts

- [[topology-aware-quantum-enhancement-block]]: A architectural component that leverages quantum-inspired topological modeling to capture complex nonlocal interactions within latent space for spatiotemporal prediction.

## Archivist Review

The submission introduces a novel architectural concept for capturing non-local dependencies in spatiotemporal tasks, which is highly relevant to current forecasting research. I have approved the 'Topology-aware Quantum Enhancement Block' as a reusable architectural pattern and 'CMA-MESO' as a relevant dataset for high-dimensional atmospheric forecasting. The open question regarding quantum module overhead is a critical, well-defined scalability challenge that justifies a permanent entry.

### Approved Concepts
- Topology-aware Quantum Enhancement Block: Central to addressing nonlocal dependencies and fine structure preservation in 3D spatiotemporal forecasting by explicitly modeling latent-space couplings.

### Approved Open Questions
- Scaling Quantum-Inspired Module Overhead: This is a primary bottleneck for deploying quantum-inspired models in operational environments requiring high-throughput inference.

## Datasets

- [[cma-meso]]

## Links

- [Abstract](https://arxiv.org/abs/2603.29407)
- [PDF](https://arxiv.org/pdf/2603.29407)

