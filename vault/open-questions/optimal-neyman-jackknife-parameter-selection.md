---
created_at: '2026-04-28T05:15:38Z'
source_papers:
- '[[arxiv-260424017-neyman-jackknife-design-based-variance-estimation-for-causal]]'
title: Optimal Neyman Jackknife parameters
---

**Background:** The Neyman Jackknife provides a flexible framework for conservative variance estimation in design-based causal inference, particularly under interference where traditional variance estimators may be anti-conservative. As the approach relies on user-specified index-sampling rules and computable proxies, its practical performance depends heavily on the chosen trade-off between the complexity of the update set and the accuracy of the proxy.

**Question / Future Work:** It is currently unclear how to optimally choose the index-sampling rule and computable proxy to minimize variance estimation error while maintaining conservative properties in diverse interference settings. Furthermore, while the current method assumes a fixed update set size for theoretical tractability, providing a formal approach to data-driven selection of these hyperparameters that guarantees asymptotic conservativeness remains an open challenge.

**Why It Matters:** This is crucial because the framework's effectiveness in real-world applications is highly sensitive to the chosen parameters, and the lack of a formal, guaranteed procedure for data-driven parameter selection limits the practical automation of the method.

**Evidence:** The main objective of our framework is choosing S so that the oracle bound is not too large, while still having enough data to construct f−S that well-approximates the oracle conditional expectation. ... Technically, conservativeness is not guaranteed if one selects L after comparing many candidates.