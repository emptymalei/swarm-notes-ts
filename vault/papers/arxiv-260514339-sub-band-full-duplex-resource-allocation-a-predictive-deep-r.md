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
processed_at: "2026-05-16T05:13:19Z"
created_at: "2026-05-16T05:13:19Z"
---

# Sub-Band Full Duplex Resource Allocation: A Predictive Deep Reinforcement Learning Approach

**Authors**: Abhiram D, Aiswarya Rajan, Arin Shemeem, Vipindev Adat Vasudevan, Abdulla P
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14339](https://arxiv.org/abs/2605.14339)

## Summary

This paper introduces a predictive deep reinforcement learning framework for dynamic resource allocation in Sub-Band Full Duplex (SBFD) systems. By combining a Bi-LSTM network for traffic demand forecasting with a Double Deep Q-Network (DDQN) for scheduling, the system proactively adapts uplink and downlink split ratios. The approach effectively handles bursty traffic dynamics, demonstrating superior performance in spectrum utilization and queue management compared to static allocation schemes.

## Key Contributions

- Integrates a hybrid Bi-LSTM forecasting model with a DDQN agent to enable proactive sub-band allocation in SBFD systems.
- Enables dynamic adaptation of uplink/downlink split ratios based on predicted traffic demand and current queue states.
- Improves spectrum utilization and reduces queue buildup compared to traditional static SBFD configurations.

## Open Questions & Future Work

- [[multi-agent-multi-cell-sbfd-allocation]]

## Archivist Review

The paper proposes an application of standard deep reinforcement learning techniques to resource allocation in full-duplex systems. While the multi-cell, multi-agent extension is a valid open research question, the proposed architectural methods (Bi-LSTM and DDQN integration) are standard in the field and do not constitute novel conceptual contributions worthy of a standalone vault entry.

### Approved Open Questions
- Multi-agent SBFD Resource Allocation: As SBFD moves toward practical deployment, the interaction between neighboring cells and the coordination of agents become critical to prevent system-wide performance degradation, making the multi-cell, multi-agent extension a necessary research frontier.

### Rejected Candidates
- [concept] Proactive sub-band allocation (`proactive-sub-band-allocation`) - paper_local: This is a specific application of general predictive resource allocation techniques rather than a reusable architectural contribution.
- [concept] Bi-LSTM DDQN integration (`bi-lstm-ddqn-integration`) - not_novel: This is a standard hybrid architecture and does not qualify as a novel, reusable concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.14339)
- [PDF](https://arxiv.org/pdf/2605.14339)

