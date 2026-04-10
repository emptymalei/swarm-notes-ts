---
# CSL-compatible fields
title: "Beyond Static Forecasting: Unleashing the Power of World Models for Mobile Traffic Extrapolation"
author:
  - literal: "Xiaoqian Qi"
  - literal: "Haoye Chai"
  - literal: "Yue Wang"
  - literal: "Yong Li"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08199"

# Custom fields
paper_id: "2604.08199"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "reinforcement-learning"
  - "digital-twin"
architectures:
  []
datasets:
  []
concept_slugs:
  - "network-action-conditioned-world-modeling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-10T15:27:49Z"
created_at: "2026-04-10T15:27:49Z"
---

# Beyond Static Forecasting: Unleashing the Power of World Models for Mobile Traffic Extrapolation

**Authors**: Xiaoqian Qi, Haoye Chai, Yue Wang, Yong Li
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08199](https://arxiv.org/abs/2604.08199)

## Summary

MobiWM is a world model architecture designed to move beyond static time-series forecasting in mobile network management by explicitly modeling the causal dynamics between traffic states and network control actions. By fusing multimodal environmental data—including imagery and sequential traffic patterns—the model enables unlimited-horizon rollouts under various configuration strategies. Extensive experiments on a large-scale real-world dataset demonstrate that MobiWM provides higher distributional fidelity than traditional forecasting models. Furthermore, it serves as a robust digital twin environment for reinforcement learning-based network optimization.

## Key Contributions

- Proposed MobiWM, a world model architecture that integrates mobile traffic states with multi-parameter network control actions (power, tilt, azimuth) to simulate operational dynamics.
- Introduced a multimodal fusion mechanism combining spatial image data with sequential traffic logs to improve spatial semantic understanding in wireless networks.
- Demonstrated superior distributional fidelity and forecasting performance across 31,900 mobile cells compared to standard temporal baselines and existing world model architectures.
- Validated the model's utility as an explorable counterfactual simulation environment through an RL-based downstream network optimization case study.

## Open Questions & Future Work

- [[infrastructure-world-model-dynamics-scaling]]

## Key Concepts

- [[network-action-conditioned-world-modeling]]: A predictive modeling framework that simulates system state evolution by conditioning on both temporal trajectories and exogenous control actions.

## Archivist Review

I approved the concept of action-conditioned world modeling as it generalizes the paper's specific implementation into a reusable paradigm for infrastructure control. The open question was broadened from mobile-specific networks to general infrastructure dynamics to better align with the vault's goal of tracking foundational scientific bottlenecks rather than domain-specific applications.

### Approved Concepts
- Network-Action-Conditioned World Modeling: It shifts mobile traffic forecasting from passive time-series modeling to active counterfactual simulation by incorporating exogenous control parameters (action-space) into the transition dynamics.

### Approved Open Questions
- Infrastructure World Model Dynamics Scaling: Establishing these architectural requirements is necessary to move beyond simple forecasting toward robust, reliable digital twins that support safe offline reinforcement learning for industrial control.

### Rejected Candidates
- [concept] MobiWM (`mobiwm`) - subcomponent_of_broader_mechanism: This is a specific model architecture instance; the broader mechanism of action-conditioned world modeling is more reusable.
- [open_question] Mobile Network World Model Development (`mobile-network-world-model-dynamics`) - duplicate_existing: Rephrased for broader infrastructure applicability while retaining the original technical intent.

## Links

- [Abstract](https://arxiv.org/abs/2604.08199)
- [PDF](https://arxiv.org/pdf/2604.08199)

