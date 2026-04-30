---
created_at: '2026-04-30T05:13:46Z'
source_papers:
- '[[arxiv-260426535-arma-approximation-of-a-non-separable-spatio-temporal-model]]'
title: SPDE Approximation Resolution Instability
---

**Background:** Spatio-temporal modeling via rational approximation of SPDEs is susceptible to numerical instability in parameter inference as the spatial resolution increases.

**Question / Future Work:** There is an unresolved sensitivity to spatial resolution where higher spatial resolutions lead to extreme values for the temporal range parameter and degraded predictive performance. Investigating the root cause—whether it stems from numerical precision in the rational approximation, model misspecification, or overfitting—is essential for methodology robustness.

**Why It Matters:** This is a critical bottleneck for scaling fractional SPDE-based inference to high-resolution climate or environmental datasets.

**Evidence:** When the resolution is ≥10^2 the parameter inference tends towards extreme values in the temporal range, with detrimental effect on predictions. The source of this effect is not clear and further study is needed in future work.