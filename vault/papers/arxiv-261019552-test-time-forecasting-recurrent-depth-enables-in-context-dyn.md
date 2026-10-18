---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Test-Time Forecasting: Recurrent Depth Enables In-Context Dynamics Prediction"
description: "The paper introduces Test-Time Forecasting (TTF), a framework that enables foundation models for dynamical systems to perform generalizable in-context prediction. By establishing a theoretical link between linear attention and (Extended) Dynamic Mode Decomposition, the authors design lightweight models that use gradient descent iterations as a form of recurrent depth at inference time. This approach allows a model trained solely for one-step prediction on ODEs and PDEs to successfully generalize to unseen, out-of-distribution system dynamics during long-term autoregressive rollouts."
resource: "https://arxiv.org/abs/2610.19552"
tags:
  - "time-series"
  - "forecasting"
  - "dynamical-systems"
  - "in-context-learning"
  - "recurrent-depth"
  - "linear-attention"
  - "physics-informed-learning"
  - "ood-generalization"
  - "foundation-models"
timestamp: "2026-10-18T00:45:52Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jeffrey B. Lai"
  - literal: "John Quinn"
  - literal: "Anthony Bao"
  - literal: "William Gilpin"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19552"
paper_source: "arxiv"
architectures:
  - "transformer"
concepts:
  - name: "test-time-forecasting"
    description: "A framework that enables one-step forecasting models to generalize to unseen dynamical systems by using gradient descent iterations at inference time as recurrent depth."
  - name: "linear-attention-dmd-equivalence"
    description: "A theoretical mapping showing that linear attention mechanisms are capable of emulating the system propagators identified by Dynamic Mode Decomposition."
datasets:
  []
open_questions:
  - name: "ttf-nonlinear-scaling"
    description: "Investigating whether the theoretical mapping between linear attention and DMD can be extended to represent the infinite-dimensional Koopman operator for complex nonlinear systems, or if it is fundamentally constrained by the linearity of the attention mechanism."
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:45:52Z"
created_at: "2026-10-18T00:45:52Z"
---

# Test-Time Forecasting: Recurrent Depth Enables In-Context Dynamics Prediction

**Authors**: Jeffrey B. Lai, John Quinn, Anthony Bao, William Gilpin
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19552](https://arxiv.org/abs/2610.19552)

## Summary

The paper introduces Test-Time Forecasting (TTF), a framework that enables foundation models for dynamical systems to perform generalizable in-context prediction. By establishing a theoretical link between linear attention and (Extended) Dynamic Mode Decomposition, the authors design lightweight models that use gradient descent iterations as a form of recurrent depth at inference time. This approach allows a model trained solely for one-step prediction on ODEs and PDEs to successfully generalize to unseen, out-of-distribution system dynamics during long-term autoregressive rollouts.

## Key Contributions

- Establishes a formal theoretical link between linear attention mechanisms and (Extended) Dynamic Mode Decomposition (DMD) for emulating dynamical system propagators.
- Proposes the Test-Time Forecasting (TTF) framework, which utilizes iterations of gradient descent at inference time as a form of recurrent depth to adapt to new dynamics.
- Demonstrates that lightweight TTF models trained only on one-step prediction for ODEs and PDEs can generalize to out-of-distribution (OOD) systems during long-term autoregressive rollouts.
- Shows that gradient-based recurrent depth enables in-context forecasting of unseen dynamical systems without needing massive foundation model parameters.

## Limitations

The framework's performance on high-dimensional chaotic systems or systems with significant noise was not detailed in the abstract.

## Open Questions & Future Work

- [[ttf-nonlinear-scaling]]

## Key Concepts

- [[test-time-forecasting]]: A framework that enables one-step forecasting models to generalize to unseen dynamical systems by using gradient descent iterations at inference time as recurrent depth.
- [[linear-attention-dmd-equivalence]]: A theoretical mapping showing that linear attention mechanisms are capable of emulating the system propagators identified by Dynamic Mode Decomposition.

## Archivist Review

I approved the core framework (Test-Time Forecasting) and its foundational theoretical link (Linear Attention-DMD Equivalence) as they provide significant reusable insights for the Scientific ML and forecasting communities. I approved the open question regarding nonlinear scaling as it addresses a fundamental bottleneck in applying linear-operator-based methods to chaotic physics. I rejected the latency tradeoff as it is a generic concern for any test-time optimization method.

### Approved Concepts
- Test-Time Forecasting: Introduces a novel paradigm for in-context dynamics prediction that uses optimization-based recurrent depth rather than just scaling model size.
- Linear Attention-DMD Equivalence: Provides a formal theoretical bridge between the mechanism of transformers (linear attention) and a foundational technique in dynamical systems (DMD).

### Approved Open Questions
- Scaling TTF to Nonlinear Chaos: Understanding the limits of this equivalence determines whether TTF can be applied to complex physical simulations like turbulence or chaotic oscillators.

### Rejected Candidates
- [concept] Looped Transformers (`looped-transformers`) - duplicate_existing: Looped transformers are an existing architectural pattern already established in literature for iterative computation and are not a novel contribution of this specific paper.
- [open_question] Inference Latency vs. Recurrent Depth Tradeoff (`ttf-inference-latency-tradeoff`) - generic: This is a generic trade-off inherent to all test-time optimization methods and does not represent a unique research bottleneck specific to the paper's core insights.

## Links

- [Abstract](https://arxiv.org/abs/2610.19552)
- [PDF](https://arxiv.org/pdf/2610.19552)

