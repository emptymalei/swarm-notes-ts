---
# CSL-compatible fields
title: "Sub-Band Full Duplex Resource Allocation: A Predictive Deep Reinforcement Learning Approach"
author:
  - literal: "Abhiram D"
  - literal: "Aiswarya Rajan"
  - literal: "Arin Shemeem"
  - literal: "Vipindev Adat Vasudevan"
  - literal: "Abdulla P"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14339"

# Custom fields
paper_id: "2605.14339"
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
processed_at: "2026-05-17T05:25:01Z"
created_at: "2026-05-17T05:25:01Z"
---

# Sub-Band Full Duplex Resource Allocation: A Predictive Deep Reinforcement Learning Approach

**Authors**: Abhiram D, Aiswarya Rajan, Arin Shemeem, Vipindev Adat Vasudevan, Abdulla P
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14339](https://arxiv.org/abs/2605.14339)

## Summary

This paper addresses dynamic resource allocation in Sub-Band Full Duplex (SBFD) systems by coupling traffic prediction with reinforcement learning. The authors use a Bidirectional Long Short-Term Memory (Bi-LSTM) network to forecast bursty traffic patterns, providing the inputs for a Double Deep Q-Network (DDQN) that manages uplink and downlink split ratios in real-time. By utilizing both current queue states and future traffic predictions, the model achieves proactive scheduling that optimizes spectrum utilization and reduces network latency compared to static configurations.

## Key Contributions

- Proposes a predictive resource allocation framework for Sub-Band Full Duplex (SBFD) systems by integrating Bi-LSTM traffic forecasting with DDQN-based scheduling.
- Demonstrates proactive UL/DL split ratio adaptation based on predicted traffic demands, reducing queue buildup and improving overall spectrum utilization.
- Provides a scalable approach for autonomous resource management in 6G networks by moving beyond static configuration limitations.

## Open Questions & Future Work

- [[multi-agent-sbfd-resource-allocation]]

## Archivist Review

I have rejected the proposed concept of a predictive SBFD framework as it represents a routine combination of existing sequence modeling and RL architectures. I approved the open question regarding multi-agent SBFD allocation, as it identifies the specific transition from single-node simulation to multi-cell network deployment that is necessary for 6G research. No datasets were approved as none were explicitly provided or sufficiently unique to warrant a standalone vault entry.

### Approved Open Questions
- Multi-Agent SBFD Resource Allocation: Multi-agent coordination is required for inter-cell interference management in dense 6G deployments, and empirical validation is essential for proving real-world applicability beyond simulated Markov-modulated processes.

### Rejected Candidates
- [concept] Predictive SBFD Resource Allocation Framework (`predictive-sbfd-resource-allocation-framework`) - not_novel: The integration of Bi-LSTM with reinforcement learning for resource management is a standard architectural pattern in recent literature rather than a novel conceptual contribution.

## Links

- [Abstract](https://arxiv.org/abs/2605.14339)
- [PDF](https://arxiv.org/pdf/2605.14339)

