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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "nearest-neighbor-radii-under-dependent-sampling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:24:55Z"
created_at: "2026-05-17T05:24:55Z"
---

# Nearest-Neighbor Radii under Dependent Sampling

**Authors**: Yuanyuan Gao, Yilong Hou, Zhexiao Lin
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14343](https://arxiv.org/abs/2605.14343)

## Summary

This paper investigates the geometric properties of nearest-neighbor radii when observations are sampled dependently, departing from the standard i.i.d. assumption. The authors analyze strongly mixing processes to derive conditions for almost sure convergence and non-asymptotic moment bounds. These theoretical findings reveal that nearest-neighbor scales remain meaningful under dependence and effectively capture local intrinsic dimensionality in high-dimensional manifolds. The paper validates these insights using both synthetic data and real-world time-series benchmarks.

## Key Contributions

- Establishes distribution-free almost sure convergence of nearest-neighbor radii under polynomial mixing conditions.
- Derives sharp non-asymptotic moment bounds under geometric mixing that scale with local intrinsic dimension rather than ambient dimension.
- Demonstrates that nearest-neighbor geometry remains statistically informative for high-dimensional dependent data through synthetic and time-series benchmarks.

## Open Questions & Future Work

- [[uniform-convergence-nn-dependent-sampling]]

## Key Concepts

- [[nearest-neighbor-radii-under-dependent-sampling]]: Theoretical analysis of nearest-neighbor neighborhood scales for strongly mixing dependent observations.

## Archivist Review

The paper introduces a mathematically rigorous framework for nearest-neighbor geometry under dependent sampling, which fills a significant theoretical gap. I have approved the core concept and the open question regarding uniform convergence as they provide foundational insights for temporal analysis beyond i.i.d. assumptions. No datasets were approved as none were identified as central or distinct enough to warrant a permanent vault entry.

### Approved Concepts
- Nearest-Neighbor Radii under Dependent Sampling: The paper provides a theoretical foundation for extending nearest-neighbor geometric properties beyond the standard i.i.d. assumption, which is critical for high-dimensional time-series and manifold-constrained data.

### Approved Open Questions
- Uniform convergence and dependence: This is foundational for validating the usage of local learning methods and graph-based estimators in dynamic, non-i.i.d. environments, which are ubiquitous in modern machine learning applications.

## Links

- [Abstract](https://arxiv.org/abs/2605.14343)
- [PDF](https://arxiv.org/pdf/2605.14343)

