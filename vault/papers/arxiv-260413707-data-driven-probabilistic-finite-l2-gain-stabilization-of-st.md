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
  - "stochastic-systems"
  - "data-driven-control"
  - "linear-matrix-inequalities"
  - "l2-gain-stabilization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "probabilistic-finite-l2-gain-stabilization"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-17T05:07:36Z"
created_at: "2026-04-17T05:07:36Z"
---

# Data-Driven Probabilistic Finite L2-Gain Stabilization of Stochastic Linear Systems

**Authors**: Yitao Yan, Shuangyu Han, Jie Bao, Biao Huang
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13707](https://arxiv.org/abs/2604.13707)

## Summary

This paper addresses the problem of finite L2-gain stabilization for stochastic linear systems, where standard L2-gain definitions are typically unbounded due to stochastic noise. The authors introduce a probabilistic L2-gain concept and develop a data-driven control design that utilizes noisy trajectory measurements and disturbance forecasts. The resulting controller synthesis is framed as a convex optimization problem using linear matrix inequalities, incorporating estimation error covariance to ensure stability and performance.

## Key Contributions

- Introduced a novel probabilistic characterization of L2-gain for stochastic systems, enabling finite-gain stabilization where standard definitions fail.
- Developed a data-driven controller synthesis approach using noisy trajectory measurements and disturbance forecasts.
- Formulated the controller synthesis as a tractable convex optimization problem using linear matrix inequalities (LMIs) that incorporate trajectory estimation error covariance.

## Open Questions & Future Work

- [[stochastic-l2-gain-tighter-bounds]]
- [[distributed-probabilistic-control]]

## Key Concepts

- [[probabilistic-finite-l2-gain-stabilization]]: A framework that characterizes the L2 gain of stochastic systems probabilistically to enable finite gain stabilization despite stochastic uncertainties.

## Archivist Review

The paper proposes a novel framework for handling stochastic control systems where standard L2-gain definitions are inapplicable. I approved the core concept as it provides a reusable theoretical foundation for probabilistic stability in stochastic settings, and approved two open questions that define clear, researchable directions for tightening bounds and scaling the approach to distributed systems. No datasets were proposed or found in the paper to warrant an entry.

### Approved Concepts
- Probabilistic Finite L2-Gain Stabilization: Addresses the fundamental limitation that standard L2 gain is ill-defined for stochastic systems by introducing a probabilistic formulation suitable for control synthesis.

### Approved Open Questions
- Tighter probabilistic L2-gain bounds: The current bounds are conservative because they cater to all possible disturbance distributions. Tighter bounds would significantly improve control performance in practical applications where partial information about disturbance statistics is known.
- Distributed probabilistic L2-gain stabilization: Large-scale dynamical systems are frequently controlled in a distributed fashion. Extending this framework is essential for maintaining probabilistic stability guarantees in complex, networked control environments.

## Links

- [Abstract](https://arxiv.org/abs/2604.13707)
- [PDF](https://arxiv.org/pdf/2604.13707)

