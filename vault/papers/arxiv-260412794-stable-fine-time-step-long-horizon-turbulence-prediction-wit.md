---
# CSL-compatible fields
title: "Stable Fine-Time-Step Long-Horizon Turbulence Prediction with a Multi-Stepsize Mixture-of-Experts Neural Operator"
author:
  - literal: "Guanyu Pan"
  - literal: "Huiyu Yang"
  - literal: "Yunpeng Wang"
  - literal: "Zikun Xu"
  - literal: "Jianchun Wang"
  - literal: "Nianyu Yi"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12794"

# Custom fields
paper_id: "2604.12794"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "neural-operator"
  - "turbulence-prediction"
  - "mixture-of-experts"
architectures:
  []
datasets:
  []
concept_slugs:
  - "ms-moe"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:03:12Z"
created_at: "2026-04-15T05:03:12Z"
---

# Stable Fine-Time-Step Long-Horizon Turbulence Prediction with a Multi-Stepsize Mixture-of-Experts Neural Operator

**Authors**: Guanyu Pan, Huiyu Yang, Yunpeng Wang, Zikun Xu, Jianchun Wang, Nianyu Yi
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12794](https://arxiv.org/abs/2604.12794)

## Summary

The paper addresses the stability issues in autoregressive turbulence forecasting caused by error accumulation at fine temporal resolutions. The authors propose the Multi-stepsize Mixture-of-Experts (Ms-MoE) neural operator, built on an Implicit Factorized Transformer, to learn a family of stride-parameterized operators. This approach enables stable long-horizon rollouts by conditioning on time strides and employing a router to activate task-specific experts. Evaluation on forced homogeneous isotropic turbulence and turbulent channel flow demonstrates superior stability and adherence to long-time-averaged physical statistics.

## Key Contributions

- Proposes Ms-MoE, a neural operator architecture that enables stable long-horizon autoregressive forecasting at fine temporal resolutions by conditioning on relative time strides.
- Introduces a time-step router mechanism that dynamically activates scale-specific and shared experts, effectively parameterizing time-advancement operators.
- Demonstrates improved stability and accuracy in long-time-averaged statistics for forced homogeneous isotropic turbulence and turbulent channel flow, evaluated at temporal resolutions 20 times finer than typical benchmarks.

## Open Questions & Future Work

- [[compositional-consistency-in-neural-operators]]

## Key Concepts

- [[ms-moe]]: A mixture-of-experts neural operator architecture that uses a time-step router to select scale-specific experts for stable, fine-resolution temporal forecasting.

## Archivist Review

I approved the Ms-MoE architecture as a novel approach to stride-aware forecasting in neural operators and added an open question regarding formal compositional consistency, which addresses a fundamental limitation in current autoregressive physical modeling. I rejected the IFactFormer backbone mention as it is a local architectural implementation detail rather than a distinct, reusable paradigm.

### Approved Concepts
- Multi-stepsize Mixture-of-Experts (Ms-MoE): This architectural innovation addresses the common instability of fine-resolution autoregressive forecasting by routing computations based on the requested time stride.

### Approved Open Questions
- Compositional consistency in operators: Ensuring formal compositional consistency is a critical theoretical hurdle for reliable, long-horizon autoregressive physical simulators that must function at arbitrary temporal resolutions.

## Links

- [Abstract](https://arxiv.org/abs/2604.12794)
- [PDF](https://arxiv.org/pdf/2604.12794)

