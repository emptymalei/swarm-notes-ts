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
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:14:14Z"
created_at: "2026-04-28T05:14:14Z"
---

# DECOFFEE: Decentralized Reinforcement Learning for Time-critical Workload Offloading and Energy Efficiency across the Computing Continuum

**Authors**: Anastasios Giannopoulos, Sotirios Spantideas, Panagiotis Trakadas
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24507](https://arxiv.org/abs/2604.24507)

## Summary

DECOFFEE is a decentralized multi-agent reinforcement learning framework designed for optimal workload offloading and energy management across the edge-cloud continuum. By formulating the placement problem as parallel Markov Decision Processes, edge nodes autonomously decide between local execution and offloading based on local observations and LSTM-predicted network states. The approach leverages a Double Dueling Deep Q-Network architecture, demonstrating superior performance over heuristic and rule-based baselines in latency-sensitive, resource-constrained environments.

## Key Contributions

- Proposes DECOFFEE, a decentralized multi-agent reinforcement learning framework for joint optimization of delay, energy, and drop rate in computing continuum workloads.
- Formulates the workload placement problem as parallel Markov Decision Processes solved via Double Dueling Deep Q-Networks.
- Integrates LSTM-based load forecasting into the agent policy to dynamically adapt to time-varying network and traffic conditions.

## Open Questions & Future Work

- [[federated-collaborative-decentralized-rl]]
- [[heterogeneous-qos-offloading]]

## Archivist Review

The proposed framework, DECOFFEE, is a system-level implementation that combines standard reinforcement learning techniques (MARL, Double Dueling DQN) with common time-series forecasting (LSTM). As these are well-established components, the paper does not introduce a novel, reusable concept worthy of a standalone note. The two open questions provided are relevant to the ongoing maturation of decentralized RL and QoS management in edge-computing scenarios.

### Approved Open Questions
- Federated decentralized learning mechanisms: This addresses the trade-off between decentralized training efficiency and the potential for collective intelligence in distributed reinforcement learning architectures.
- Support for heterogeneous workloads: This is essential for moving from theoretical workload models to functional deployments that must satisfy diverse user-level SLAs.

### Rejected Candidates
- [concept] DECOFFEE Framework (`decoffee-framework`) - paper_local: The proposed framework is a paper-specific system architecture that describes a combination of existing methods (MARL, DQN, LSTM) rather than a novel, reusable core concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.24507)
- [PDF](https://arxiv.org/pdf/2604.24507)

