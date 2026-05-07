---
# CSL-compatible fields
title: "Bilinear Mamba-Koopman Neural MPC for Varying Dynamics"
author:
  - literal: "Matan Pagi"
  - literal: "Zohar Sorek"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04793"

# Custom fields
paper_id: "2605.04793"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series"
  - "model-predictive-control"
architectures:
  []
datasets:
  []
concept_slugs:
  - "bilinear-mamba-koopman-neural-mpc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:15:08Z"
created_at: "2026-05-07T05:15:08Z"
---

# Bilinear Mamba-Koopman Neural MPC for Varying Dynamics

**Authors**: Matan Pagi, Zohar Sorek
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04793](https://arxiv.org/abs/2605.04793)

## Summary

Bilinear Mamba-Koopman Neural MPC addresses the limitation of control-independent operators in Koopman-based MPC by introducing control-dependent coupling in the latent dynamics. By employing a low-rank structure, the approach maintains convexity and enables efficient optimization via Sequential Convex Programming (SCP) while remaining computationally lightweight. Experiments show the model improves forecasting accuracy and provides robust performance under varying dynamics and delayed re-planning scenarios compared to standard linear formulations.

## Key Contributions

- Introduces Bilinear Mamba-Koopman Neural MPC to enable control-dependent latent dynamics, generalizing standard Koopman-based approaches.
- Utilizes a low-rank structure to introduce control-dependent coupling with less than 1% parameter overhead, maintaining exact model Jacobians for efficient Sequential Convex Programming.
- Demonstrates superior forecasting accuracy and robustness to stale-plan execution in time-varying regimes across CartPole and RSCP benchmarks.

## Open Questions & Future Work

- [[decoupling-benchmarks-koopman]]
- [[koopman-runtime-stability-gating]]

## Key Concepts

- [[bilinear-mamba-koopman-neural-mpc]]: A Koopman-based neural MPC model that introduces control-dependent coupling in latent dynamics using low-rank structures to enhance adaptability to varying conditions.

## Archivist Review

The paper provides a significant advancement in Koopman-based control by introducing a bilinear extension that maintains convexity for optimization. The approved concept is central to this mechanism, while the open questions address clear methodological gaps in benchmarking and safety. Datasets were rejected as they are domain-specific standard benchmarks (CartPole) or proprietary experimental setups (RSCP) rather than widely reusable community datasets.

### Approved Concepts
- Bilinear Mamba-Koopman Neural MPC: Provides a novel approach to lifting Koopman operator constraints while maintaining computational tractability for model predictive control.

### Approved Open Questions
- Benchmarking control-state coupling: This is critical for evaluating the specific architectural gains of models like the bilinear Koopman extension versus other potential improvements for Koopman learning.
- Runtime stability gating for MPC: Ensuring stability is a primary requirement for deploying learned controllers in safety-critical industrial environments.

## Links

- [Abstract](https://arxiv.org/abs/2605.04793)
- [PDF](https://arxiv.org/pdf/2605.04793)

