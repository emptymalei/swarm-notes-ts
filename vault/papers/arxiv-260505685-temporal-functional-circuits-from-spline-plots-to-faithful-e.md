---
# CSL-compatible fields
title: "Temporal Functional Circuits: From Spline Plots to Faithful Explanations in KAN Forecasting"
author:
  - literal: "Naveen Mysore"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05685"

# Custom fields
paper_id: "2605.05685"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "temporal-functional-circuits"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:12:51Z"
created_at: "2026-05-09T05:12:51Z"
---

# Temporal Functional Circuits: From Spline Plots to Faithful Explanations in KAN Forecasting

**Authors**: Naveen Mysore
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05685](https://arxiv.org/abs/2605.05685)

## Summary

This paper presents Temporal Functional Circuits, a framework designed to enhance the interpretability of Kolmogorov-Arnold Networks (KANs) in time-series forecasting. By employing a gated residual structure that separates linear trends from sparse KAN-based corrections, the method allows for rigorous faithfulness testing via edge-level interventions. Experimental results on eight benchmarks and synthetic datasets show that the architecture provides competitive performance while enabling mechanistic insights into how specific input lags influence predictions.

## Key Contributions

- Introduces Temporal Functional Circuits, a framework providing faithful, temporally grounded explanations for KAN-based time-series forecasting.
- Achieves 59% lower MSE on regime-switching signals compared to linear-only models using a gated residual KAN architecture.
- Demonstrates through edge-level interventions that learned B-spline components contribute significant predictive value beyond base activations.

## Open Questions & Future Work

- [[adaptive-gate-regularization]]

## Key Concepts

- [[temporal-functional-circuits]]: A KAN-based framework for time-series forecasting that decomposes predictions into linear base and nonlinear spline corrections, enabling edge-level faithfulness testing.

## Archivist Review

I approved the overarching framework of Temporal Functional Circuits, as it provides a novel and reusable methodology for interpreting Kolmogorov-Arnold Networks in a temporal context. I also approved the open question regarding adaptive gate regularization, as it addresses a significant, recurring bottleneck in training sparse, gated architectures. I rejected the gated residual KAN as a standalone concept because it is a subcomponent of the Temporal Functional Circuits framework.

### Approved Concepts
- Temporal Functional Circuits: It bridges the gap between Kolmogorov-Arnold Networks (KANs) and time-series interpretability by grounding edge-level spline functions in specific temporal lags.

### Approved Open Questions
- Adaptive Gate Regularization: Automated gate regulation would facilitate the scaling of gated architectures across diverse forecasting domains without the need for exhaustive manual validation.

### Rejected Candidates
- [concept] Gated Residual KAN (`gated-residual-kan`) - subcomponent_of_broader_mechanism: This is a subcomponent architecture of the overarching 'Temporal Functional Circuits' framework.

## Links

- [Abstract](https://arxiv.org/abs/2605.05685)
- [PDF](https://arxiv.org/pdf/2605.05685)

