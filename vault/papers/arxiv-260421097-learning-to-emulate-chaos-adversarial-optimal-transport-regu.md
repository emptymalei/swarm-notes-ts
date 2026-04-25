---
# CSL-compatible fields
title: "Learning to Emulate Chaos: Adversarial Optimal Transport Regularization"
author:
  - literal: "Gabriel Melo"
  - literal: "Leonardo Santiago"
  - literal: "Peter Y. Lu"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.21097"

# Custom fields
paper_id: "2604.21097"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "dynamical-systems"
  - "generative-modeling"
  - "optimal-transport"
architectures:
  []
datasets:
  []
concept_slugs:
  - "adversarial-optimal-transport-regularization"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-25T04:55:25Z"
created_at: "2026-04-25T04:55:25Z"
---

# Learning to Emulate Chaos: Adversarial Optimal Transport Regularization

**Authors**: Gabriel Melo, Leonardo Santiago, Peter Y. Lu
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.21097](https://arxiv.org/abs/2604.21097)

## Summary

This paper addresses the difficulty of training neural emulators for chaotic dynamical systems, where sensitivity to initial conditions renders point-wise squared-error losses ineffective for long-term forecasting. The authors introduce a family of adversarial optimal transport regularization objectives that force emulators to match the underlying statistical attractors of the system. By jointly learning summary statistics and emulator parameters, the method achieves significantly better long-term statistical fidelity across multiple high-dimensional chaotic systems.

## Key Contributions

- Proposes a family of adversarial optimal transport objectives (Sinkhorn 2-Wasserstein and WGAN-style 1-Wasserstein) for training dynamical system emulators.
- Enables joint learning of high-quality summary statistics and physically consistent emulators for chaotic systems.
- Demonstrates improved long-term statistical fidelity in emulators across various high-dimensional chaotic attractors compared to traditional squared-error methods.

## Open Questions & Future Work

- [[extend-adversarial-ot-to-non-ergodic-dynamics]]

## Key Concepts

- [[adversarial-optimal-transport-regularization]]: A training framework for dynamical system emulators that uses adversarial optimal transport to enforce physical consistency and matching of attractor statistics.

## Archivist Review

The paper introduces a compelling approach to training dynamical system emulators using optimal transport to enforce statistical consistency. I have approved the overarching concept and the key open question regarding the extension to non-ergodic dynamics, as these represent substantial and reusable contributions to the field of chaotic system emulation.

### Approved Concepts
- Adversarial Optimal Transport Regularization: It introduces a new regularization framework specifically designed to improve the statistical fidelity of emulators for chaotic dynamical systems by leveraging Wasserstein-based objectives.

### Approved Open Questions
- Extending OT to Non-Ergodic Dynamics: The current method relies on the ergodic hypothesis to converge to a stable invariant measure. Generalizing this to non-ergodic or stochastic settings is critical for applying these techniques to real-world chaotic systems that are rarely perfectly stationary or purely deterministic.

## Links

- [Abstract](https://arxiv.org/abs/2604.21097)
- [PDF](https://arxiv.org/pdf/2604.21097)

