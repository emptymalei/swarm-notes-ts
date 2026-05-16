---
# CSL-compatible fields
title: "Training ML Models with Predictable Failures"
author:
  - literal: "Will Schwarzer"
  - literal: "Scott Niekum"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.15134"

# Custom fields
paper_id: "2605.15134"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "safety"
  - "reliability"
  - "evaluation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "forecastability-loss"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-16T05:10:47Z"
created_at: "2026-05-16T05:10:47Z"
---

# Training ML Models with Predictable Failures

**Authors**: Will Schwarzer, Scott Niekum
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15134](https://arxiv.org/abs/2605.15134)

## Summary

This paper addresses the challenge of predicting ML model failure rates at deployment scale, where rare but critical failure modes are often missing from evaluation sets. The authors decompose the forecast error of existing extrapolation methods, revealing a systematic bias that can lead to dangerous under-predictions when rare events are omitted. To mitigate this, they propose a fine-tuning objective called the forecastability loss, which improves the model's consistency with failure rate projections. Experiments in language and reinforcement learning domains confirm that the objective effectively reduces forecast error without sacrificing primary task capability.

## Key Contributions

- Formalized the finite-k decomposition of existing failure rate estimators to quantify forecast error and bias.
- Identified that current extrapolation methods under-predict deployment failure rates when rare failure modes are absent from the evaluation set.
- Introduced the forecastability loss objective, demonstrating reduced held-out forecast error on a language-model password game and an RL gridworld while maintaining task performance.

## Open Questions & Future Work

- [[failure-tail-forecastability-scaling]]

## Key Concepts

- [[forecastability-loss]]: A fine-tuning objective that optimizes a model for consistency with extreme-value failure rate projections to improve safety at deployment scale.

## Archivist Review

I approved the forecastability loss concept as it provides a distinct, reusable architectural training technique for safety-critical forecasting. I approved the failure-tail scalability question because it identifies a fundamental bottleneck in the long-term reliability of safety evaluation methods. The second open question was rejected as it was framed primarily as a request for more scaling and domain-specific experiments.

### Approved Concepts
- Forecastability Loss: It addresses a critical safety gap in model failure rate estimation by aligning training with extrapolation reliability.

### Approved Open Questions
- Failure-tail forecastability scaling: This question is central to the future scalability and validity of current model safety assessment methodologies.

## Links

- [Abstract](https://arxiv.org/abs/2605.15134)
- [PDF](https://arxiv.org/pdf/2605.15134)

