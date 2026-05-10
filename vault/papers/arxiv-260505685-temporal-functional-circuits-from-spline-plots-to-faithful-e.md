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
domain: "time-series"
tags:
  - "forecasting"
  - "interpretability"
  - "mechanistic-interpretability"
architectures:
  []
datasets:
  []
concept_slugs:
  - "temporal-functional-circuits"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:20:58Z"
created_at: "2026-05-10T05:20:58Z"
---

# Temporal Functional Circuits: From Spline Plots to Faithful Explanations in KAN Forecasting

**Authors**: Naveen Mysore
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05685](https://arxiv.org/abs/2605.05685)

## Summary

This paper presents Temporal Functional Circuits, an interpretability framework for Kolmogorov-Arnold Networks (KAN) applied to time-series forecasting. By utilizing a gated residual architecture that separates linear base components from sparse KAN spline corrections, the model achieves competitive accuracy while enabling edge-level attribution and faithfulness validation. The approach effectively maps edge functions to specific input lags and demonstrates that learned spline shapes are essential for capturing signal complexity beyond standard linear activations.

## Key Contributions

- Introduces Temporal Functional Circuits to transform KAN latent edge functions into temporally grounded, faithful explanations.
- Develops a gated residual KAN architecture that achieves 59% lower MSE than linear baselines on regime-switching signals.
- Demonstrates that learned B-spline edge functions carry predictive value beyond base activation through edge-level intervention experiments.

## Open Questions & Future Work

- [[automated-gate-regularization-selection]]
- [[faithfulness-vs-causal-discovery]]

## Key Concepts

- [[temporal-functional-circuits]]: A framework for transforming Kolmogorov-Arnold Network edge functions into temporally grounded and faithful explanations for time-series forecasting.

## Archivist Review

I approved the Temporal Functional Circuits framework as a key contribution to KAN interpretability in time-series. The open questions regarding gate regularization and the distinction between internal faithfulness and external causality are substantial bottlenecks in deploying these architectures safely. No datasets were approved as none were cited as primary, novel contributions.

### Approved Concepts
- Temporal Functional Circuits: It provides a systematic framework for interpreting and validating latent functional edges in KAN architectures for time-series.

### Approved Open Questions
- Automated Gate Regularization Selection: The lack of an automated selection mechanism limits the robustness and ease of deployment of gated KAN architectures.
- Faithfulness vs. Causal Discovery: Distinguishing between predictive faithfulness and true causal explanation is critical for high-stakes forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2605.05685)
- [PDF](https://arxiv.org/pdf/2605.05685)

