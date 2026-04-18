---
# CSL-compatible fields
title: "Data-Driven Probabilistic Finite L2-Gain Stabilization of Stochastic Linear Systems"
author:
  - literal: "Yitao Yan"
  - literal: "Shuangyu Han"
  - literal: "Jie Bao"
  - literal: "Biao Huang"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13707"

# Custom fields
paper_id: "2604.13707"
paper_source: "arxiv"
domain: "control-theory"
tags:
  - "stochastic-systems"
  - "control-theory"
  - "data-driven-control"
architectures:
  []
datasets:
  []
concept_slugs:
  - "probabilistic-finite-l2-gain-stabilization"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-18T04:54:11Z"
created_at: "2026-04-18T04:54:11Z"
---

# Data-Driven Probabilistic Finite L2-Gain Stabilization of Stochastic Linear Systems

**Authors**: Yitao Yan, Shuangyu Han, Jie Bao, Biao Huang
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13707](https://arxiv.org/abs/2604.13707)

## Summary

This paper introduces a novel approach for the finite L2-gain stabilization of stochastic linear systems, addressing the challenge that stochastic noise typically makes deterministic L2-gain metrics unbounded. By defining the L2-gain in a probabilistic sense, the authors derive a data-driven control design that utilizes noisy trajectory measurements and disturbance forecasts. The method results in a convex optimization problem formulated as linear matrix inequalities, ensuring effective controller synthesis from data.

## Key Contributions

- Introduces a probabilistic characterization of L2-gain to resolve the infinite gain problem in stochastic linear systems.
- Formulates a convex offline control design using linear matrix inequalities (LMIs) based on noisy trajectory measurements and disturbance forecasts.
- Proposes a data-driven trajectory estimation algorithm that integrates estimation error covariance into the controller synthesis conditions.

## Open Questions & Future Work

- [[tighter-stochastic-l2-gain-bounds]]
- [[distributed-probabilistic-l2-stabilization]]

## Key Concepts

- [[probabilistic-finite-l2-gain-stabilization]]: A framework for stabilizing stochastic linear systems by defining L2-gain in a probabilistic, rather than deterministic, manner.

## Archivist Review

The proposed concept of probabilistic finite L2-gain stabilization is approved as a foundational methodology for robust stochastic control. The open questions regarding tightening performance bounds and scaling to distributed architectures represent significant, non-trivial research bottlenecks in the field of control theory. No datasets were identified for promotion, as the paper relies on numerical examples rather than a reusable benchmark dataset.

### Approved Concepts
- Probabilistic Finite L2-Gain Stabilization: Provides a new mathematical framework to address the unbounded L2 gain issue in stochastic control systems.

### Approved Open Questions
- Tighter stochastic L2-gain bounds: This is technically important because the current framework assumes only first and second-order statistics, and tightening the bounds would directly improve the performance and applicability of the controller in practical settings where more prior information might be available.
- Distributed probabilistic L2-stabilization: This extension is critical for scaling data-driven control methods to complex, large-scale industrial processes where centralized control is infeasible.

## Links

- [Abstract](https://arxiv.org/abs/2604.13707)
- [PDF](https://arxiv.org/pdf/2604.13707)

