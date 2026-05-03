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
  - "latent-dynamics"
  - "deformable-objects"
architectures:
  []
datasets:
  []
concept_slugs:
  - "quaternionic-kinematic-chain-representation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T05:13:49Z"
created_at: "2026-05-03T05:13:49Z"
---

# RopeDreamer: A Kinematic Recurrent State Space Model for Dynamics of Flexible Deformable Linear Objects

**Authors**: Tim Missal, Lucas Domingues, Berk Guler, Simon Manschitz, Jan Peters, Paula Dornhofer Paro Costa
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28161](https://arxiv.org/abs/2604.28161)

## Summary

This paper addresses the challenge of modeling the dynamics of flexible deformable linear objects (DLOs) by introducing RopeDreamer, a recurrent state space model. By utilizing a quaternionic kinematic chain representation, the model effectively constrains the dynamics to a physically valid manifold, preventing issues like link stretching. A dual-decoder architecture further improves performance by decoupling state reconstruction from future-state prediction. The method demonstrates significant improvements in long-horizon forecasting accuracy and computational efficiency compared to current state-of-the-art approaches in complex contact-rich robotic tasks.

## Key Contributions

- Proposed a latent dynamics framework that utilizes a Quaternionic Kinematic Chain representation to enforce physical validity in DLO modeling.
- Developed a dual-decoder architecture that decouples state reconstruction from future-state prediction to refine latent physical representations.
- Achieved a 40.52% reduction in open-loop prediction error over 50-step horizons and a 31.17% reduction in inference time compared to state-of-the-art baselines.

## Open Questions & Future Work

- [[online-system-identification-dlo-dynamics]]

## Key Concepts

- [[quaternionic-kinematic-chain-representation]]: A representation for deformable objects using relative quaternions to maintain length consistency and physical validity in latent space.

## Archivist Review

I approved the Quaternionic Kinematic Chain Representation for its specific, reusable approach to enforcing physical constraints in latent space for deformable linear objects. I also approved the open question regarding online material property adaptation as it represents a fundamental challenge for transitioning robotic dynamics models from simulation to the real world. Other potential candidates were either subcomponents or lacked sufficient distinctness to warrant permanent vault status.

### Approved Concepts
- Quaternionic Kinematic Chain Representation: It provides a domain-specific geometric constraint that enforces physical validity in the state representation of deformable linear objects.

### Approved Open Questions
- Online Material Property Adaptation: This is critical for bridging the sim-to-real gap, as current models trained in simulators with fixed physics parameters often fail when applied to real-world objects with different physical characteristics.

## Links

- [Abstract](https://arxiv.org/abs/2604.28161)
- [PDF](https://arxiv.org/pdf/2604.28161)

