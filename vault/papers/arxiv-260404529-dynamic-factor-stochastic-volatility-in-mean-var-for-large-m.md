---
# CSL-compatible fields
title: "Dynamic Factor Stochastic Volatility-in-Mean VAR for Large Macroeconomic Panels"
author:
  - literal: "Daichi Hiraki"
  - literal: "Siddhartha Chib"
  - literal: "Yasuhiro Omori"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.04529"

# Custom fields
paper_id: "2604.04529"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "fred-qd"
concept_slugs:
  - "dynamic-factor-stochastic-volatility-in-mean-model"
dataset_slugs:
  - "fred-qd"
skill: "GeneralMLSkill"
processed_at: "2026-04-07T04:53:26Z"
created_at: "2026-04-07T04:53:26Z"
---

# Dynamic Factor Stochastic Volatility-in-Mean VAR for Large Macroeconomic Panels

**Authors**: Daichi Hiraki, Siddhartha Chib, Yasuhiro Omori
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.04529](https://arxiv.org/abs/2604.04529)

## Summary

This paper proposes a dynamic factor stochastic volatility-in-mean (SVM) framework for VAR models to capture the impact of time-varying uncertainty on macroeconomic variables. By incorporating a latent factor structure for volatility that also influences the conditional mean, the model provides a tractable way to handle large macroeconomic panels. An efficient MCMC algorithm is developed for estimation, and empirical results on the FRED-QD dataset confirm that the proposed approach improves forecast accuracy during major economic disruptions compared to benchmark stochastic volatility models.

## Key Contributions

- Introduces a dynamic factor stochastic volatility-in-mean (SVM) VAR model that integrates common volatility factors into both conditional variance and conditional mean dynamics.
- Derives an efficient Markov chain Monte Carlo (MCMC) algorithm for estimation, enabling tractability in high-dimensional non-Gaussian settings.
- Demonstrates superior predictive performance over standard stochastic volatility VAR benchmarks, particularly during periods of high economic volatility like the 2008 financial crisis.

## Open Questions & Future Work

- [[time-varying-in-mean-coefficient-estimation]]
- [[structural-inference-for-high-dimensional-factor-models]]

## Key Concepts

- [[dynamic-factor-stochastic-volatility-in-mean-model]]: A time-series framework where latent volatility factors affect both conditional variance and the conditional mean of a vector autoregression.

## Archivist Review

The paper introduces a structured approach to high-dimensional time series modeling that connects latent volatility factors to both mean and variance dynamics. I approved the generalized framework concept and the dataset, and retained two open questions that highlight the critical transition from purely predictive high-dimensional models to structural and time-varying inference.

### Approved Concepts
- Dynamic Factor Stochastic Volatility-in-Mean Model: It provides a scalable mechanism for modeling high-dimensional time series where latent volatility factors influence both conditional variance and the mean outcome.

### Approved Open Questions
- Time-varying In-mean Coefficients: Understanding the temporal stability of the risk-return trade-off is critical for structural inference and more robust long-horizon forecasting.
- Structural Inference for Factor Models: Bridging the gap between predictive models and structural inference is essential for policy-oriented applications of high-dimensional machine learning.

### Rejected Candidates
- [concept] Dynamic Factor Stochastic Volatility-in-Mean VAR (`dynamic-factor-svm-var`) - subcomponent_of_broader_mechanism: This is a specific model implementation (VAR) of the broader architectural concept, which is better captured by the generalized model name.

## Datasets

- [[fred-qd]]

## Links

- [Abstract](https://arxiv.org/abs/2604.04529)
- [PDF](https://arxiv.org/pdf/2604.04529)

