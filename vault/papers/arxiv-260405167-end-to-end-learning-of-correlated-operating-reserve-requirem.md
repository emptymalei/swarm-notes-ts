---
# CSL-compatible fields
title: "End-to-End Learning of Correlated Operating Reserve Requirements in Security-Constrained Economic Dispatch"
author:
  - literal: "Owen Shen"
  - literal: "Hung-po Chao"
  - literal: "Haihao Lu"
  - literal: "Patrick Jaillet"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.05167"

# Custom fields
paper_id: "2604.05167"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "robust-optimization"
  - "energy-systems"
  - "differentiable-programming"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-08T04:57:27Z"
created_at: "2026-04-08T04:57:27Z"
---

# End-to-End Learning of Correlated Operating Reserve Requirements in Security-Constrained Economic Dispatch

**Authors**: Owen Shen, Hung-po Chao, Haihao Lu, Patrick Jaillet
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.05167](https://arxiv.org/abs/2604.05167)

## Summary

This paper introduces an end-to-end learning framework for designing correlated operating reserve requirements in Security-Constrained Economic Dispatch (SCED). By reformulating the bilevel robust optimization problem into a differentiable single-stage objective, the method optimizes ellipsoidal uncertainty sets by leveraging KKT and dual information from the SCED solver. The framework incorporates a smoothed quantile-sensitivity estimator and split conformal calibration, ensuring both finite-sample coverage guarantees and efficient task-driven gradient estimation. Experimental results on the IEEE 118-bus system demonstrate significant cost savings over baseline methods while maintaining required reliability levels.

## Key Contributions

- Formulates correlated reserve-set design as an end-to-end differentiable robust optimization problem by profiling coverage constraints into a shape-dependent radius.
- Enables task-gradient computation for SCED parameters using KKT/dual information, avoiding direct differentiation through the optimization solver.
- Achieves a 4.8% reduction in dispatch cost on the IEEE 118-bus system compared to traditional sample covariance benchmarks while ensuring strict coverage requirements.

## Open Questions & Future Work

- [[unified-sced-reserve-optimization]]

## Archivist Review

I reviewed the proposed end-to-end learning framework for SCED reserve requirements. While the method is technically sound, I have decided not to add new concepts to the vault as the core techniques (KKT-based gradient estimation, conformal calibration, and uncertainty set optimization) are well-represented or are too specific to the SCED domain. I approved one open question focused on the systemic unification of these components in power grid optimization, which addresses a clear, persistent research bottleneck.

### Approved Open Questions
- Unified SCED Reserve Optimization: This is a significant methodological challenge in power systems optimization; solving this provides a direct path to reducing operating costs while maintaining grid reliability in systems with high renewable penetration.

### Rejected Candidates
- [open_question] End-to-End Reserve-Set Design (`end-to-end-reserve-set-design-sced`) - other: The title was slightly redundant and a new slug was created to better reflect the broader system optimization problem.

## Links

- [Abstract](https://arxiv.org/abs/2604.05167)
- [PDF](https://arxiv.org/pdf/2604.05167)

