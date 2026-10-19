---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Bayesian Hidden Markov Model with Singh--Maddala Emission Distributions for Heavy-Tailed Regime-Switching Time Series"
description: "This paper introduces HMMSM, a Hidden Markov Model featuring Singh-Maddala (Burr Type XII) emission distributions designed specifically for heavy-tailed and right-skewed regime-switching time series. The authors develop an adaptive Bayesian inference pipeline using Metropolis-within-Gibbs and Forward-Filtering Backward-Sampling to handle the non-conjugate nature of the emission parameters. Results on simulated data show that HMMSM accurately recovers parameters and outperforms several standard baseline models (e.g., Gaussian, Gamma, Weibull) in heavy-tailed scenarios. A real-world application to Irish monthly rainfall data reveals persistent wet and moderate regimes, though the model behaves similarly to simpler HMMs when tails are not extremely heavy."
resource: "https://arxiv.org/abs/2610.22656"
tags:
  - "heavy-tailed-distributions"
  - "hidden-markov-model"
  - "time-series"
  - "bayesian-inference"
  - "regime-analysis"
  - "probabilistic-forecasting"
  - "environmental-monitoring"
  - "statistical-modeling"
timestamp: "2026-10-19T04:39:59Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Safaa K. Kadhem"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22656"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "hmmsm"
    description: "A Hidden Markov Model variant employing the three-parameter Singh-Maddala (Burr Type XII) distribution as its emission density to capture heavy-tailed and skewed time series behavior."
datasets:
  []
open_questions:
  - name: "nonhomogeneous-extreme-regime-transitions"
    description: "Standard Hidden Markov Models for heavy-tailed data typically assume stationary transition probabilities. Incorporating time-varying covariates into the transition matrix, potentially via a multinomial logit link or Pólya-Gamma data augmentation, is required to model non-stationary persistence and capture how external signals influence the frequency and duration of extreme regimes."
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:39:59Z"
created_at: "2026-10-19T04:39:59Z"
---

# A Bayesian Hidden Markov Model with Singh--Maddala Emission Distributions for Heavy-Tailed Regime-Switching Time Series

**Authors**: Safaa K. Kadhem
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22656](https://arxiv.org/abs/2610.22656)

## Summary

This paper introduces HMMSM, a Hidden Markov Model featuring Singh-Maddala (Burr Type XII) emission distributions designed specifically for heavy-tailed and right-skewed regime-switching time series. The authors develop an adaptive Bayesian inference pipeline using Metropolis-within-Gibbs and Forward-Filtering Backward-Sampling to handle the non-conjugate nature of the emission parameters. Results on simulated data show that HMMSM accurately recovers parameters and outperforms several standard baseline models (e.g., Gaussian, Gamma, Weibull) in heavy-tailed scenarios. A real-world application to Irish monthly rainfall data reveals persistent wet and moderate regimes, though the model behaves similarly to simpler HMMs when tails are not extremely heavy.

## Key Contributions

- Proposes HMMSM, the first regime-switching Hidden Markov Model to utilize the three-parameter Singh-Maddala (Burr Type XII) distribution for emission modeling.
- Derives a fully Bayesian inference framework combining Forward-Filtering Backward-Sampling (FFBS) with adaptive Metropolis-within-Gibbs steps for robust parameter estimation.
- Demonstrates through simulation that HMMSM significantly outperforms Gaussian, Gamma, and Weibull HMMs on heavy-tailed benchmarks based on WAIC, DIC, and LOO criteria.
- Identifies two persistent meteorological regimes (Moderate and Wet) in Irish rainfall data, providing insights into seasonal coherence and regime persistence.

## Limitations

The study notes weak identifiability of the Singh-Maddala scale parameter and observes that HMMSM is statistically indistinguishable from HMM-Gamma on datasets with light tails, such as the Irish rainfall record.

## Open Questions & Future Work

- [[nonhomogeneous-extreme-regime-transitions]]

## Key Concepts

- [[hmmsm]]: A Hidden Markov Model variant employing the three-parameter Singh-Maddala (Burr Type XII) distribution as its emission density to capture heavy-tailed and skewed time series behavior.

## Archivist Review

Approved the HMMSM concept as it represents a novel use of the Burr Type XII distribution within the HMM framework for extreme values. Approved the open question regarding nonhomogeneous transitions as it addresses a fundamental limitation in regime-switching models for environmental and financial data. Rejected the dataset and sampling technique as they are either paper-local or standard methodologies.

### Approved Concepts
- HMMSM: HMMSM addresses a significant limitation in standard regime-switching models by incorporating a distribution capable of simultaneously modeling extreme right-skewness and slowly decaying upper tails.

### Approved Open Questions
- Nonhomogeneous Extreme-Regime Transitions: Developing nonhomogeneous transitions is essential for understanding how climate change or market volatility influences the duration and frequency of extreme meteorological or economic regimes.

### Rejected Candidates
- [concept] Adaptive Metropolis-within-Gibbs Sampler (`adaptive-metropolis-within-gibbs-sampler`) - not_novel: This is a standard statistical sampling technique and not a novel concept introduced by the paper.
- [dataset] irish-gridded-rainfall-record (`irish-gridded-rainfall-record`) - paper_local: This is a local application dataset used for case-study validation rather than a widely recognized benchmark for the ML community.
- [open_question] Zero-Inflated Singh-Maddala HMMs (`zero-inflated-singh-maddala-hmm`) - subcomponent_of_broader_mechanism: While valid, this is a specific extension of the proposed model; non-stationary transitions represent a broader and more impactful research direction for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2610.22656)
- [PDF](https://arxiv.org/pdf/2610.22656)

