---
# CSL-compatible fields
title: "Accelerated kriging interpolation for real-time grid frequency forecasting"
author:
  - literal: "Carlos Moreno-Blazquez"
  - literal: "Filiberto Fele"
  - literal: "Teodoro Alamo"
issued:
  date-parts:
    - [2026, 4, 3]
url: "https://arxiv.org/abs/2604.02932"

# Custom fields
paper_id: "2604.02932"
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
processed_at: "2026-04-06T05:02:13Z"
created_at: "2026-04-06T05:02:13Z"
---

# Accelerated kriging interpolation for real-time grid frequency forecasting

**Authors**: Carlos Moreno-Blazquez, Filiberto Fele, Teodoro Alamo
**Date**: 2026-04-03
**Paper ID**: [arxiv:2604.02932](https://arxiv.org/abs/2604.02932)

## Summary

This paper presents an accelerated kriging-based interpolation algorithm designed for high-speed, real-time grid frequency forecasting. By leveraging the inherent numerical structure of the kriging formulation, the proposed method bypasses standard computational bottlenecks to provide accurate predictions in under a second. The approach is validated using a simulated distribution grid, showing promise for improving stability and control in power systems with high renewable energy penetration.

## Key Contributions

- Introduces a nonparametric kriging-based prediction algorithm tailored for grid frequency forecasting.
- Exploits the numerical structure of the kriging formulation to achieve sub-second computation times suitable for real-time grid control.
- Demonstrates the effectiveness of the method in a simulated distribution grid environment.

## Open Questions & Future Work

- [[admm-penalty-parameter-tuning]]

## Archivist Review

The paper introduces a speed-optimized implementation of a known interpolation technique for a specific power grid application. No new methodological concepts were identified that transcend the domain-specific implementation. The proposed open question on ADMM tuning is a general optimization concern and does not specifically address a time-series or forecasting bottleneck, thus it was rejected.

### Approved Open Questions
- ADMM penalty parameter selection: The choice of the penalty parameter significantly affects both the numerical stability and the convergence speed of the algorithm, which is critical for real-time applications where stringent computation time constraints exist.

### Rejected Candidates
- [open_question] ADMM penalty parameter selection (`admm-penalty-parameter-tuning`) - generic: While this is a valid challenge for optimization, it is a well-known, general issue in numerical analysis rather than a novel, domain-specific open question in time series forecasting or the paper's specific scope.

## Links

- [Abstract](https://arxiv.org/abs/2604.02932)
- [PDF](https://arxiv.org/pdf/2604.02932)

