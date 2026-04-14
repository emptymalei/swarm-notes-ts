---
# CSL-compatible fields
title: "NimbusGuard: A Novel Framework for Proactive Kubernetes Autoscaling Using Deep Q-Networks"
author:
  - literal: "Chamath Wanigasooriya"
  - literal: "Indrajith Ekanayake"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11017"

# Custom fields
paper_id: "2604.11017"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "reinforcement-learning"
  - "deep-learning"
  - "kubernetes"
architectures:
  - "long-short-term-memory-lstm"
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-14T05:04:18Z"
created_at: "2026-04-14T05:04:18Z"
---

# NimbusGuard: A Novel Framework for Proactive Kubernetes Autoscaling Using Deep Q-Networks

**Authors**: Chamath Wanigasooriya, Indrajith Ekanayake
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11017](https://arxiv.org/abs/2604.11017)

## Summary

NimbusGuard is an open-source proactive autoscaling framework designed to improve resource efficiency in Kubernetes clusters. By integrating a Deep Q-Network agent with an LSTM-based workload forecaster, the system shifts scaling decisions from reactive monitoring to predictive resource management. Evaluation results show that this proactive approach significantly outperforms standard Horizontal Pod Autoscalers and KEDA in both performance and cost reduction.

## Key Contributions

- Introduces NimbusGuard, an open-source proactive autoscaling framework for Kubernetes that replaces traditional reactive scaling controllers.
- Combines Deep Q-Networks (DQN) with an LSTM forecasting module to anticipate workload demands and optimize resource allocation.
- Demonstrates superior performance and cost efficiency compared to native Kubernetes Horizontal Pod Autoscalers and event-driven KEDA.

## Open Questions & Future Work

- [[hybrid-horizontal-vertical-autoscaling]]

## Archivist Review

I rejected the 'NimbusGuard' concept as it represents a specific tool implementation rather than a foundational methodological concept that will recur in the literature. I approved the hybrid autoscaling question as it addresses a fundamental limitation in current cloud-native orchestration research.

### Approved Open Questions
- Hybrid Horizontal and Vertical Autoscaling: The current focus on horizontal scaling alone limits the flexibility and cost-optimization potential of Kubernetes autoscalers. A hybrid approach combining horizontal and vertical scaling could significantly improve resource utilization efficiency.

### Rejected Candidates
- [concept] NimbusGuard (`nimbusguard`) - paper_local: The proposed system is a specific application framework rather than a reusable architectural pattern or generalized algorithmic contribution.

## Links

- [Abstract](https://arxiv.org/abs/2604.11017)
- [PDF](https://arxiv.org/pdf/2604.11017)

