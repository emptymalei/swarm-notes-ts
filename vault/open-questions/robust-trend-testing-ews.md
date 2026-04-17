---
created_at: '2026-04-17T05:04:47Z'
source_papers:
- '[[arxiv-260415230-on-the-robustness-of-mann-kendall-tests-used-to-forecast-cri]]'
title: Robust trend testing for EWS
---

**Background:** The standard method for forecasting critical transitions involves estimating indicators like variance and autocorrelation over overlapping rolling windows and testing for trends using the Mann-Kendall statistic. Recent findings indicate that these tests rely on Gaussian assumptions that do not hold for the autocorrelated time series produced by this rolling window methodology.

**Question / Future Work:** There is a need to develop alternative, robust trend-testing frameworks for early warning signals (EWS) that do not rely on the invalid assumption that the Mann-Kendall statistic is Gaussian when applied to highly autocorrelated, finite-length time series. Research is required to validate alternative statistical methods that account for this autocorrelation, as well as investigate techniques like Gaussian-weighted rolling windows to mitigate induced temporal dependency.

**Why It Matters:** The paper demonstrates that current standard practices for identifying early warning signals lead to highly inflated Type I error rates, rendering existing automated critical transition detection unreliable. Establishing valid statistical protocols is essential for the reliable monitoring of complex systems.

**Evidence:** We detect mismatches leading to inflated type I error rates, which would routinely lead to announcing a critical transition while it is not occurring. In contrast to a recent recommendation, we conclude that the use of Mann-Kendall tests for trend detection in the context of forecasting critical transitions should be avoided.