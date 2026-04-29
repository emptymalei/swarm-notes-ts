---
# CSL-compatible fields
title: "Deflation-Free Optimal Scoring"
author:
  - literal: "Sharmin Afroz"
  - literal: "Brendan Ames"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25664"

# Custom fields
paper_id: "2604.25664"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "classification"
  - "feature-selection"
  - "dimensionality-reduction"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dfsos"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:10:54Z"
created_at: "2026-04-29T05:10:54Z"
---

# Deflation-Free Optimal Scoring

**Authors**: Sharmin Afroz, Brendan Ames
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25664](https://arxiv.org/abs/2604.25664)

## Summary

The paper introduces Deflation-Free Sparse Optimal Scoring (DFSOS), a novel framework for linear discriminant analysis in high-dimensional settings. Unlike standard sequential deflation strategies that are prone to error propagation, DFSOS estimates all discriminant vectors simultaneously by enforcing a global orthogonality constraint. The method leverages Bregman iteration to decompose the objective into tractable subproblems, and convergence is theoretically supported under augmented Lagrangian conditions. Empirical results confirm that this simultaneous optimization leads to more robust performance in high-dimensional classification tasks.

## Key Contributions

- Introduces Deflation-Free Sparse Optimal Scoring (DFSOS), which simultaneously estimates all discriminant vectors using a global orthogonality constraint.
- Decomposes the high-dimensional discriminant analysis problem into tractable subproblems using Bregman iteration.
- Demonstrates that DFSOS achieves superior or comparable classification accuracy compared to traditional deflation-based methods on synthetic and time series datasets.

## Open Questions & Future Work

- [[efficient-algorithms-for-deflation-free-sos]]

## Key Concepts

- [[dfsos]]: A simultaneous estimation framework for sparse linear discriminant analysis using global orthogonality constraints to avoid deflation-based error propagation.

## Archivist Review

I approved the DFSOS concept as it defines a distinct methodological shift from sequential deflation in discriminant analysis. I also approved the open question regarding the efficiency of these algorithms because the trade-off between computational cost and error propagation is a central, recurring challenge in high-dimensional optimization. I rejected the convergence/consistency open question as it is relatively generic for new algorithmic proposals and does not represent a specific technical bottleneck unique to the problem class.

### Approved Concepts
- Deflation-Free Sparse Optimal Scoring (DFSOS): DFSOS addresses the error propagation issue inherent in sequential deflation-based strategies for discriminant analysis.

### Approved Open Questions
- Efficient Algorithms for DFSOS: Computational efficiency is a primary barrier to the practical deployment of deflation-free sparse discriminant analysis in high-dimensional settings.

## Links

- [Abstract](https://arxiv.org/abs/2604.25664)
- [PDF](https://arxiv.org/pdf/2604.25664)

