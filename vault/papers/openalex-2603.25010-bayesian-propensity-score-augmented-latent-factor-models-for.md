---
# CSL-compatible fields
title: "Bayesian Propensity Score-Augmented Latent Factor Models for Causal Inference with Time-Series Cross-Sectional Data"
author:
  - literal: "Licheng Liu"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25010"

# Custom fields
paper_id: "2603.25010"
paper_source: "openalex"
domain: "causal-inference"
tags:
  - "causal-inference"
  - "bayesian-methods"
  - "latent-variables"
  - "time-series-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "bayesian-propensity-factor-model"
  - "approximate-bayesian-feedback-procedure"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:15:29Z"
created_at: "2026-03-29T20:15:29Z"
---

# Bayesian Propensity Score-Augmented Latent Factor Models for Causal Inference with Time-Series Cross-Sectional Data

**Authors**: Licheng Liu
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25010](https://arxiv.org/abs/2603.25010)

## Summary

This paper introduces a Bayesian propensity score-augmented latent factor model designed for causal inference on time-series cross-sectional data. The model enhances existing methods by incorporating latent factor loadings to explicitly model the treatment assignment mechanism and allowing flexible integration of the propensity score, such as through stratification, which facilitates more credible within-strata comparisons. For estimation and inference, the authors propose an approximate Bayesian procedure to mitigate the notorious model feedback problem common in Bayesian propensity score analyses. The efficacy of this new framework is validated through Monte Carlo simulations and an empirical study investigating the impact of political connections on firm value.

## Key Contributions

- Development of a Bayesian propensity score-augmented latent factor model specifically tailored for causal inference in time-series cross-sectional data settings.
- The framework explicitly models treatment assignment via latent factor loadings and flexibly incorporates the propensity score (e.g., via stratification) in the outcome model.
- Introduction of an approximate Bayesian procedure to efficiently estimate the model and overcome the common model feedback problem inherent in Bayesian propensity score analysis.
- Demonstration of superior performance compared to existing methods via Monte Carlo simulations and an empirical application on political connections and firm value.

## Limitations

The abstract does not explicitly state limitations, but the reliance on an 'approximate' Bayesian procedure suggests potential trade-offs in exactness versus computational feasibility.

## Open Questions & Future Work

- [[parametric-sensitivity-propensity-score-augmentation]]
- [[achieving-double-robustness-latent-factors]]

## Key Concepts

- [[bayesian-propensity-factor-model]]: A novel Bayesian causal inference framework that merges latent factor modeling with propensity score stratification to handle time-series cross-sectional data.
- [[approximate-bayesian-feedback-procedure]]: An approximate Bayesian inference procedure designed to resolve the model feedback issue that arises when propensity scores are estimated within a Bayesian causal model.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 2 concept(s), 2 open question(s), and 0 dataset(s), with 0 rejected candidate note(s).

### Approved Concepts
- Bayesian Propensity Score-Augmented Latent Factor Model: This is the primary novel statistical framework proposed in the paper, integrating latent factor modeling with propensity score methods for causal inference.
- Approximate Bayesian Procedure for Model Feedback: This is the specific estimation technique developed to solve a known methodological challenge (model feedback) within Bayesian propensity score analysis.

### Approved Open Questions
- Parametric sensitivity of PS-LFM: The reliance on parametric specifications for how propensity scores interact with latent factors limits the model's robustness to true data-generating processes where this relationship is complex or unknown.
- Achieving Double Robustness: Double robustness is a desirable property in causal inference as it increases robustness against model misspecification in either the treatment mechanism or the outcome process. Losing this property due to linking latent factor estimation across models is a significant methodological limitation.

## Links

- [Abstract](https://arxiv.org/abs/2603.25010)
- [PDF](https://arxiv.org/pdf/2603.25010)

