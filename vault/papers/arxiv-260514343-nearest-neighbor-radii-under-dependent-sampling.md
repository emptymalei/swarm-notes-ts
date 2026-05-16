---
# CSL-compatible fields
title: "Nearest-Neighbor Radii under Dependent Sampling"
author:
  - literal: "Yuanyuan Gao"
  - literal: "Yilong Hou"
  - literal: "Zhexiao Lin"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14343"

# Custom fields
paper_id: "2605.14343"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "nearest-neighbor-methods"
  - "geometric-theory"
  - "high-dimensional-data"
architectures:
  []
datasets:
  []
concept_slugs:
  - "nearest-neighbor-radii-under-dependent-sampling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:13:14Z"
created_at: "2026-05-16T05:13:14Z"
---

# Nearest-Neighbor Radii under Dependent Sampling

**Authors**: Yuanyuan Gao, Yilong Hou, Zhexiao Lin
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14343](https://arxiv.org/abs/2605.14343)

## Summary

This paper investigates the geometric properties of nearest-neighbor radii when observations are sampled dependently rather than independently. The authors provide theoretical guarantees, including almost sure convergence under polynomial mixing and non-asymptotic moment bounds under geometric mixing, that explicitly account for the local intrinsic dimension of the data. These findings extend the applicability of k-nearest neighbor methods to high-dimensional manifold-concentrated data with temporal or spatial dependencies, as validated through synthetic and time-series experiments.

## Key Contributions

- Derived distribution-free almost sure convergence results for nearest-neighbor radii under polynomial mixing conditions.
- Established sharp non-asymptotic moment bounds for nearest-neighbor radii under geometric mixing, revealing dependence on intrinsic dimension rather than ambient dimension.
- Demonstrated that nearest-neighbor geometry remains statistically informative under dependent sampling through empirical validation on time-series benchmarks.

## Open Questions & Future Work

- [[uniform-convergence-nn-dependent-sampling]]

## Key Concepts

- [[nearest-neighbor-radii-under-dependent-sampling]]: A theoretical framework characterizing the scale of nearest-neighbor neighborhoods under strong mixing dependence.

## Archivist Review

The paper provides a rigorous theoretical foundation for analyzing nearest-neighbor geometry under dependent, non-i.i.d. data, which is highly relevant for time-series and manifold-concentrated data. I approved the core concept of NN radii under dependency and a corresponding open question regarding uniform consistency, as these are foundational, research-oriented, and widely applicable beyond this specific paper. No datasets were approved as none were presented as specific, uniquely named research contributions.

### Approved Concepts
- Nearest-neighbor radii under dependent sampling: Establishes a theoretical foundation for nearest-neighbor geometric properties under non-i.i.d. conditions, which is crucial for high-dimensional time-series analysis.

### Approved Open Questions
- Uniform Convergence under Dependence: A uniform theory is critical for providing global consistency and convergence rate guarantees for k-NN-based algorithms in dependent settings.

## Links

- [Abstract](https://arxiv.org/abs/2605.14343)
- [PDF](https://arxiv.org/pdf/2605.14343)

