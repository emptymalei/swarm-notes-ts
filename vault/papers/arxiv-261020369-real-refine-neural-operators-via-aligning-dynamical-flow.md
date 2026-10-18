---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ReAl: Refine neural operators via aligning dynamical flow"
description: "This paper presents ReAl (Refine and Align), a plug-in framework designed to enhance neural partial differential equation (PDE) surrogates. While traditional surrogates trained on mean squared error often fail to capture high-frequency details, and generative models suffer from drift during rollouts, ReAl uses conditional flow matching to model residuals and recover fine-scale structures. To ensure long-term stability, particularly in chaotic systems, the model employs a reinforcement learning-based alignment stage that optimizes trajectory-level rewards, effectively reducing error accumulation in autoregressive forecasting."
resource: "https://arxiv.org/abs/2610.20369"
tags:
  - "scientific-modeling"
  - "flow-matching"
  - "time-series-forecasting"
  - "autoregressive-models"
  - "reinforcement-learning"
  - "spatio-temporal-modeling"
  - "physics-informed-ml"
  - "forecasting-accuracy"
  - "generative-modeling"
timestamp: "2026-10-18T00:33:33Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jing Xu"
  - literal: "Zenglin Xu"
  - literal: "Li Yi"
  - literal: "Ruoxi Jiang"
  - literal: "Yuan Qi"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20369"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "real-pde-refinement"
    description: "A model-agnostic plug-in for neural PDE surrogates that uses conditional flow matching for high-frequency refinement and reinforcement learning for trajectory-level stability."
  - name: "trajectory-level-alignment"
    description: "A training strategy that optimizes sequential models using rewards derived from multi-step rollouts to minimize distribution drift and preserve physical consistency."
datasets:
  []
open_questions:
  - name: "trajectory-alignment-scaling"
    description: "How can trajectory-level reinforcement learning be efficiently scaled to high-resolution, high-dimensional spatio-temporal systems without the prohibitive computational cost of generating large ensembles of rollouts?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:33:33Z"
created_at: "2026-10-18T00:33:33Z"
---

# ReAl: Refine neural operators via aligning dynamical flow

**Authors**: Jing Xu, Zenglin Xu, Li Yi, Ruoxi Jiang, Yuan Qi
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20369](https://arxiv.org/abs/2610.20369)

## Summary

This paper presents ReAl (Refine and Align), a plug-in framework designed to enhance neural partial differential equation (PDE) surrogates. While traditional surrogates trained on mean squared error often fail to capture high-frequency details, and generative models suffer from drift during rollouts, ReAl uses conditional flow matching to model residuals and recover fine-scale structures. To ensure long-term stability, particularly in chaotic systems, the model employs a reinforcement learning-based alignment stage that optimizes trajectory-level rewards, effectively reducing error accumulation in autoregressive forecasting.

## Key Contributions

- Proposed ReAl, a model-agnostic framework that enhances high-frequency fidelity and long-term stability of neural PDE surrogates.
- Implemented a refinement stage using conditional flow matching to recover residual fine-scale structures missing from deterministic base predictions.
- Introduced a trajectory-level alignment stage using reinforcement learning to mitigate generative error accumulation in autoregressive rollouts.
- Validated the method across diverse architectures, demonstrating significant improvements in forecasting accuracy and stability for chaotic dynamical systems.

## Limitations

The abstract does not explicitly detail the computational cost of the reinforcement learning stage or the multi-trajectory generation during alignment.

## Open Questions & Future Work

- [[trajectory-alignment-scaling]]

## Key Concepts

- [[real-pde-refinement]]: A model-agnostic plug-in for neural PDE surrogates that uses conditional flow matching for high-frequency refinement and reinforcement learning for trajectory-level stability.
- [[trajectory-level-alignment]]: A training strategy that optimizes sequential models using rewards derived from multi-step rollouts to minimize distribution drift and preserve physical consistency.

## Archivist Review

Approved the ReAl framework as it represents a novel model-agnostic approach to bridging the gap between MSE stability and generative detail in PDE surrogates. Approved trajectory-level alignment as a distinct and reusable mechanism for stabilizing autoregressive rollouts in chaotic systems via reinforcement learning. The open question addresses the critical scaling bottleneck of multi-trajectory RL in high-dimensional physics simulations. No datasets were approved as none were specifically named in the abstract or provided in the analysis.

### Approved Concepts
- ReAl (Refine and Align): ReAl addresses the fundamental trade-off between the stability of deterministic MSE-trained surrogates and the detail-capturing capability of generative models in scientific machine learning.
- Trajectory-level Alignment: It specifically targets the issue of error accumulation and 'distribution drift' in generative models when applied to long-horizon autoregressive rollouts in chaotic systems.

### Approved Open Questions
- Scaling Trajectory-level Alignment: Efficiency is critical for real-time PDE surrogates; if the alignment stage is too expensive, it may limit the practical utility of these plug-ins for large-scale 3D simulations.

### Rejected Candidates
- [concept] ReAl (Refine and Align) (`real-pde-refinement-alignment`) - other: Renamed slug to 'real-pde-refinement' for brevity and consistency with the vault's naming conventions.
- [open_question] Computational Scaling of Trajectory Alignment (`real-computational-scaling-rl`) - paper_local: Renamed slug and title to 'trajectory-alignment-scaling' to be more general and less paper-local.

## Links

- [Abstract](https://arxiv.org/abs/2610.20369)
- [PDF](https://arxiv.org/pdf/2610.20369)

