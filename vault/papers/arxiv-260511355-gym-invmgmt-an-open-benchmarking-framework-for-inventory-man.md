---
# CSL-compatible fields
title: "gym-invmgmt: An Open Benchmarking Framework for Inventory Management Methods"
author:
  - literal: "Reza Barati"
  - literal: "Qinmin Vivian Hu"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11355"

# Custom fields
paper_id: "2605.11355"
paper_source: "arxiv"
domain: "operations-research-and-supply-chain-optimization"
tags:
  - "reinforcement-learning"
  - "inventory-management"
  - "benchmark"
  - "multi-agent-reinforcement-learning"
  - "stochastic-programming"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-13T05:25:55Z"
created_at: "2026-05-13T05:25:55Z"
---

# gym-invmgmt: An Open Benchmarking Framework for Inventory Management Methods

**Authors**: Reza Barati, Qinmin Vivian Hu
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11355](https://arxiv.org/abs/2605.11355)

## Summary

gym-invmgmt is an open, Gymnasium-compatible benchmarking framework designed to standardize the evaluation of inventory management policies across optimization, heuristic, and learned controller paradigms. By enforcing a shared contract for transitions, rewards, and KPI definitions, it mitigates performance misinterpretations arising from varied evaluation assumptions. The authors evaluate multiple approaches, finding that PPO-Transformer provides the best learned performance, while informing stochastic programming serves as a strong, albeit computationally expensive, baseline.

## Key Contributions

- Introduces gym-invmgmt, a Gymnasium-compatible benchmarking framework standardizing evaluation contracts for diverse inventory management policies.
- Establishes a 22-scenario core grid for cross-paradigm testing, covering varying topology, demand regimes, and information access constraints.
- Demonstrates that PPO-Transformer delivers the highest learned-policy performance, while stochastic programming acts as a high-cost but effective non-oracle reference.

## Open Questions & Future Work

- [[topology-aware-action-decoding-in-supply-chains]]
- [[hybrid-or-learning-control-integration]]

## Archivist Review

The submitted benchmark framework is a significant contribution to inventory management, but I have opted to keep the vault focused by approving only the identified research bottlenecks as open questions. The concepts (e.g., PPO-Transformer, Residual RL) are treated as specific implementation choices rather than broad reusable architectural paradigms. The open questions have been refined to ensure they represent standing research hurdles in the integration of OR and ML.

### Approved Open Questions
- Topology-Aware Action Decoding: This addresses the critical challenge of learned policies failing to generalize physically to novel supply chain structures.
- Hybrid OR-Learning Control Integration: Bridging the gap between the accuracy of classical OR solvers and the speed of deep learning is essential for real-time, non-stationary industrial systems.

### Rejected Candidates
- [open_question] Topology-aware action decoding mechanisms (`topology-aware-action-decoding`) - other: Renamed for better specificity and uniqueness as a permanent vault entry.
- [open_question] Hybrid OR-learning control integration (`hybrid-or-learning-control`) - other: Renamed for better specificity as a permanent vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2605.11355)
- [PDF](https://arxiv.org/pdf/2605.11355)

