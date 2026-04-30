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
domain: "statistics"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dfsos"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:15:28Z"
created_at: "2026-04-30T05:15:28Z"
---

# Deflation-Free Optimal Scoring

**Authors**: Sharmin Afroz, Brendan Ames
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25664](https://arxiv.org/abs/2604.25664)

## Summary

This paper addresses the limitations of error propagation in traditional deflation-based Sparse Optimal Scoring (SOS) methods for high-dimensional discriminant analysis. The authors propose Deflation-Free Sparse Optimal Scoring (DFSOS), which simultaneously estimates all discriminant vectors under a global orthogonality constraint. The method leverages Bregman iteration to decompose the optimization into manageable subproblems and is proven to converge to stationary points of the augmented Lagrangian. Empirical results across synthetic and real-world time series datasets confirm that this simultaneous approach improves classification robustness.

## Key Contributions

- Introduces DFSOS, a simultaneous estimation framework for sparse discriminant analysis that replaces traditional sequential deflation strategies.
- Formulates the problem using Bregman iteration combined with global orthogonality-constrained optimization to ensure more robust convergence.
- Demonstrates through synthetic and time series experiments that DFSOS achieves superior or equivalent classification accuracy compared to existing deflation-based methods.

## Open Questions & Future Work

- [[efficient-algorithms-for-deflation-free-sos]]

## Key Concepts

- [[dfsos]]: A framework for sparse discriminant analysis that estimates all discriminant vectors simultaneously using global orthogonality constraints and Bregman iteration.

## Archivist Review

Approved the core method, DFSOS, as it provides a clear, reusable framework for avoiding deflation-based error propagation in high-dimensional discriminant analysis. I approved the question regarding computational efficiency as it represents a significant, long-standing bottleneck in high-dimensional statistics. The convergence rate question was rejected as overly routine for this type of optimization paper.

### Approved Concepts
- Deflation-Free Sparse Optimal Scoring (DFSOS): It overcomes error propagation and suboptimality issues inherent in traditional sequential deflation-based discriminant analysis.

### Approved Open Questions
- Efficient algorithms for DFSOS: Computational efficiency is a major bottleneck for the adoption of deflation-free optimization in high-dimensional statistical learning.

### Rejected Candidates
- [open_question] Convergence rate of DFSOS (`dfsos-convergence-rate-analysis`) - other: Convergence rate analysis is a routine theoretical objective rather than a substantial, tracked bottleneck for the field.

## Links

- [Abstract](https://arxiv.org/abs/2604.25664)
- [PDF](https://arxiv.org/pdf/2604.25664)

