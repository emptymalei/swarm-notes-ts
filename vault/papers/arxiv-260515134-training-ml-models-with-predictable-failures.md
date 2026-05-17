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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "forecastability-loss"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-17T05:22:27Z"
created_at: "2026-05-17T05:22:27Z"
---

# Training ML Models with Predictable Failures

**Authors**: Will Schwarzer, Scott Niekum
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15134](https://arxiv.org/abs/2605.15134)

## Summary

This paper analyzes the reliability of extrapolating deployment-scale failure rates from limited evaluation sets, identifying a systemic bias in existing methods. The authors prove that while these estimators typically err on the side of safety, they fail when the evaluation set misses rare high-failure modes. To mitigate this, they introduce the forecastability loss, a fine-tuning objective that improves the accuracy of failure rate predictions. Experiments in language modeling and reinforcement learning demonstrate that this approach reduces forecast error while maintaining task capability.

## Key Contributions

- Formulates a finite-k decomposition of existing extreme-value failure rate estimators to quantify bias toward safety-favorable over-prediction.
- Identifies a critical failure mode where missing rare, high-failure modes in small evaluation sets leads to under-prediction of deployment-scale failures.
- Introduces the 'forecastability loss' to optimize model training for more reliable failure rate prediction without sacrificing primary task performance.

## Open Questions & Future Work

- [[understanding-model-failure-tail-dependence]]
- [[composing-evt-importance-sampling]]

## Key Concepts

- [[forecastability-loss]]: A fine-tuning objective designed to reduce the forecast error of deployment-scale failure rates by explicitly optimizing for predictable performance degradation.

## Archivist Review

The approved concept, forecastability loss, represents a novel fine-tuning objective for safety-aware model training. The approved open questions address the foundational limitations in extrapolating failure tail behavior and the potential for integrating EVT with importance sampling, which are high-level research bottlenecks in AI safety.

### Approved Concepts
- Forecastability Loss: It provides a specific learning objective to minimize forecast error of failure rates at deployment scale.

### Approved Open Questions
- Model Failure Tail Dependence: This is crucial for scaling pre-deployment safety assessments to larger models and diverse real-world deployment domains where failure tail behavior may not be well-behaved under current assumptions.
- Composing EVT and IS: Combining these two complementary paradigms could provide more robust safety guarantees by leveraging the strengths of both extrapolation and rare-event simulation.

## Links

- [Abstract](https://arxiv.org/abs/2605.15134)
- [PDF](https://arxiv.org/pdf/2605.15134)

