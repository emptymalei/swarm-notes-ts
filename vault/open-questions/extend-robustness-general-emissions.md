---
created_at: '2026-04-17T05:06:47Z'
source_papers:
- '[[arxiv-260414322-doubly-outlier-robust-online-infinite-hidden-markov-model]]'
title: Generalizing robustness to non-LG models
---

**Background:** Generalised Bayesian inference utilizes robust updates, such as the weighted observation likelihood filter (WoLF), to ensure bounded posterior influence in linear-Gaussian state-space models. However, these methods are restricted to specific emission models and lack a general framework for arbitrary distribution types.

**Question / Future Work:** Extend the analysis of bounded posterior influence functions (PIF) and the corresponding conditions for robustness to general emission models beyond the current linear-Gaussian restriction.

**Why It Matters:** Broadening the robustness guarantees to a wider class of emission models is necessary to make the doubly-robust framework applicable to non-Gaussian or non-linear time series problems.

**Evidence:** the theoretical guarantees rely on LG emissions to obtain closed-form PIF expressions, the analysis to more general emission models remains open.