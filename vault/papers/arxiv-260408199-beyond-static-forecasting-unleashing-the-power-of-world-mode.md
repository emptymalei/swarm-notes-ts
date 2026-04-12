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
  - "forecasting"
  - "digital-twin"
  - "reinforcement-learning"
  - "mobile-networks"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mobiwm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-12T05:03:29Z"
created_at: "2026-04-12T05:03:29Z"
---

# Beyond Static Forecasting: Unleashing the Power of World Models for Mobile Traffic Extrapolation

**Authors**: Xiaoqian Qi, Haoye Chai, Yue Wang, Yong Li
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08199](https://arxiv.org/abs/2604.08199)

## Summary

MobiWM is a world model framework designed for mobile network traffic prediction that shifts from static time-series extrapolation to dynamic interaction modeling. By integrating mobile traffic states with multi-parameter network actions (e.g., power, tilt) and multimodal environmental data, the model effectively captures the causal influence of network adjustments on traffic distribution. Extensive experiments show that MobiWM provides high-fidelity simulations for unlimited-horizon rollouts, proving effective as a digital twin for downstream reinforcement learning-based network optimization.

## Key Contributions

- Introduces MobiWM, a world model framework that explicitly captures the dynamics between mobile traffic system states and multi-parameter network control actions.
- Enables unlimited-horizon rollout and counterfactual simulation, allowing operators to explore network optimization strategies beyond static point forecasting.
- Demonstrates superior distributional fidelity and forecasting performance compared to existing baselines on a large-scale dataset spanning 31,900 cells.

## Open Questions & Future Work

- [[mobile-network-world-modeling]]

## Key Concepts

- [[mobiwm]]: A world model for mobile networks that integrates system states and network control actions to enable counterfactual simulation and planning.

## Archivist Review

I have approved the MobiWM concept as it represents a shift in time-series forecasting towards interactive world modeling, which is highly reusable. The open question regarding mobile network world modeling is also approved as it articulates the gap between current general world models and the specific requirements for high-dimensional action-state transitions in wireless network infrastructure. No datasets were approved as the large-scale cell data mentioned remains unnamed and specific to this implementation.

### Approved Concepts
- MobiWM: It introduces a world model approach to mobile network traffic prediction, moving beyond static time-series forecasting to simulate the interaction between traffic dynamics and network parameters.

### Approved Open Questions
- Mobile Network World Modeling: This is fundamental for moving beyond static traffic prediction toward actionable, simulation-based network planning and optimization, which is essential for 5G-Advanced and 6G network management.

## Links

- [Abstract](https://arxiv.org/abs/2604.08199)
- [PDF](https://arxiv.org/pdf/2604.08199)

