---
created_at: '2026-05-16T05:11:22Z'
source_papers:
- '[[arxiv-260514976-multi-regime-markov-switching-models-with-time-varying-trans]]'
title: Identifiability of GAS score coefficients
---

**Background:** Markov-switching models with generalized autoregressive score (GAS) drivers exhibit potential identifiability challenges in the parameter space of the score coefficient and regime-specific variance.

**Question / Future Work:** The joint likelihood surface of GAS-based time-varying transition probability (TVTP) models often presents a ridge, causing the score coefficient to collapse to zero or become statistically non-identifiable. Investigation is required to characterize the nature of this ridge, develop more robust estimation techniques, or identify alternative parameterizations that decouple the score process from the regime volatility.

**Why It Matters:** This issue limits the practical application of score-driven TVTP models, as standard maximum likelihood estimation fails to reliably recover the intended dynamic parameters.

**Evidence:** the GAS score coefficient appears to be statistically non-identifiable, due to a ridge in the joint likelihood surface (σ2, A)