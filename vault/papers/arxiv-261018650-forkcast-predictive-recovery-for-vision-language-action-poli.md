---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ForkCast: Predictive Recovery for Vision-Language-Action Policies via Counterfactual Futures"
description: "ForkCast is a predictive recovery framework for Vision-Language-Action (VLA) policies that handles execution disruptions such as object slippage and visual occlusion. Instead of relying on a separate failure detector, it uses a candidate-conditioned world model to simulate three counterfactual futures—continuing the current action, re-observing the scene, or replanning the trajectory—and scores them using a shared task-progress head. This approach allows the system to simultaneously decide when an intervention is necessary and which recovery strategy is most effective. Evaluated on RoboTwin 2.0, ForkCast significantly improves task success rates and exhibits high transferability across different VLA architectures without necessitating updates to the base models."
resource: "https://arxiv.org/abs/2610.18650"
tags:
  - "robotics"
  - "vision-language-action"
  - "world-models"
  - "error-recovery"
  - "trajectory-planning"
  - "predictive-modeling"
  - "autonomous-driving"
  - "control-systems"
timestamp: "2026-10-18T00:55:27Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Chenru Wen"
  - literal: "Huajian Zeng"
  - literal: "Haokai Ding"
  - literal: "Jian Kang"
  - literal: "Anqing Duan"
  - literal: "Dawei Zhou"
  - literal: "Dezhen Song"
  - literal: "Xingxing Zuo"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18650"
paper_source: "arxiv"
architectures:
  - "transformer"
concepts:
  - name: "forkcast"
    description: "A predictive recovery framework for vision-language-action (VLA) policies that uses a candidate-conditioned world model to select intervention strategies by comparing forecasted counterfactual futures."
datasets:
  - name: "RoboTwin 2.0"
    description: "A simulation benchmark for robot manipulation tasks used to evaluate VLA policies under failure conditions like occlusion and object slip."
open_questions:
  - name: "dynamic-recovery-candidate-generation"
    description: "How can the set of recovery candidates be dynamically expanded or optimized beyond fixed strategies to handle more diverse and unconstrained failure modes in real-world environments?"
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:55:27Z"
created_at: "2026-10-18T00:55:27Z"
---

# ForkCast: Predictive Recovery for Vision-Language-Action Policies via Counterfactual Futures

**Authors**: Chenru Wen, Huajian Zeng, Haokai Ding, Jian Kang, Anqing Duan, Dawei Zhou, Dezhen Song, Xingxing Zuo
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18650](https://arxiv.org/abs/2610.18650)

## Summary

ForkCast is a predictive recovery framework for Vision-Language-Action (VLA) policies that handles execution disruptions such as object slippage and visual occlusion. Instead of relying on a separate failure detector, it uses a candidate-conditioned world model to simulate three counterfactual futures—continuing the current action, re-observing the scene, or replanning the trajectory—and scores them using a shared task-progress head. This approach allows the system to simultaneously decide when an intervention is necessary and which recovery strategy is most effective. Evaluated on RoboTwin 2.0, ForkCast significantly improves task success rates and exhibits high transferability across different VLA architectures without necessitating updates to the base models.

## Key Contributions

- Developed ForkCast, a framework that enables frozen Vision-Language-Action (VLA) policies to recover from failures by forecasting and comparing counterfactual futures.
- Introduced a unified decision mechanism that scores three candidates—Commit, Reobserve, and Replan—using a candidate-conditioned world model and a task-progress head.
- Achieved a 125% relative improvement in success rates (from 13.3% to 30.0%) on the RoboTwin 2.0 benchmark under challenging occlusion and slip conditions.
- Demonstrated zero-shot transferability of the ForkCast recovery logic across multiple distinct VLA backbones without requiring internal model updates.

## Limitations

Requires adaptation on real-robot candidate rollouts to maintain performance outside of simulation.

## Open Questions & Future Work

- [[dynamic-recovery-candidate-generation]]

## Key Concepts

- [[forkcast]]: A predictive recovery framework for vision-language-action (VLA) policies that uses a candidate-conditioned world model to select intervention strategies by comparing forecasted counterfactual futures.

## Archivist Review

I approved 'ForkCast' as the primary concept as it represents the central methodological contribution of the paper. I approved the 'RoboTwin 2.0' dataset as it is a specific, named benchmark used for evaluating the proposed system's recovery capabilities. I also approved the open question regarding dynamic candidate generation, as it identifies a fundamental limitation of current predictive recovery frameworks. I rejected 'Task-Progress-Based Intervention' because it is a subcomponent and the defining logic of the ForkCast framework rather than an independent concept.

### Approved Concepts
- ForkCast: It provides a unified mechanism for both failure detection and recovery strategy selection without requiring explicit failure detectors or intervention thresholds.

### Approved Open Questions
- Dynamic Recovery Candidate Generation: Static candidate sets are limited by the designer's foresight and may not cover the long tail of potential failure scenarios in complex robotics tasks.

### Rejected Candidates
- [concept] Task-Progress-Based Intervention (`task-progress-intervention`) - subcomponent_of_broader_mechanism: This mechanism is the core internal logic of the ForkCast framework and does not currently warrant a standalone entry distinct from the framework itself.

## Datasets

- [[RoboTwin 2.0]]

## Links

- [Abstract](https://arxiv.org/abs/2610.18650)
- [PDF](https://arxiv.org/pdf/2610.18650)

