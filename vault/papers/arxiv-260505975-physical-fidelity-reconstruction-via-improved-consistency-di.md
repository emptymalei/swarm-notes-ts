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
domain: "time-series"
tags:
  - "forecasting"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "consistency-distilled-flow-matching"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:11:31Z"
created_at: "2026-05-09T05:11:31Z"
---

# Physical Fidelity Reconstruction via Improved Consistency-Distilled Flow Matching for Dynamical Systems

**Authors**: Sicheng Ma, Tianyue Yang, Xiuzhe Wu, Xiao Xue
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05975](https://arxiv.org/abs/2605.05975)

## Summary

The paper proposes a distillation approach to compress optimal-transport flow-matching models into one-step consistency models for high-fidelity scientific flow reconstruction. By initializing the generative process from noised low-fidelity observations, the model enables conditional reconstruction without the need for retraining the teacher. Evaluated on fluid dynamics benchmarks, the method achieves significant inference speedups and superior reconstruction quality compared to models trained from scratch. This approach offers an efficient path for deploying high-capacity generative models in latency-sensitive scientific applications.

## Key Contributions

- Introduces a distillation strategy that converts optimal-transport flow-matching models into one-step consistency models for scientific flow reconstruction.
- Achieves a 12x inference speedup and 50% parameter reduction compared to the flow-matching teacher while maintaining competitive spectral fidelity.
- Demonstrates a 23.1% improvement in SSIM over direct consistency model training by leveraging teacher distillation for enhanced training efficiency.

## Open Questions & Future Work

- [[adaptive-noising-schedules-for-distillation]]

## Key Concepts

- [[consistency-distilled-flow-matching]]: A distillation approach that converts optimal-transport flow-matching models into one-step consistency models to enable high-fidelity scientific flow reconstruction.

## Archivist Review

I approved the core concept of distilling flow-matching into consistency models as it provides a distinct, reusable methodology for high-fidelity, low-latency scientific simulation. I also approved the open question regarding adaptive noising, as it highlights a specific technical bottleneck in the spectral accuracy of one-step distillation that is relevant across scientific machine learning. Datasets were rejected because the fluid dynamics benchmarks mentioned are general problem types rather than standard, fixed datasets.

### Approved Concepts
- Consistency-Distilled Flow Matching: It provides a novel method for compressing computationally expensive iterative scientific generative models (flow matching) into real-time one-step models, essential for simulation-in-the-loop and latency-sensitive scientific applications.

### Approved Open Questions
- Adaptive Noising for Distillation: This addresses a fundamental limitation in the current deployment of one-step models for high-fidelity scientific applications where spectral accuracy is as important as latency.

### Rejected Candidates
- [concept] Improved Consistency-Distilled Flow Matching (`improved-consistency-distilled-flow-matching`) - other: Renamed to be more canonical by removing the 'Improved' prefix.
- [dataset] Smoke Buoyancy (`smoke-buoyancy`) - not_reusable: Generic simulation environments or specific instances of standard fluid benchmarks are not sufficiently unique for individual datasets in the vault.
- [dataset] Turbulent Channel Flow (`turbulent-channel-flow`) - not_reusable: This is a standard fluid dynamics problem setup rather than a specific, cited benchmark dataset with permanent utility.

## Links

- [Abstract](https://arxiv.org/abs/2605.05975)
- [PDF](https://arxiv.org/pdf/2605.05975)

