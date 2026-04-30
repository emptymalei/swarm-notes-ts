---
created_at: '2026-04-30T05:15:50Z'
source_papers:
- '[[arxiv-260425499-evotsc-evolving-feature-learning-models-for-time-series-clas]]'
title: Multivariate Time Series Classification
---

**Background:** Time series classification (TSC) often involves multiple dependent variables, necessitating representations that account for inter-variable correlations. Existing evolutionary feature learning approaches for TSC primarily focus on univariate data where such correlations are absent.

**Question / Future Work:** Extending evolutionary feature learning to handle multivariate time series requires developing cross-variate operators within the program structure capable of explicitly capturing correlations among multiple variables.

**Why It Matters:** Many real-world TSC problems are inherently multivariate; failure to capture inter-variable dependencies restricts the utility of evolutionary search frameworks.

**Evidence:** Extending EvoTSC to handle multivariate time series, where cross-variate dependencies carry additional information, is a natural and important direction.