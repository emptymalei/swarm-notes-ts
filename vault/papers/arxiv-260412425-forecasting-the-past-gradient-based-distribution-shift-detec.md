---
# CSL-compatible fields
title: "Forecasting the Past: Gradient-Based Distribution Shift Detection in Trajectory Prediction"
author:
  - literal: "Michele De Vita"
  - literal: "Julian Wiederer"
  - literal: "Vasileios Belagiannis"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12425"

# Custom fields
paper_id: "2604.12425"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "uncertainty-estimation"
  - "distribution-shift"
  - "trajectory-prediction"
  - "autonomous-driving"
  - "self-supervised-learning"
architectures:
  []
datasets:
  - "shifts"
  - "argoverse"
concept_slugs:
  - "gradient-based-distribution-shift-detection"
dataset_slugs:
  - "shifts"
  - "argoverse"
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:04:05Z"
created_at: "2026-04-15T05:04:05Z"
---

# Forecasting the Past: Gradient-Based Distribution Shift Detection in Trajectory Prediction

**Authors**: Michele De Vita, Julian Wiederer, Vasileios Belagiannis
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12425](https://arxiv.org/abs/2604.12425)

## Summary

This paper introduces a self-supervised, post-hoc technique for identifying distributional shifts in trajectory prediction models commonly used in autonomous driving. By training a decoder on the proxy task of predicting the second half of observed trajectories from the first, the method uses the L2 norm of the loss gradient to signal when test data deviates from training distributions. The approach is entirely non-intrusive, preserving the original model's performance while providing a robust metric for uncertainty and collision risk in unfamiliar environments.

## Key Contributions

- Introduces a self-supervised post-hoc scoring method that detects distribution shifts by measuring the L2 norm of gradients from a trajectory-forecasting proxy task.
- Ensures zero interference with primary trajectory prediction models by operating as an independent, non-intrusive supervision layer.
- Demonstrates superior distribution shift detection performance on Shifts and Argoverse datasets and achieves early collision detection in the Highway simulator.

## Key Concepts

- [[gradient-based-distribution-shift-detection]]: A post-hoc method using the L2 norm of forecasting loss gradients to quantify distribution shifts in sequence prediction models.

## Archivist Review

The paper provides a distinct, post-hoc mechanism for distribution shift detection using gradient norms, which is highly reusable in time-series and trajectory forecasting contexts. I approved the core concept and the two named datasets explicitly used for evaluation. Other potential candidates were either too generic or subcomponents of this specific workflow.

### Approved Concepts
- Gradient-Based Distribution Shift Detection: This provides a post-hoc, model-agnostic mechanism for detecting distributional shifts in sequence forecasting tasks without modifying the primary model.

## Datasets

- [[shifts]]
- [[argoverse]]

## Links

- [Abstract](https://arxiv.org/abs/2604.12425)
- [PDF](https://arxiv.org/pdf/2604.12425)

