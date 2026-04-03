---
created_at: '2026-04-03T05:20:31Z'
source_papers:
- '[[arxiv-2604.01500-copula-based-time-series-for-non-gaussian-and-non-markovian]]'
title: Consistency conditions for copula-based time series
---

**Background:** The parameter estimation for non-Markovian copula-based time series models involves latent variables that must be calculated iteratively, and conditions for the consistency of these estimators currently rely on high-level assumptions.

**Question / Future Work:** It remains unclear how to translate these high-level conditions for ergodicity and stationarity of the latent innovation and autoregressive processes into specific, actionable constraints on the parameters or structural properties of the chosen AR and MAG copulas. Establishing these more concrete conditions is essential for formalizing the consistency of maximum likelihood estimators in this model framework.

**Why It Matters:** This is a fundamental theoretical gap that prevents practitioners from verifying if their chosen model architecture and copula selection satisfy the requirements for consistent estimation in practice.

**Evidence:** Currently the conditions are on a high-level and future research directions could be to translate these high-level conditions to conditions on the copula parameters.