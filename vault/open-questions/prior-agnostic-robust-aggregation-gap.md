---
created_at: '2026-04-29T05:13:38Z'
source_papers:
- '[[arxiv-260424517-prior-agnostic-robust-forecast-aggregation]]'
title: Optimality Gap in Prior-Agnostic Aggregation
---

**Background:** Robust forecast aggregation aims to combine expert probability forecasts into a single reliable estimate without direct observation of the latent states or the underlying information-generating processes. Existing research primarily focuses on settings with a known, fixed binary state space, which fails to account for more general environments where the latent driver of outcome likelihoods is unknown.

**Question / Future Work:** The study establishes a clear performance gap when the state space is unknown versus known. An explicit, closed-form, prior-agnostic aggregator is proposed, but the gap between its regret upper bound and the theoretical minimax lower bound remains unresolved, suggesting that more optimal aggregation strategies or stronger lower bounds may exist for prior-agnostic environments.

**Why It Matters:** This gap is central to the minimax optimality of prior-agnostic aggregation rules. Closing it would provide a definitive answer to the limits of robust aggregation in the presence of latent, unknown-state-space uncertainty.

**Evidence:** our aggregation function achieves worst-case regret 0.0255 (Theorem 3.2), and we complement this upper bound by showing that the optimal scheme cannot do much better. In particular, we show a lower bound that no aggregation scheme can achieve regret below 31/1326 ≈ 0.0234 (Theorem 3.4).