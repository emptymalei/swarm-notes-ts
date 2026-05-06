---
created_at: '2026-05-06T05:11:11Z'
source_papers:
- '[[arxiv-260503997-uncertainty-quantification-in-forecast-comparisons]]'
title: Multivariate Block Length Selection
---

**Background:** The moving block bootstrap is a common tool for quantifying uncertainty in time series forecast evaluations by resampling blocks of data to account for temporal dependence. The effectiveness of this method depends heavily on the choice of block length, which ideally balances the representation of autocorrelation with the number of effective independent samples.

**Question / Future Work:** There is currently no universally accepted, principled method for automatically selecting the optimal block length for the moving block bootstrap in a multivariate forecast evaluation setting. Developing an automatic, data-driven selection procedure for this context remains an open, unresolved problem.

**Why It Matters:** Inappropriate block length selection can lead to inaccurate variance estimation, causing incorrect coverage of confidence bands and invalid statistical inference in forecast comparisons.

**Evidence:** Data-driven block length selection for the moving block bootstrap remains an open problem in the multivariate setting.