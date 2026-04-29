---
created_at: '2026-04-29T05:11:28Z'
source_papers:
- '[[arxiv-260425205-functional-autoregression-without-truncation-a-continuous-re]]'
title: Joint Regularization and Lag Selection
---

**Background:** Functional autoregressive models (FAR) typically rely on functional principal component analysis (FPCA) which requires a discrete, often ad hoc, truncation level. The sensitivity of forecast performance to this truncation level is a known limitation in the functional time series literature.

**Question / Future Work:** While Tikhonov regularization provides a continuous alternative to truncation for FAR(1) estimation, extending this to higher-order lag models (FAR(p)) or models with exogenous covariates (FARX) remains an open challenge. Specifically, it is unclear how to optimally perform joint selection of the lag order p and the regularization parameter alpha.

**Why It Matters:** Generalizing the regularization framework to FAR(p) and FARX is critical for broader applicability in functional time series where dependencies often exceed a single lag or include external influences.

**Evidence:** The extension to FAR(p) with p > 1 and to functional autoregressive models with exogenous covariates (FARX) ... raises questions about how to choose the lag order p jointly with the regularization parameter α.