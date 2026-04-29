---
# CSL-compatible fields
title: "DECOFFEE: Decentralized Reinforcement Learning for Time-critical Workload Offloading and Energy Efficiency across the Computing Continuum"
author:
  - literal: "Anastasios Giannopoulos"
  - literal: "Sotirios Spantideas"
  - literal: "Panagiotis Trakadas"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24507"

# Custom fields
paper_id: "2604.24507"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "reinforcement-learning"
  - "edge-computing"
  - "distributed-systems"
  - "energy-efficiency"
  - "workload-scheduling"
architectures:
  - "dqn"
  - "lstm"
datasets:
  []
concept_slugs:
  - "decoffee"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:13:44Z"
created_at: "2026-04-29T05:13:44Z"
---

# DECOFFEE: Decentralized Reinforcement Learning for Time-critical Workload Offloading and Energy Efficiency across the Computing Continuum

**Authors**: Anastasios Giannopoulos, Sotirios Spantideas, Panagiotis Trakadas
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24507](https://arxiv.org/abs/2604.24507)

## Summary

DECOFFEE is a decentralized multi-agent reinforcement learning framework designed to optimize workload offloading in the Edge-Cloud computing continuum. The system employs a Double Dueling Deep Q-Network combined with LSTM-based forecasting to address the challenges of stochastic load arrivals and heterogeneous network conditions. By formulating placement as parallel Markov Decision Processes, it effectively manages the trade-offs between execution delay, energy consumption, and workload reliability. Simulations confirm that the approach significantly outperforms traditional heuristic and rule-based methods in highly dynamic distributed environments.

## Key Contributions

- Introduces DECOFFEE, a decentralized multi-agent reinforcement learning framework for workload offloading across the edge-cloud continuum.
- Formulates workload placement as parallel Markov Decision Processes, solved via a Double Dueling DQN architecture integrated with LSTM forecasting.
- Demonstrates consistent performance improvements over rule-based and heuristic baselines in reducing latency, energy consumption, and workload drop rates under dynamic stochastic conditions.

## Open Questions & Future Work

- [[federated-collaborative-learning-edge-cloud]]

## Key Concepts

- [[decoffee]]: A decentralized reinforcement learning framework for joint optimization of latency, energy, and reliability in edge-cloud computing.

## Archivist Review

The paper proposes a specific reinforcement learning framework for distributed resource management. I have approved the framework name as a concept because its design pattern (decentralized multi-agent RL for heterogeneous continuum nodes) is recurring, and I have approved the open question on collaborative learning for the continuum because it addresses the inherent scaling and privacy challenges of such architectures. Other candidates were not proposed.

### Approved Concepts
- DECOFFEE: Acts as the primary novel framework for decentralized multi-agent workload offloading in edge-cloud continuum environments.

### Approved Open Questions
- Federated Collaborative Continuum Learning: This is a critical bottleneck for deploying large-scale decentralized systems where individual agents need global intelligence but face constraints regarding communication overhead, data privacy, and the complexity of non-stationary environments.

## Links

- [Abstract](https://arxiv.org/abs/2604.24507)
- [PDF](https://arxiv.org/pdf/2604.24507)

