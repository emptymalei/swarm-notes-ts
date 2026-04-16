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
domain: "time-series"
tags:
  - "time-series"
  - "trajectory-prediction"
  - "distribution-shift-detection"
  - "autonomous-driving"
architectures:
  []
datasets:
  []
concept_slugs:
  - "gradient-based-distribution-shift-detection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:08:17Z"
created_at: "2026-04-16T05:08:17Z"
---

# Forecasting the Past: Gradient-Based Distribution Shift Detection in Trajectory Prediction

**Authors**: Michele De Vita, Julian Wiederer, Vasileios Belagiannis
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12425](https://arxiv.org/abs/2604.12425)

## Summary

This paper addresses the performance degradation of trajectory prediction models caused by distributional shifts in automated driving scenarios. The authors introduce a self-supervised, post-hoc detection method that calculates the L2 norm of gradients from a decoder tasked with predicting the latter half of observed trajectories. By utilizing this gradient-based score, the framework effectively identifies unfamiliar conditions without interfering with the primary trajectory model's performance. The method is validated on the Shifts and Argoverse datasets and demonstrates additional utility for early collision detection in motion planning.

## Key Contributions

- Proposes a post-hoc, self-supervised gradient-based score to detect distributional shifts in trajectory prediction models without altering original model parameters.
- Achieves improved distribution shift detection performance on the Shifts and Argoverse benchmarks compared to standard uncertainty estimation methods.
- Demonstrates versatility by enabling early collision detection for deep Q-Network motion planners in the Highway simulator.

## Key Concepts

- [[gradient-based-distribution-shift-detection]]: A self-supervised method that uses the L2 norm of gradients from a post-hoc forecasting task to detect distributional shifts in trajectory prediction models.

## Archivist Review

The review applied strict criteria to ensure only foundational, reusable mechanisms are admitted. I approved 'gradient-based-distribution-shift-detection' as a novel, model-agnostic approach for detecting distribution shifts, while rejecting the datasets as they are established benchmarks. No new open questions were identified as substantial enough to warrant a standalone entry.

### Approved Concepts
- gradient-based-distribution-shift-detection: The core contribution is a novel, self-supervised mechanism to quantify out-of-distribution inputs by analyzing gradient norms in a secondary, post-hoc forecasting task.

### Rejected Candidates
- [dataset] Shifts (`shifts`) - not_reusable: Routine benchmark dataset.
- [dataset] Argoverse (`argoverse`) - not_reusable: Routine benchmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.12425)
- [PDF](https://arxiv.org/pdf/2604.12425)

