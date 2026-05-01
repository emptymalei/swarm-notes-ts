---
created_at: '2026-05-01T05:24:52Z'
source_papers:
- '[[arxiv-260426668-nonlinear-probabilistic-forecast-reconciliation]]'
title: Non-Gaussian Nonlinear Reconciliation Methods
---

**Background:** Reconciliation methods via conditioning often assume Gaussianity of the free-level time series, which limits their application. Extending these methods to non-Gaussian, intermittent, or discrete scenarios remains an open challenge.

**Question / Future Work:** Existing Unscented Kalman Filter-based approaches for nonlinear probabilistic forecast reconciliation assume a Gaussian distribution for the free-level time series, making them unsuitable for intermittent or discrete time series. Extending these methods to non-Gaussian or discrete settings remains an unresolved research problem.

**Why It Matters:** Many real-world time series, such as those representing counts or intermittent data, do not follow Gaussian distributions, limiting the applicability of the currently proposed UKF-based reconciliation methods.