---
# CSL-compatible fields
title: "Amortized Filtering and Smoothing with Conditional Normalizing Flows"
author:
  - literal: "Tiangang Cui"
  - literal: "Xiaodong Feng"
  - literal: "Chenlong Pei"
  - literal: "Xiaoliang Wan"
  - literal: "Tao Zhou"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07169"

# Custom fields
paper_id: "2604.07169"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "bayesian-inference"
  - "normalizing-flows"
architectures:
  []
datasets:
  []
concept_slugs:
  - "amortized-filtering-and-smoothing-framework-afsf"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:53:23Z"
created_at: "2026-04-09T04:53:23Z"
---

# Amortized Filtering and Smoothing with Conditional Normalizing Flows

**Authors**: Tiangang Cui, Xiaodong Feng, Chenlong Pei, Xiaoliang Wan, Tao Zhou
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07169](https://arxiv.org/abs/2604.07169)

## Summary

This paper introduces AFSF, a unified framework for Bayesian filtering and smoothing in high-dimensional nonlinear dynamical systems using conditional normalizing flows. The approach employs a recurrent encoder to map observation histories into fixed-dimensional summary statistics, which then condition both forward flows (for filtering) and backward flows (for transition kernels). By coupling these flows, the model improves smoothing accuracy and supports extrapolation beyond training horizons. A flow-based particle filter variant is also provided to facilitate diagnostic checks when model factors are accessible.

## Key Contributions

- Proposes AFSF, a unified framework that utilizes recurrent encoders and conditional normalizing flows for amortized Bayesian filtering and smoothing.
- Demonstrates the use of shared summary statistics to learn both forward and backward flows, enabling accurate trajectory-level smoothing and extrapolation.
- Introduces a flow-based particle filtering variant that enables explicit ESS-based diagnostics for state estimation.

## Open Questions & Future Work

- [[smoothing-error-accumulation-scaling]]

## Key Concepts

- [[amortized-filtering-and-smoothing-framework-afsf]]: A unified framework for Bayesian filtering and smoothing that uses recurrent encoders and conditional normalizing flows to approximate filtering distributions and backward kernels.

## Archivist Review

I have approved the core AFSF mechanism as a novel contribution to state-space modeling. I also retained the open question regarding smoothing error accumulation, as it highlights a fundamental limitation in iterative backward inference. I rejected the open question on encoder architectures as it describes a routine model-tuning task rather than a foundational research bottleneck.

### Approved Concepts
- Amortized Filtering and Smoothing Framework (AFSF): Introduces a novel architecture for state estimation that combines recurrent encoding with forward/backward flow-based distribution estimation.

### Approved Open Questions
- Smoothing Error Accumulation Scaling: Understanding and overcoming error accumulation in backward recursion is essential for extending amortized filtering and smoothing frameworks to very high-dimensional spatio-temporal systems.

### Rejected Candidates
- [open_question] Advanced Encoders for Filtering (`advanced-encoders-filtering`) - generic: Proposing to replace one architecture with another (e.g., RNN to Transformer) is a common incremental improvement rather than a deep, unsolved research question for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.07169)
- [PDF](https://arxiv.org/pdf/2604.07169)

