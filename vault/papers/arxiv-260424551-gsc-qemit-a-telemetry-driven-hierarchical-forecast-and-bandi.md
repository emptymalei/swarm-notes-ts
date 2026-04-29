---
# CSL-compatible fields
title: "GSC-QEMit: A Telemetry-Driven Hierarchical Forecast-and-Bandit Framework for Adaptive Quantum Error Mitigation"
author:
  - literal: "Steven Szachara"
  - literal: "Sheeraja Rajakrishnan"
  - literal: "Dylan Jay Van Allen"
  - literal: "Jason Pollack"
  - literal: "Travis Desell"
  - literal: "Daniel Krutz"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24551"

# Custom fields
paper_id: "2604.24551"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "uncertainty-aware"
  - "probabilistic-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "gsc-qemit"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-29T05:13:31Z"
created_at: "2026-04-29T05:13:31Z"
---

# GSC-QEMit: A Telemetry-Driven Hierarchical Forecast-and-Bandit Framework for Adaptive Quantum Error Mitigation

**Authors**: Steven Szachara, Sheeraja Rajakrishnan, Dylan Jay Van Allen, Jason Pollack, Travis Desell, Daniel Krutz
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24551](https://arxiv.org/abs/2604.24551)

## Summary

GSC-QEMit is a hierarchical, telemetry-driven framework designed for adaptive quantum error mitigation in nonstationary noise environments. The framework utilizes a Growing Hierarchical Self-Organizing Map for context clustering, a Gaussian-process forecaster to track fidelity degradation, and a cost-aware contextual multi-armed bandit to optimize action selection. Evaluations on benchmark quantum circuits demonstrate significant fidelity improvements while reducing overhead by effectively reserving heavy mitigation interventions for periods of high noise.

## Key Contributions

- Introduced GSC-QEMit, a hierarchical framework for adaptive quantum error mitigation using telemetry-driven context clustering, fidelity forecasting, and cost-aware bandit action selection.
- Demonstrated a 9.0% improvement in average logical fidelity across diverse quantum circuit families compared to unmitigated execution.
- Achieved efficient mitigation-to-cost trade-offs by dynamically allocating heavy intervention resources specifically during inferred noise spikes.

## Open Questions & Future Work

- [[physical-hardware-adaptive-qem-deployment]]

## Key Concepts

- [[gsc-qemit]]: A hierarchical framework integrating telemetry clustering, Gaussian-process forecasting, and contextual bandit-based action selection for adaptive quantum error mitigation.

## Archivist Review

I approved GSC-QEMit as a novel hierarchical control framework applicable to dynamic, resource-constrained systems beyond quantum error mitigation. I approved the open question regarding hardware deployment because it identifies a critical transition gap between simulated policies and the real-time constraints of NISQ-era processors. Other potential subcomponents were rejected to maintain the focus on the overarching architecture.

### Approved Concepts
- GSC-QEMit: Central framework of the paper providing a novel hierarchical approach for adaptive quantum error mitigation by balancing mitigation strength and overhead.

### Approved Open Questions
- Physical Hardware Adaptive QEM Deployment: Bridging the gap between simulated adaptive control policies and physical hardware implementation is critical for scaling NISQ-era reliability and determining if these frameworks provide tangible performance gains on actual quantum processors.

## Links

- [Abstract](https://arxiv.org/abs/2604.24551)
- [PDF](https://arxiv.org/pdf/2604.24551)

