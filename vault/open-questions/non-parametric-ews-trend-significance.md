---
created_at: '2026-04-19T05:05:17Z'
source_papers:
- '[[arxiv-260415230-on-the-robustness-of-mann-kendall-tests-used-to-forecast-cri]]'
title: Robust trend significance for EWS
---

**Background:** The Mann-Kendall test is frequently employed to detect early warning signals (EWS) for critical transitions, assuming a Gaussian distribution for the test statistic despite the inherent autocorrelation in EWS indicators. Recent evidence indicates that this assumption is often invalid, leading to inflated type I error rates in critical transition forecasting.

**Question / Future Work:** There is a need to develop or validate robust, non-parametric statistical frameworks for assessing the significance of trends in EWS that account for induced autocorrelation and avoid reliance on inaccurate Gaussianity assumptions. Future work should focus on alternative statistical tests, such as those grounded in null model resampling or trend-independent methods for forecasting critical transitions.

**Why It Matters:** Reliable detection of critical transitions is essential for early warning in ecological, climate, and medical domains. Current methodological reliance on Mann-Kendall tests leads to systematic false positives ('cry wolf' effects), undermining the utility of these forecasting frameworks.

**Evidence:** Our robustness analysis challenges the use of non-parametric tests for trend detection in the context of EWS of critical transitions. ... we see two main alternative approaches to assess the significance that the system is undergoing a critical transition: use Mann-Kendall’s tau on EWS indicator time series but with alternative tests that make no assumption on its distribution, or use methods to forecast critical transitions that do not use Mann-Kendall’s tau to quantify trends.