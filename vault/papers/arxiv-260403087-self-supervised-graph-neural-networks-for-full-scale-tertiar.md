---
# CSL-compatible fields
title: "Self-Supervised Graph Neural Networks for Full-Scale Tertiary Voltage Control"
author:
  - literal: "Balthazar Donon"
  - literal: "Geoffroy Jamgotchian"
  - literal: "Hugo Kulesza"
  - literal: "Louis Wehenkel"
issued:
  date-parts:
    - [2026, 4, 3]
url: "https://arxiv.org/abs/2604.03087"

# Custom fields
paper_id: "2604.03087"
paper_source: "arxiv"
domain: "time-series"
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
processed_at: "2026-04-06T05:02:05Z"
created_at: "2026-04-06T05:02:05Z"
---

# Self-Supervised Graph Neural Networks for Full-Scale Tertiary Voltage Control

**Authors**: Balthazar Donon, Geoffroy Jamgotchian, Hugo Kulesza, Louis Wehenkel
**Date**: 2026-04-03
**Paper ID**: [arxiv:2604.03087](https://arxiv.org/abs/2604.03087)

## Summary

This paper addresses the computational complexity of Tertiary Voltage Control (TVC) in power systems by reframing it as an amortized optimization task rather than a traditional Mixed Integer Non Linear Program. The authors introduce a self-supervised Graph Neural Network (GNN) trained to predict control setpoints that minimize voltage violations. Applied to the French TSO's forecasting pipeline, the model achieves effective voltage regulation on real-scale HV-EHV power grid data without requiring optimality guarantees.

## Key Contributions

- Formulates tertiary voltage control as an amortized optimization problem to bypass the scalability limitations of traditional MINLP solvers.
- Proposes a self-supervised GNN architecture trained to minimize voltage violations in high-voltage power grids.
- Demonstrates significant reduction in voltage violations on full-scale HV-EHV French power grid day-ahead forecast data.

## Open Questions & Future Work

- [[simulator-robustness-training-loops]]

## Archivist Review

I have approved 'Improving Simulator Robustness' as it captures a critical bottleneck when applying data-driven methods to physical grid systems where standard simulators (like AC power flow) frequently break down. I rejected the training efficiency question as it is a generic engineering challenge rather than a unique scientific bottleneck. No concepts were approved, as the framing of TVC as 'amortized optimization' is a known paradigm and the GNN application is specific to the power system domain without offering a broader reusable temporal modeling primitive.

### Approved Open Questions
- Improving Simulator Robustness: Simulator convergence is critical for the stability of self-supervised and reinforcement learning frameworks applied to safety-critical physical systems.

### Rejected Candidates
- [open_question] Accelerating GNN Training Efficiency (`gnn-tvc-training-efficiency`) - generic: Computational efficiency and parallelization are generic challenges in ML and do not constitute a specific scientific research question in this context.

## Links

- [Abstract](https://arxiv.org/abs/2604.03087)
- [PDF](https://arxiv.org/pdf/2604.03087)

