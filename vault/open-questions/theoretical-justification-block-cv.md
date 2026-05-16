---
created_at: '2026-05-16T05:12:51Z'
source_papers:
- '[[arxiv-260514491-adaptive-long-run-variance-thresholding-for-sparse-covarianc]]'
title: Theoretical justification of block-CV
---

**Background:** The estimation of sparse covariance matrices in high-dimensional time series often relies on block cross-validation to select tuning parameters, as random sample splitting can violate the temporal structure of the data. However, the theoretical properties of these data-driven tuning procedures for dependent data remain largely unexplored.

**Question / Future Work:** There is a lack of theoretical justification for the block cross-validation procedures commonly used for selecting regularization parameters in sparse covariance matrix estimation for high-dimensional time series. It is unclear under what conditions these procedures achieve optimal convergence rates or support recovery consistency.

**Why It Matters:** Tuning parameter selection is crucial for the practical performance of thresholding estimators. Understanding the theoretical validity of these selection methods is necessary to ensure the reliability of the resulting covariance estimates in applied settings.