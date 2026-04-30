---
created_at: '2026-04-30T05:13:05Z'
source_papers:
- '[[arxiv-260426668-nonlinear-probabilistic-forecast-reconciliation]]'
title: Non-Gaussian nonlinear probabilistic reconciliation
---

**Background:** The Unscented Kalman Filter (UKF) provides a computationally efficient way to perform probabilistic forecast reconciliation for nonlinear constraints under a Gaussian assumption.

**Question / Future Work:** Future research is required to extend UKF-based or other conditioning-based reconciliation methods to handle non-Gaussian predictive distributions, such as those arising in intermittent, discrete, or mixed-type time series, where the standard Gaussian assumption of the UKF fails.

**Why It Matters:** Many real-world forecasting tasks involve non-Gaussian variables (e.g., counts, intermittency), making this a critical limitation for the adoption of the proposed reconciliation framework.

**Evidence:** our specific algorithm based on UKF is unsuitable to reconcile intermittent or discrete time series with nonlinear constraints due to its underlying Gaussian assumption.