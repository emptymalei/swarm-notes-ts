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
  - "time-series-forecasting"
  - "traffic-prediction"
  - "world-models"
  - "digital-twins"
  - "reinforcement-learning"
  - "multimodal-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mobiwm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:44:45Z"
created_at: "2026-04-11T04:44:45Z"
---

# Beyond Static Forecasting: Unleashing the Power of World Models for Mobile Traffic Extrapolation

**Authors**: Xiaoqian Qi, Haoye Chai, Yue Wang, Yong Li
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08199](https://arxiv.org/abs/2604.08199)

## Summary

MobiWM is a world model designed for mobile network traffic prediction that shifts from static pattern recognition to modeling the interactive dynamics between traffic states and network control actions. By fusing multimodal spatial environmental data with time-series traffic, it creates a high-fidelity, explorable simulation environment for network optimization. The model supports unlimited-horizon rollout and counterfactual analysis, enabling more effective reinforcement learning-based network planning than traditional forecasting approaches.

## Key Contributions

- Introduces MobiWM, a world model architecture that integrates mobile traffic states with multi-parameter network adjustment actions (power, tilt, etc.) to capture complex operational dynamics.
- Enables unlimited-horizon rollout and counterfactual simulation of network adjustments by fusing multimodal environmental data (images and sequences) through shared spatial semantics.
- Outperforms existing traffic prediction baselines and state-of-the-art world models in distributional fidelity across large-scale deployments covering 31,900 cells.

## Open Questions & Future Work

- [[mobile-network-world-model-dynamics]]

## Key Concepts

- [[mobiwm]]: A world model for mobile networks that models the dynamics between traffic states and multi-parameter network adjustment actions to support unlimited-horizon rollout and counterfactual simulation.

## Archivist Review

I have approved 'MobiWM' as a core concept representing the transition from static forecasting to action-conditioned world modeling in telecommunications. I have also approved one open question concerning the modeling of network dynamics, which addresses the scalability and structural inductive biases required for such complex physical-cyber systems. Other candidates were rejected to avoid duplication or for being too implementation-specific.

### Approved Concepts
- MobiWM: It introduces the concept of action-aware world modeling specifically for telecommunications infrastructure, enabling counterfactual simulation and digital twin-driven network optimization.

### Approved Open Questions
- Mobile network world model dynamics: Establishing high-fidelity, action-aware simulation environments is critical for enabling RL-driven optimization and counterfactual analysis without the risk of deploying directly to live networks.

### Rejected Candidates
- [concept] Mobile Network World Model (`mobile-network-world-model-dynamics-concept`) - duplicate_existing: This is the same as the MobiWM concept, which is more specific and better defined.

## Links

- [Abstract](https://arxiv.org/abs/2604.08199)
- [PDF](https://arxiv.org/pdf/2604.08199)

