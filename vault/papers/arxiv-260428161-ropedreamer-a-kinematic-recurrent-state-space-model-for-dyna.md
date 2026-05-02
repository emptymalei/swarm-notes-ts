---
# CSL-compatible fields
title: "RopeDreamer: A Kinematic Recurrent State Space Model for Dynamics of Flexible Deformable Linear Objects"
author:
  - literal: "Tim Missal"
  - literal: "Lucas Domingues"
  - literal: "Berk Guler"
  - literal: "Simon Manschitz"
  - literal: "Jan Peters"
  - literal: "Paula Dornhofer Paro Costa"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.28161"

# Custom fields
paper_id: "2604.28161"
paper_source: "arxiv"
domain: "robotics"
tags:
  - "robotics"
  - "dynamics-modeling"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "quaternionic-kinematic-chain-representation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:07:05Z"
created_at: "2026-05-02T05:07:05Z"
---

# RopeDreamer: A Kinematic Recurrent State Space Model for Dynamics of Flexible Deformable Linear Objects

**Authors**: Tim Missal, Lucas Domingues, Berk Guler, Simon Manschitz, Jan Peters, Paula Dornhofer Paro Costa
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28161](https://arxiv.org/abs/2604.28161)

## Summary

RopeDreamer is a latent dynamics framework designed for the robust long-term forecasting of deformable linear objects (DLOs) in contact-rich robotic manipulation. By representing DLOs as sequences of relative quaternions, the model adheres to a physically valid manifold that prevents artifacts like link stretching. The framework employs a dual-decoder architecture to decouple state reconstruction from future-state prediction, effectively capturing underlying deformation physics while outperforming existing state-of-the-art methods in both prediction accuracy and inference speed.

## Key Contributions

- Introduces RopeDreamer, a latent dynamics framework that integrates a Recurrent State Space Model with a Quaternionic Kinematic Chain representation for DLO manipulation.
- Achieves a 40.52% reduction in open-loop prediction error over 50-step horizons compared to state-of-the-art baselines in complex pick-and-place trajectories.
- Demonstrates 31.17% faster inference times while maintaining superior topological consistency in contact-rich scenarios with multiple self-intersections.

## Open Questions & Future Work

- [[hierarchical-latent-dynamics-dlo]]

## Key Concepts

- [[quaternionic-kinematic-chain-representation]]: A DLO representation using relative quaternion rotations to maintain link-length constancy and stay on a valid physical manifold.

## Archivist Review

The 'Quaternionic Kinematic Chain Representation' was approved as a robust, reusable geometric inductive bias for link-based dynamics. The 'Hierarchical Latent Dynamics for DLOs' open question was approved for articulating the specific trade-offs between reconstruction precision, long-term stability, and sim-to-real robustness in deformation modeling.

### Approved Concepts
- Quaternionic Kinematic Chain Representation: It serves as the core physical constraint mechanism that prevents non-physical deformations like link stretching in DLO dynamics modeling.

### Approved Open Questions
- Hierarchical Latent Dynamics for DLOs: This represents a critical bottleneck for real-world deployment of DLO dynamics models, as the current performance relies on simulation-trained latent spaces that may not generalize to diverse material parameters.

## Links

- [Abstract](https://arxiv.org/abs/2604.28161)
- [PDF](https://arxiv.org/pdf/2604.28161)

