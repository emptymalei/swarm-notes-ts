---
# CSL-compatible fields
title: "Fisher Information and Dynamical Sampling I"
author:
  - literal: "Mattia Carrino"
  - literal: "Stefan Hohenegger"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24499"

# Custom fields
paper_id: "2604.24499"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "information-theory"
  - "dynamical-systems"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:14:22Z"
created_at: "2026-04-28T05:14:22Z"
---

# Fisher Information and Dynamical Sampling I

**Authors**: Mattia Carrino, Stefan Hohenegger
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24499](https://arxiv.org/abs/2604.24499)

## Summary

This paper investigates the theoretical limitations of reconstructing dynamical systems from sampled time-series data using Fisher information as the primary metric. The authors derive the asymptotic bias of the Fisher information estimator for finite sample sizes, providing a framework to quantify reconstruction accuracy. Furthermore, they demonstrate that clustering degrees of freedom effectively mitigates this bias and propose a quantitative assessment of the associated information loss. The approach is validated through a compartmental model, offering a general methodology for analyzing high-dimensional dynamical systems.

## Key Contributions

- Derives an analytical expression for the bias of the Fisher information estimator for dynamical system reconstructions from discrete time-series measurements.
- Demonstrates that clustering degrees of freedom in a dynamical system reduces reconstruction bias, thereby improving estimation accuracy given finite sample sizes.
- Provides a quantitative metric for assessing information loss resulting from dimension reduction (clustering) in general dynamical systems.

## Open Questions & Future Work

- [[bias-reduction-fisher-info-dynamical-sampling]]

## Archivist Review

The paper provides a formal theoretical derivation of the bias of Fisher information estimators in dynamical sampling. I have approved the open question regarding bias-optimized estimators as it identifies a clear, non-trivial research path. I rejected the concept candidates because they are central theoretical results of this specific mathematical investigation rather than reusable methodological building blocks.

### Approved Open Questions
- Bias-optimized Fisher information estimators: This question is fundamental for the reliability of information-geometric analysis in real-world dynamical systems where measurement precision and sampling frequency are constrained. Defining optimal estimators is essential to bridge the gap between idealized information-geometric theory and practical data-driven modeling.

### Rejected Candidates
- [concept] Fisher information bias estimation (`fisher-information-bias-estimation`) - paper_local: This represents the core finding of the paper rather than a distinct, reusable methodology or framework concept.
- [concept] Information loss in clustered dynamical systems (`information-loss-clustering-degrees-of-freedom`) - not_novel: The concept of using clustering to manage dimensionality is well-established in dynamical systems, and the specific information-loss assessment here is a derivation tailored to the paper's theoretical framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.24499)
- [PDF](https://arxiv.org/pdf/2604.24499)

