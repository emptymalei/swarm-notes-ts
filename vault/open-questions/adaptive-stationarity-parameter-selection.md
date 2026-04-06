---
created_at: '2026-04-06T05:03:42Z'
source_papers:
- '[[arxiv-260402620-reducing-bias-and-optimising-execution-time-in-iterative-sol]]'
title: Adaptive Stationarity Parameter Selection
---

**Background:** Simulations of superconducting systems using the Time Dependent Ginzburg Landau (TDGL) equations require determining when a system has reached a stationary state to ensure numerical accuracy and computational efficiency. The choice of appropriate parameters for stationarity testing, such as significance levels and window sizes, is currently based on empirical calibration for specific systems.

**Question / Future Work:** The current algorithm for determining stationarity in TDGL simulations relies on specific hyperparameters, including the significance level for trend testing and the window sizes used for moving averages. A general, robust framework is needed that can automatically adapt these parameters across diverse physical scenarios, different superconductor types, or varying simulation conditions without requiring extensive manual recalibration.

**Why It Matters:** Automating or generalising the selection of stationarity test parameters is critical for making the algorithm robust and widely applicable, moving beyond empirical, case-specific tuning to a more universally reliable simulation methodology.

**Evidence:** As empirically observed, the algorithm is, in effect, little sensitive to variations in this value, but it should be high in order to be more conservative in finding the zero trend line... the value of L1 = 10^4 has been found to be enough... this value was obtained by calibration using many simulations, but it could be subjected to more calibrations still, should the need arise.