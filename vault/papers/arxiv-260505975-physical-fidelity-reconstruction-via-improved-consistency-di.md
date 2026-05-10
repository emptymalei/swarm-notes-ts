---
# CSL-compatible fields
title: "Physical Fidelity Reconstruction via Improved Consistency-Distilled Flow Matching for Dynamical Systems"
author:
  - literal: "Sicheng Ma"
  - literal: "Tianyue Yang"
  - literal: "Xiuzhe Wu"
  - literal: "Xiao Xue"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05975"

# Custom fields
paper_id: "2605.05975"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "generative-modeling"
  - "scientific-machine-learning"
  - "flow-matching"
  - "distillation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "consistency-distilled-flow-matching"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:19:37Z"
created_at: "2026-05-10T05:19:37Z"
---

# Physical Fidelity Reconstruction via Improved Consistency-Distilled Flow Matching for Dynamical Systems

**Authors**: Sicheng Ma, Tianyue Yang, Xiuzhe Wu, Xiao Xue
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05975](https://arxiv.org/abs/2605.05975)

## Summary

This paper addresses the computational latency of iterative sampling in high-fidelity flow reconstruction by distilling optimal-transport flow-matching models into compact, one-step consistency models. By initializing generative trajectories from noised low-fidelity observations, the proposed method enables conditional reconstruction without requiring the retraining of the underlying generative model. Experimental results on smoke buoyancy, turbulent channel flow, and Kolmogorov flow benchmarks demonstrate significant inference speedups and superior reconstruction quality compared to models trained from scratch.

## Key Contributions

- Introduces a distillation framework that compresses an optimal-transport flow-matching teacher model into a high-fidelity, one-step consistency model for scientific flow reconstruction.
- Demonstrates that the distilled student model achieves a 12x inference speedup over the teacher while maintaining comparable spectral accuracy on 256x256 fluid field benchmarks.
- Shows that teacher-led distillation yields a 23.1% improvement in SSIM over consistency models trained from scratch, establishing it as an efficient training paradigm for scientific generative models.

## Open Questions & Future Work

- [[one-step-physical-reconstruction-scaling]]

## Key Concepts

- [[consistency-distilled-flow-matching]]: A technique that compresses an optimal-transport flow-matching model into a one-step consistency model for rapid, high-fidelity scientific data reconstruction.

## Archivist Review

I approved the core concept of consistency distillation as a mechanism for scientific model compression and the associated open question regarding the scalability of such approaches to complex, non-stationary scientific fields. The identified fluid dynamics benchmarks were rejected as they are domain-specific testbeds rather than reusable, archival-grade datasets.

### Approved Concepts
- Consistency-Distilled Flow Matching: This method addresses the latency bottleneck of iterative sampling in scientific flow reconstruction by enabling one-step generation while maintaining high spectral fidelity.

### Approved Open Questions
- Scalability of One-Step Reconstruction: This direction is critical for determining the scalability of one-step generative models to the complex, high-dimensional, and non-stationary conditions frequently encountered in practical scientific simulation and ensemble forecasting workflows.

## Links

- [Abstract](https://arxiv.org/abs/2605.05975)
- [PDF](https://arxiv.org/pdf/2605.05975)

