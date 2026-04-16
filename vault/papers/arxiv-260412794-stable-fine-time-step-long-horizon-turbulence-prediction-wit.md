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
  - "time-series"
  - "forecasting"
  - "physics-informed-machine-learning"
architectures:
  - "IFactFormer"
datasets:
  []
concept_slugs:
  - "multi-stepsize-mixture-of-experts-ms-moe"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:07:58Z"
created_at: "2026-04-16T05:07:58Z"
---

# Stable Fine-Time-Step Long-Horizon Turbulence Prediction with a Multi-Stepsize Mixture-of-Experts Neural Operator

**Authors**: Guanyu Pan, Huiyu Yang, Yunpeng Wang, Zikun Xu, Jianchun Wang, Nianyu Yi
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12794](https://arxiv.org/abs/2604.12794)

## Summary

This paper addresses the instability and error accumulation challenges inherent in fine-grained, long-horizon autoregressive turbulence prediction. The authors introduce the Ms-MoE-IFactFormer, a neural operator architecture that utilizes a time-step router to conditionally activate scale-specific experts based on the requested temporal stride. By training on datasets with significantly finer resolution than prior benchmarks, the model achieves more stable long-time rollouts and improved statistical convergence in forced isotropic turbulence and channel flows.

## Key Contributions

- Introduces Ms-MoE, a mixture-of-experts neural operator that dynamically routes time-steps to scale-specific experts for stable long-horizon turbulence prediction.
- Achieves stable autoregressive rollouts at 20 times finer temporal resolution than previous baseline models.
- Demonstrates superior agreement with long-time-averaged statistics on HIT and turbulent channel flow datasets.

## Open Questions & Future Work

- [[compositional-consistency-objectives]]

## Key Concepts

- [[multi-stepsize-mixture-of-experts-ms-moe]]: A neural operator architecture that uses a time-step router to select scale-specific experts, enabling stable fine-time-step turbulence forecasting.

## Archivist Review

I approved the Ms-MoE architecture as it presents a novel, reusable mechanism for addressing the temporal stride sensitivity in long-horizon forecasting. The open question on compositional consistency is also approved for its relevance to fundamental stability in neural operator surrogates. Other candidates were rejected for being generic implementation tuning (routing budgets) or lack of novelty.

### Approved Concepts
- Multi-stepsize Mixture-of-Experts (Ms-MoE): It enables a single neural operator architecture to perform stable long-horizon autoregressive predictions across multiple temporal resolutions by routing between scale-specific experts, addressing the instability of autoregressive error accumulation.

### Approved Open Questions
- Compositional Consistency Objectives: Compositional consistency is a theoretical property of exact flow maps; enforcing it during training is a promising avenue to reduce error accumulation and improve long-term physical fidelity in neural PDE surrogates.

### Rejected Candidates
- [open_question] MoE Routing Budget Tradeoffs (`moe-routing-budget-tradeoffs`) - generic: This is a standard implementation tuning concern for MoE models, rather than a fundamental scientific bottleneck in time-series forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2604.12794)
- [PDF](https://arxiv.org/pdf/2604.12794)

