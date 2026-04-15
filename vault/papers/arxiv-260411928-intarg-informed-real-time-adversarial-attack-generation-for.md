---
# CSL-compatible fields
title: "INTARG: Informed Real-Time Adversarial Attack Generation for Time-Series Regression"
author:
  - literal: "Gamze Kirman Tokgoz"
  - literal: "Onat Gungor"
  - literal: "Tajana Rosing"
  - literal: "Baris Aksanli"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11928"

# Custom fields
paper_id: "2604.11928"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "adversarial-attacks"
  - "time-series-forecasting"
  - "online-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "informed-selective-adversarial-attack-isaa"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:06:01Z"
created_at: "2026-04-15T05:06:01Z"
---

# INTARG: Informed Real-Time Adversarial Attack Generation for Time-Series Regression

**Authors**: Gamze Kirman Tokgoz, Onat Gungor, Tajana Rosing, Baris Aksanli
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11928](https://arxiv.org/abs/2604.11928)

## Summary

This paper introduces INTARG, an adversarial attack framework designed for time-series forecasting models operating under online, memory-constrained environments. By focusing on selective, informed intervention at specific time steps—specifically those where the target model has high confidence but stands to lose significant accuracy—the framework minimizes the required number of attack steps. Empirical results demonstrate that this strategy achieves substantially higher prediction errors compared to non-selective baselines while maintaining high efficiency.

## Key Contributions

- Introduces INTARG, a selective adversarial attack framework for time-series regression under bounded-buffer constraints.
- Demonstrates that targeting time steps with high model confidence and maximum expected error significantly improves attack efficacy.
- Achieves up to 2.42x increase in prediction error while executing attacks on fewer than 10% of total time steps.

## Open Questions & Future Work

- [[scalability-of-constrained-adversarial-attacks]]

## Key Concepts

- [[informed-selective-adversarial-attack-isaa]]: A time-series adversarial attack framework that selectively targets time steps based on model confidence and maximal expected prediction error.

## Archivist Review

The review focused on extracting the core mechanism of informed, selective adversarial intervention for time-series, separating it from the paper-specific implementation name. The open question was reframed to target the technical bottleneck of scaling these attacks under tighter memory/sampling regimes and cross-domain transferability. Generic ML terminology and paper-local names were discarded to maintain vault longevity.

### Approved Concepts
- Informed Selective Adversarial Attack (ISAA): It establishes a paradigm for efficient red-teaming in resource-constrained, online forecasting environments by targeting high-impact temporal windows.

### Approved Open Questions
- Scalability of Constrained Adversarial Attacks: It addresses the gap between theoretical adversarial robustness and the practical, compute-limited constraints of real-time industrial forecasting deployments.

### Rejected Candidates
- [concept] INTARG (`intarg`) - subcomponent_of_broader_mechanism: INTARG is the specific implementation name of a broader mechanism (Informed Selective Adversarial Attack); the concept itself is more reusable than the specific framework name.
- [open_question] Adaptive Adversarial Streaming Constraints (`adaptive-adversarial-streaming-limitations`) - duplicate_existing: The proposed question is overly broad and partially redundant with the core contribution of the paper, whereas the newly crafted question focuses more precisely on scalability and transferability.

## Links

- [Abstract](https://arxiv.org/abs/2604.11928)
- [PDF](https://arxiv.org/pdf/2604.11928)

