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
  - "adversarial-learning"
  - "chaotic-systems"
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
processed_at: "2026-04-24T05:08:56Z"
created_at: "2026-04-24T05:08:56Z"
---

# Learning to Emulate Chaos: Adversarial Optimal Transport Regularization

**Authors**: Gabriel Melo, Leonardo Santiago, Peter Y. Lu
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.21097](https://arxiv.org/abs/2604.21097)

## Summary

This paper introduces a framework for training neural emulators of chaotic dynamical systems using adversarial optimal transport regularization. By replacing traditional squared-error losses with Sinkhorn or WGAN-style dual formulations, the approach learns to match the statistical properties and attractor structure of chaotic systems rather than relying on point-wise trajectory matching. Experimental validation across several complex systems demonstrates that this regularization significantly improves long-term statistical fidelity in scenarios where sensitivity to initial conditions limits traditional methods.

## Key Contributions

- Introduced adversarial optimal transport regularization to training neural emulators for chaotic dynamical systems.
- Proposed a framework that jointly learns high-quality summary statistics and physically consistent emulators.
- Formulated both Sinkhorn divergence (2-Wasserstein) and WGAN-style dual formulation (1-Wasserstein) approaches for emulator training.
- Demonstrated superior long-term statistical fidelity over standard squared-error loss benchmarks across high-dimensional chaotic attractors.

## Open Questions & Future Work

- [[extend-adversarial-ot-to-non-ergodic-dynamics]]
- [[emulating-stochastic-chaotic-dynamics]]

## Key Concepts

- [[adversarial-optimal-transport-regularization]]: A training framework for neural emulators that employs optimal transport objectives to align the statistical distributions and attractors of generated and reference chaotic trajectories.

## Archivist Review

I have approved the core methodological contribution of adversarial optimal transport regularization for chaotic systems and two high-level open research directions. I rejected other candidates as they were either specific formulations already covered by the main concept or minor future-work extensions. The selected items are distinct, reusable, and represent fundamental advancements in the field of dynamical system emulation.

### Approved Concepts
- Adversarial Optimal Transport Regularization: This is a novel, high-level methodological paradigm for training emulators on chaotic systems that bypasses the limitations of point-wise squared-error losses.

### Approved Open Questions
- Non-ergodic adversarial OT generalization: Generalizing these methods to non-stationary systems is critical for applying data-driven emulators to real-world phenomena where the dynamics evolve over time.
- Stochastic chaotic dynamics emulation: Physical systems are often inherently stochastic, and emulators must balance chaotic structural fidelity with accurate stochastic representation.

## Links

- [Abstract](https://arxiv.org/abs/2604.21097)
- [PDF](https://arxiv.org/pdf/2604.21097)

