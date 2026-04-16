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
domain: "control-systems"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "probabilistic-finite-l2-gain-stabilization"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-16T05:06:24Z"
created_at: "2026-04-16T05:06:24Z"
---

# Data-Driven Probabilistic Finite L2-Gain Stabilization of Stochastic Linear Systems

**Authors**: Yitao Yan, Shuangyu Han, Jie Bao, Biao Huang
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13707](https://arxiv.org/abs/2604.13707)

## Summary

This paper addresses the challenge of applying finite L2-gain stabilization to stochastic linear systems, where input noise typically causes unbounded gain. The authors introduce a probabilistic characterization of L2-gain and propose a data-driven stabilization design that utilizes noisy trajectory measurements and potentially inaccurate disturbance forecasts. The resulting control synthesis is formulated as a convex optimization problem via linear matrix inequalities, effectively accounting for trajectory estimation errors.

## Key Contributions

- Introduces a novel probabilistic L2-gain framework to overcome the unbounded gain issue in stochastic linear systems.
- Develops a data-driven controller synthesis method using noisy trajectory measurements and uncertain disturbance forecasts.
- Formulates the controller design as a convex offline optimization problem via linear matrix inequalities (LMIs), incorporating estimation error covariance.

## Open Questions & Future Work

- [[tighter-probabilistic-performance-bounds]]

## Key Concepts

- [[probabilistic-finite-l2-gain-stabilization]]: A framework for managing disturbance sensitivity in stochastic systems by reformulating L2-gain constraints probabilistically.

## Archivist Review

The paper introduces a significant theoretical advancement for control systems by reformulating the standard finite L2-gain objective to accommodate stochastic uncertainty, which is a common bottleneck. I have approved the core concept and the resulting open research direction, as both provide a reusable foundation for future research in stochastic control and robust optimization. No further candidates were requested or provided.

### Approved Concepts
- Probabilistic Finite L2-Gain Stabilization: Addresses the theoretical limitation that standard L2-gain is unbounded in stochastic systems due to input noise.

### Approved Open Questions
- Tighter probabilistic performance bounds: The current formulation is general and potentially conservative due to the lack of specific distribution knowledge; relaxing this could significantly improve performance in practical applications.

## Links

- [Abstract](https://arxiv.org/abs/2604.13707)
- [PDF](https://arxiv.org/pdf/2604.13707)

