---
created_at: '2026-04-09T04:53:23Z'
source_papers:
- '[[arxiv-260407169-amortized-filtering-and-smoothing-with-conditional-normalizi]]'
title: Smoothing Error Accumulation Scaling
---

**Background:** The performance of smoothing algorithms in high-dimensional state-space models can degrade as state dimensionality increases, often due to error accumulation in backward recursion.

**Question / Future Work:** Further investigation is needed into why smoothing performance deteriorates in high-dimensional systems, specifically whether this is fundamentally due to approximation errors accumulating during backward propagation or if it can be mitigated by more training data or different flow architectures.

**Why It Matters:** Understanding and overcoming error accumulation in backward recursion is essential for extending amortized filtering and smoothing frameworks to very high-dimensional spatio-temporal systems.

**Evidence:** This deterioration is mainly due to the iterative structure of the smoothing procedure in Algorithm 3. In particular, sampling from p_smoothing_theta1_theta2_psi(u_k | y_1:T_train) requires repeated backward propagation through the learned backward flow p_theta2_psi(u_k-1 | u_k, s_k), so approximation errors may accumulate along the reverse trajectory and eventually reduce the smoothing accuracy in higher-dimensional settings.