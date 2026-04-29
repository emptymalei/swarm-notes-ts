---
created_at: '2026-04-29T05:13:08Z'
source_papers:
- '[[arxiv-260424646-reduced-order-data-assimilation-for-thermospheric-density-us]]'
title: Adaptive covariance tuning for ROMs
---

**Background:** Physics-based general circulation models (GCMs) are computationally expensive, necessitating reduced-order models (ROMs) to facilitate real-time thermospheric density estimation. Current ROMs rely on static training data and manual parameter tuning, which can limit their generalizability and accuracy under extreme, out-of-training space weather conditions.

**Question / Future Work:** The current framework relies on an iterative manual tuning procedure for covariance matrices, such as process noise and initial state uncertainty. Future efforts are required to develop principled, online adaptive tuning methods, such as innovation-based expectation-maximization, to dynamically adjust these covariances, especially during the onset of geomagnetic storms where stochastic model error characteristics change rapidly.

**Why It Matters:** Manual tuning is suboptimal and labor-intensive; automated adaptive tuning is critical for real-time operational reliability and robustness during extreme events.

**Evidence:** The process noise Q was set via the iterative manual tuning procedure... empirical validation that the tuned Q is consistent with observed innovation statistics is left to future work. ... principled online tuning via expectation-maximization or similar methods is deferred to future work.