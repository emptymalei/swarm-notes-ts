---
# CSL-compatible fields
title: "Non-monotonic causal discovery with Kolmogorov-Arnold Fuzzy Cognitive Maps"
author:
  - literal: "Jose L. Salmeron"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.05136"

# Custom fields
paper_id: "2604.05136"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "kolmogorov-arnold-fuzzy-cognitive-map"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:57:36Z"
created_at: "2026-04-08T04:57:36Z"
---

# Non-monotonic causal discovery with Kolmogorov-Arnold Fuzzy Cognitive Maps

**Authors**: Jose L. Salmeron
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.05136](https://arxiv.org/abs/2604.05136)

## Summary

The paper introduces Kolmogorov-Arnold Fuzzy Cognitive Maps (KA-FCM), an evolution of traditional Fuzzy Cognitive Maps that replaces scalar synaptic weights with learnable B-spline functions. By relocating non-linearity from the nodes to the causal influence phase on edges, KA-FCMs can model non-monotonic and periodic causal dependencies. The architecture is validated across non-monotonic inference, symbolic regression, and chaotic time-series forecasting, demonstrating superior performance over standard FCMs and competitive results against MLPs while retaining full model interpretability.

## Key Contributions

- Introduced Kolmogorov-Arnold Fuzzy Cognitive Maps (KA-FCMs), which replace traditional scalar weights with learnable B-spline functions to capture non-monotonic causal relationships.
- Enables modeling of complex dynamic systems and periodic behaviors without requiring increased graph density or hidden layers.
- Achieved competitive performance against MLP black-box models on chaotic time-series forecasting while maintaining graph-based interpretability.

## Open Questions & Future Work

- [[scalability-of-large-scale-functional-fcm]]

## Key Concepts

- [[kolmogorov-arnold-fuzzy-cognitive-map]]: A neuro-symbolic architecture that replaces static synaptic weights in Fuzzy Cognitive Maps with learnable B-spline functions to model non-monotonic dependencies.

## Archivist Review

The paper introduces a novel neuro-symbolic architecture that effectively bridges the gap between the interpretability of Fuzzy Cognitive Maps and the expressive power of non-monotonic function approximation. I approved the architecture and the associated scalability concern, as these are foundational for future research into functional graph-based time-series modeling. Other potential candidates were not identified or were deemed too specific to the paper's internal implementation.

### Approved Concepts
- Kolmogorov-Arnold Fuzzy Cognitive Map: This is the primary architectural contribution of the paper, replacing scalar weights with learnable B-spline functions to enable non-monotonic causal modeling.

### Approved Open Questions
- Scalability of large-scale functional FCMs: Understanding how to maintain both high predictive accuracy and human-understandable interpretations in dense, large-scale networks is a fundamental challenge for the adoption of neuro-symbolic models in real-world scenarios.

## Links

- [Abstract](https://arxiv.org/abs/2604.05136)
- [PDF](https://arxiv.org/pdf/2604.05136)

