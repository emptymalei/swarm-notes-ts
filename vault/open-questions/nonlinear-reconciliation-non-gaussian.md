---
created_at: '2026-05-02T05:11:56Z'
source_papers:
- '[[arxiv-260426668-nonlinear-probabilistic-forecast-reconciliation]]'
title: Non-Gaussian nonlinear reconciliation
---

**Background:** Probabilistic forecast reconciliation methods under nonlinear constraints, specifically those based on the Unscented Kalman Filter (UKF), often rely on Gaussian assumptions about the free-level forecast distribution to remain computationally efficient.

**Question / Future Work:** Research is required to develop robust nonlinear reconciliation techniques that can handle non-Gaussian and intermittent/discrete time series data, as the current UKF-based approach is strictly constrained by its underlying Gaussian assumption.

**Why It Matters:** The reliance on Gaussianity in UKF-based reconciliation prevents the application of this efficient framework to common real-world data types like intermittent or discrete time series.