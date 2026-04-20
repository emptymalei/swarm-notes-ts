---
# CSL-compatible fields
title: "Simultaneous Inference for Covariance and Precision Matrices of Long-Range Dependent Time Series"
author:
  - literal: "Percy S. Zhai"
  - literal: "Mladen Kolar"
  - literal: "Wei Biao Wu"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.16219"

# Custom fields
paper_id: "2604.16219"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "triadic-block-approximation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:08:32Z"
created_at: "2026-04-20T05:08:32Z"
---

# Simultaneous Inference for Covariance and Precision Matrices of Long-Range Dependent Time Series

**Authors**: Percy S. Zhai, Mladen Kolar, Wei Biao Wu
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.16219](https://arxiv.org/abs/2604.16219)

## Summary

This paper addresses the challenge of inference for covariance and precision matrices in long-range dependent time series. The authors introduce a Berry-Esseen type Gaussian approximation that utilizes triadic block construction to provide finite-sample bounds for infinity norm estimation errors. Furthermore, they develop a block-sampling bootstrap method that maintains validity under strong temporal dependence. The proposed framework allows for consistent inference in ultra-high-dimensional settings without imposing rigid structural assumptions on the matrices.

## Key Contributions

- Establishes a Berry-Esseen type Gaussian approximation bound for the infinity norm of sample covariance estimation errors in long-range dependent settings.
- Proves the validity of a block-sampling bootstrap method specifically adapted for long-range temporal dependence.
- Demonstrates that the proposed inference framework remains valid in ultra-high-dimensional regimes (dimension growing sub-exponentially with sample size) without requiring structural assumptions.

## Open Questions & Future Work

- [[high-dimensional-precision-inference-without-sparsity]]

## Key Concepts

- [[triadic-block-approximation]]: A construction method for temporal blocks that facilitates Gaussian approximation and inference in long-range dependent time series.

## Archivist Review

I approved the triadic block approximation as a novel methodological contribution for handling long-range dependence, and a focused open question regarding the high-dimensional precision matrix estimation problem which is clearly identified as a limitation of the current results. The selection adheres to the policy of focusing on reusable methodologies and significant research bottlenecks. No datasets were approved as none were central to the contribution.

### Approved Concepts
- Triadic Block Approximation: Central technical novelty for enabling Gaussian approximation in the presence of long-range dependence.

### Approved Open Questions
- High-dimensional Precision Inference Limits: Provides a path toward assumption-free statistical inference in high-dimensional settings, which is essential for complex, non-structured data.

## Links

- [Abstract](https://arxiv.org/abs/2604.16219)
- [PDF](https://arxiv.org/pdf/2604.16219)

