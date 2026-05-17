---
# CSL-compatible fields
title: "Multi-regime Markov-switching models with time-varying transition probabilities: An application to U.S. Treasury yields"
author:
  - literal: "Samuel Modée"
  - literal: "Yushu Li"
  - literal: "Sjur Westgaard"
  - literal: "Stein Andreas Bethuelsen"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14976"

# Custom fields
paper_id: "2605.14976"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting-horizon"
  - "seasonality-handling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "generalized-autoregressive-score-gas-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:23:03Z"
created_at: "2026-05-17T05:23:03Z"
---

# Multi-regime Markov-switching models with time-varying transition probabilities: An application to U.S. Treasury yields

**Authors**: Samuel Modée, Yushu Li, Sjur Westgaard, Stein Andreas Bethuelsen
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14976](https://arxiv.org/abs/2605.14976)

## Summary

This paper extends Markov-switching models with time-varying transition probabilities (TVTP) to a general K-regime framework using Generalized Autoregressive Score (GAS) dynamics. Through Monte Carlo simulations and an empirical application to U.S. Treasury yields, the authors demonstrate that while point forecasts are robust to misspecification, regime characterization requires careful specification of the transition dynamics. The research identifies a persistent identifiability challenge regarding the GAS score coefficient and provides an R package to facilitate implementation.

## Key Contributions

- Extends the two-regime GAS model to a general K-regime setting with regime-specific means and variances.
- Demonstrates that while one-step point forecasts are robust to TVTP misspecification, filtered regime probabilities are highly sensitive.
- Identifies a statistical non-identifiability issue in the GAS score coefficient due to a ridge in the joint likelihood surface of variance and score parameters.
- Provides an open-source R package, multiregimeTVTP, for simulation and estimation of TVTP-MS models.

## Open Questions & Future Work

- [[gas-model-parameter-identifiability]]

## Key Concepts

- [[generalized-autoregressive-score-gas-model]]: A time-series model that updates parameters using the score of the likelihood function.

## Archivist Review

I approved the Generalized Autoregressive Score (GAS) model as it is a core econometric framework for time-varying parameters that benefits from being tracked in the vault. I also approved the open question regarding GAS parameter identifiability because the paper clearly documents a persistent failure mode (likelihood surface ridges) that affects empirical convergence and stability across applications. The candidate for TVTP link function impact was rejected as it is a broad area of inquiry rather than a specific, well-defined open bottleneck.

### Approved Concepts
- Generalized Autoregressive Score (GAS) model: The paper provides a significant extension to K-regimes and investigates identifiability issues within this framework.

### Approved Open Questions
- GAS model parameter identifiability: This issue directly prevents the successful application of the GAS framework in empirical settings, even when the model is theoretically sound, and necessitates either improved optimization strategies or a re-evaluation of the score-driven mechanism for transition probabilities.

## Links

- [Abstract](https://arxiv.org/abs/2605.14976)
- [PDF](https://arxiv.org/pdf/2605.14976)

