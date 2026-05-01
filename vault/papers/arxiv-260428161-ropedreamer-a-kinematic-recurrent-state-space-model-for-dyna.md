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
  - "state-space-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "quaternionic-kinematic-chain-representation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:21:43Z"
created_at: "2026-05-01T05:21:43Z"
---

# RopeDreamer: A Kinematic Recurrent State Space Model for Dynamics of Flexible Deformable Linear Objects

**Authors**: Tim Missal, Lucas Domingues, Berk Guler, Simon Manschitz, Jan Peters, Paula Dornhofer Paro Costa
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28161](https://arxiv.org/abs/2604.28161)

## Summary

RopeDreamer is a latent dynamics framework designed for the robust long-term forecasting of deformable linear objects (DLOs) during complex robotic manipulation. By representing DLOs as Quaternionic Kinematic Chains, the model preserves physical constraints like link-length constancy that Cartesian models often violate. The system uses a dual-decoder architecture to separate state reconstruction from future-state prediction, resulting in superior topological consistency and reduced prediction errors in contact-rich, self-intersecting scenarios.

## Key Contributions

- Introduced a latent dynamics framework that utilizes a Quaternionic Kinematic Chain representation to ensure physical validity and link-length constancy in DLO dynamics modeling.
- Developed a dual-decoder architecture that decouples state reconstruction from future-state prediction to better capture underlying deformation physics.
- Achieved a 40.52% reduction in open-loop prediction error and a 31.17% reduction in inference time over 50-step horizons compared to state-of-the-art baselines in contact-rich DLO manipulation tasks.

## Open Questions & Future Work

- [[online-system-identification-dlo-dynamics]]

## Key Concepts

- [[quaternionic-kinematic-chain-representation]]: A method for modeling deformable linear objects using sequences of relative quaternionic rotations to preserve physical integrity and link-length constraints.

## Archivist Review

I approved the 'Quaternionic Kinematic Chain Representation' as it provides a distinct, physically-grounded architectural constraint for temporal modeling of articulated structures. The open question on online system identification for DLOs highlights a critical, non-trivial limitation in adapting predictive models to variable physical environments. All other candidates were rejected as they were either too specific to the paper's local implementation or covered by broader concepts already in the vault.

### Approved Concepts
- Quaternionic Kinematic Chain Representation: This representation serves as a structural inductive bias that enforces physical invariants, making it a powerful technique for modeling flexible, articulated entities in robotics and beyond.

### Approved Open Questions
- Online system identification DLO dynamics: The lack of adaptation to changing physical properties is a primary bottleneck in moving from simulated benchmarks to robust, real-world robotic interaction.

## Links

- [Abstract](https://arxiv.org/abs/2604.28161)
- [PDF](https://arxiv.org/pdf/2604.28161)

