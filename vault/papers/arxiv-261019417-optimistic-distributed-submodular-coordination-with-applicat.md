---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Optimistic Distributed Submodular Coordination with Applications to Multi-Target Tracking with Multiple Robots"
description: "This paper presents the Optimistic Distributed Online Greedy (O-DOG) algorithm, designed for multi-agent submodular coordination in dynamic bandit environments. Unlike standard methods, O-DOG leverages optimistic predictions of future rewards and neighbor actions to track time-varying optima across arbitrary network topologies. Theoretical analysis confirms that O-DOG achieves sublinear tracking regret provided predictions are sufficiently accurate, while simulations in multi-robot target tracking demonstrate its efficiency and robustness compared to non-predictive distributed algorithms."
resource: "https://arxiv.org/abs/2610.19417"
tags:
  - "robotics"
  - "multi-agent-systems"
  - "online-learning"
  - "distributed-systems"
  - "control-theory"
  - "stochastic-optimization"
  - "dynamic-adaptation"
  - "agent-interaction"
timestamp: "2026-10-18T00:46:18Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Pranjal Sharma"
  - literal: "Atharva Navsalkar"
  - literal: "Zirui Xu"
  - literal: "Vasileios Tzoumas"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19417"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "o-dog-algorithm"
    description: "A distributed online algorithm for multi-agent submodular coordination that leverages predictions of environmental evolution to achieve sublinear tracking regret."
datasets:
  []
open_questions:
  - name: "communication-latency-impact-on-distributed-greedy"
    description: "How does significant communication latency or intermittent connectivity in time-varying network topologies impact the convergence and regret guarantees of distributed greedy algorithms that rely on optimistic predictions?"
  - name: "heterogeneous-prediction-quality-effects"
    description: "How does heterogeneity in prediction quality among agents affect the global coordination performance and the overall tracking regret of the multi-robot system?"
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:46:18Z"
created_at: "2026-10-18T00:46:18Z"
---

# Optimistic Distributed Submodular Coordination with Applications to Multi-Target Tracking with Multiple Robots

**Authors**: Pranjal Sharma, Atharva Navsalkar, Zirui Xu, Vasileios Tzoumas
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19417](https://arxiv.org/abs/2610.19417)

## Summary

This paper presents the Optimistic Distributed Online Greedy (O-DOG) algorithm, designed for multi-agent submodular coordination in dynamic bandit environments. Unlike standard methods, O-DOG leverages optimistic predictions of future rewards and neighbor actions to track time-varying optima across arbitrary network topologies. Theoretical analysis confirms that O-DOG achieves sublinear tracking regret provided predictions are sufficiently accurate, while simulations in multi-robot target tracking demonstrate its efficiency and robustness compared to non-predictive distributed algorithms.

## Key Contributions

- Introduced the Optimistic Distributed Online Greedy (O-DOG) algorithm, which incorporates reward and action predictions for decentralized submodular coordination.
- Proved that O-DOG achieves sublinear tracking regret even when optimal actions change at every time step, provided prediction errors remain bounded.
- Derived theoretical bounds for decentralization suboptimality as a function of network topology, showing that accurate predictions accelerate convergence to coordinated states.
- Validated the algorithm's performance in simulated multi-robot target tracking scenarios, demonstrating improved tracking accuracy over prediction-free baselines.

## Limitations

The algorithm's performance is strictly dependent on prediction accuracy; while it matches prediction-free baselines at worst, its primary advantages are contingent on high-quality forecasts.

## Open Questions & Future Work

- [[communication-latency-impact-on-distributed-greedy]]
- [[heterogeneous-prediction-quality-effects]]

## Key Concepts

- [[o-dog-algorithm]]: A distributed online algorithm for multi-agent submodular coordination that leverages predictions of environmental evolution to achieve sublinear tracking regret.

## Archivist Review

I approved the O-DOG algorithm as the primary technical contribution of the paper. Standard metrics like tracking regret and well-established problem domains like multi-target tracking were rejected to maintain the specificity of the vault. The open questions were selected based on their technical relevance to the robustness of distributed coordination systems.

### Approved Concepts
- Optimistic Distributed Online Greedy (O-DOG): It addresses the coordination of multiple agents in dynamic environments by integrating reward predictions directly into the greedy selection process, a significant advancement over static or non-optimistic methods.

### Approved Open Questions
- Resilience to Communication Latency: In real-world robotics, communication is rarely instantaneous or perfect; understanding the limits of O-DOG under such constraints is vital for deployment.
- Impact of Heterogeneous Prediction Quality: Uniform prediction accuracy is unlikely in heterogeneous robot swarms, and identifying how poor predictions from a single agent might propagate through the network is crucial for robustness.

### Rejected Candidates
- [concept] Multi-Target Tracking (`multi-target-tracking`) - not_novel: Multi-target tracking is a well-established application domain and not a novel concept or technique introduced by this paper.
- [concept] Submodular Coordination (`submodular-coordination`) - not_novel: Submodular coordination is a standard optimization framework used as the basis for the paper rather than a novel contribution.
- [concept] Tracking Regret (`tracking-regret`) - not_novel: Tracking regret is a standard performance metric in online learning and not a new concept proposed here.

## Links

- [Abstract](https://arxiv.org/abs/2610.19417)
- [PDF](https://arxiv.org/pdf/2610.19417)

