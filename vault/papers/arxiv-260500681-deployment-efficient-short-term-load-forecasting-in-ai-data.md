---
# CSL-compatible fields
title: "Deployment-Efficient Short-Term Load Forecasting in AI Data Centers via Sequence-to-Point Knowledge Distillation"
author:
  - literal: "Lei Wang"
  - literal: "Jiahao Chen"
  - literal: "Fanping Sui"
  - literal: "Ying Zhang"
  - literal: "Di Shi"
issued:
  date-parts:
    - [2026, 5, 1]
url: "https://arxiv.org/abs/2605.00681"

# Custom fields
paper_id: "2605.00681"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "mit-supercloud-dataset"
concept_slugs:
  - "sequence-to-point-knowledge-distillation"
dataset_slugs:
  - "mit-supercloud-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-04T05:14:59Z"
created_at: "2026-05-04T05:14:59Z"
---

# Deployment-Efficient Short-Term Load Forecasting in AI Data Centers via Sequence-to-Point Knowledge Distillation

**Authors**: Lei Wang, Jiahao Chen, Fanping Sui, Ying Zhang, Di Shi
**Date**: 2026-05-01
**Paper ID**: [arxiv:2605.00681](https://arxiv.org/abs/2605.00681)

## Summary

This paper introduces a sequence-to-point knowledge distillation framework to address the trade-off between forecasting accuracy and computational efficiency in AI data centers. By leveraging a high-capacity sequence teacher model and a compact point-wise student model, the approach effectively captures the non-stationary, bursty nature of load demands. The proposed distillation strategy facilitates the transfer of temporal knowledge, resulting in significantly lower latency and reduced model size without compromising predictive performance. Extensive evaluation on the MIT Supercloud dataset confirms that the framework outperforms existing deep learning baselines in both efficiency and accuracy.

## Key Contributions

- Proposes a knowledge distillation framework for short-term load forecasting in AI data centers that reconciles high forecasting accuracy with low deployment latency.
- Introduces a sequence-to-point distillation strategy that aligns teacher and student models via predictive behavior and temporally pooled representations.
- Achieves >10x reduction in parameter memory and model size compared to deep learning baselines while improving forecast accuracy on the MIT Supercloud dataset.

## Open Questions & Future Work

- [[integration-with-grid-coordination]]

## Key Concepts

- [[sequence-to-point-knowledge-distillation]]: A knowledge distillation method that transfers temporal information from a sequence teacher model to a lightweight point-wise student model for efficient load forecasting.

## Archivist Review

I approved the core knowledge distillation concept and the associated integration open question as they represent a reusable framework and a significant system-level research bottleneck. I also approved the MIT Supercloud dataset given its specific role in evaluating bursty AI data center power demand. Other components were deemed sub-components or too generic for standalone vault entry.

### Approved Concepts
- Sequence-to-point Knowledge Distillation: It addresses the critical accuracy-deployment tradeoff by transferring temporal patterns from complex sequence models to efficient point-wise models.

### Approved Open Questions
- Grid-Data Center Flexibility Coordination: This is a key domain-specific application area. Connecting low-level load forecasting to high-level grid flexibility and demand response is critical for the practical utility of these models in sustainable energy management.

## Datasets

- [[mit-supercloud-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2605.00681)
- [PDF](https://arxiv.org/pdf/2605.00681)

