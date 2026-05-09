---
# CSL-compatible fields
title: "Beyond Long Tail POIs: Transition-Centered Generalization for Human Mobility Prediction"
author:
  - literal: "Dingyang Lyu"
  - literal: "Zhengjia Xu"
  - literal: "Jey Han Lau"
  - literal: "Jianzhong Qi"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05771"

# Custom fields
paper_id: "2605.05771"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "warm-transition-holdout-training"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-09T05:12:18Z"
created_at: "2026-05-09T05:12:18Z"
---

# Beyond Long Tail POIs: Transition-Centered Generalization for Human Mobility Prediction

**Authors**: Dingyang Lyu, Zhengjia Xu, Jey Han Lau, Jianzhong Qi
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05771](https://arxiv.org/abs/2605.05771)

## Summary

This paper addresses the problem of transition-level sparsity in next-POI human mobility prediction, where models fail due to rare or unseen source-destination pairs rather than just infrequent POIs. The authors frame this as a compositional generalization challenge and introduce RECAP, a framework that reconstructs rare transitions using multi-hop graph transitivity and historical user patterns. By combining this reconstruction strategy with a novel warm-transition holdout training technique, the model achieves superior generalization performance on long-tail transitions compared to traditional methods.

## Key Contributions

- Identifies transition-level sparsity, rather than just POI-level sparsity, as a core bottleneck in next-POI human mobility prediction.
- Proposes RECAP, a transition reconstruction framework that leverages multi-hop graph transitivity and historical user revisit patterns for compositional generalization.
- Introduces warm-transition holdout training to mitigate memorization of frequent transitions and incentivize the model to learn transferable signals for tail transitions.
- Demonstrates consistent improvement in prediction accuracy over baselines across multiple real-world datasets, particularly on tail transitions.

## Open Questions & Future Work

- [[integrating-transition-signals-into-llms]]

## Key Concepts

- [[warm-transition-holdout-training]]: A training strategy that mitigates memorization by holding out frequent transitions, forcing models to learn from transferable signals rather than rote frequency patterns.

## Archivist Review

I have approved the core regularization technique as a reusable concept and the challenge of integrating explicit transition-level structural bias into LLMs as a significant open bottleneck. RECAP itself is a specific architectural framework, so I have excluded it in favor of its novel training component, which is more broadly applicable. No datasets were approved as they were described only in aggregate.

### Approved Concepts
- Warm-transition Holdout Training: This is a distinct regularization strategy that shifts focus from memorizing high-frequency events to learning generalizable compositional features, which is highly reusable in other long-tail forecasting tasks.

### Approved Open Questions
- Transition-aware LLM mobility prediction: LLM-based mobility prediction is an emerging paradigm, but currently struggles with transition-level sparsity that simple neural models are beginning to address; merging these approaches is critical for achieving both scalability and accuracy.

## Links

- [Abstract](https://arxiv.org/abs/2605.05771)
- [PDF](https://arxiv.org/pdf/2605.05771)

