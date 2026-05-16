---
created_at: '2026-05-16T05:12:07Z'
source_papers:
- '[[arxiv-260514642-distributionally-robust-model-predictive-control-for-virtual]]'
title: Temporal Dependencies in DRO Ambiguity Sets
---

**Background:** Distributionally robust optimization (DRO) methods frequently rely on stage-wise construction of ambiguity sets to maintain computational tractability in multi-period control problems. This approach, however, often assumes independence between stages, potentially failing to capture the temporal dependencies inherent in stochastic processes such as market prices.

**Question / Future Work:** The current framework relies on stage-wise construction of Wasserstein ambiguity sets from marginal quantile forecasts, which does not explicitly capture temporal dependencies in the electricity price process. In a multi-step model predictive control setting, where decisions depend on the joint distribution of prices across the entire horizon, this independence can lead to overly conservative robustification. Developing methods to construct joint Wasserstein ambiguity sets over price trajectories that explicitly account for temporal dependencies is a fundamental challenge.

**Why It Matters:** This is a critical bottleneck in applying distributionally robust control to energy systems, as it directly impacts the trade-off between robustness (constraint satisfaction) and performance (economic efficiency). Addressing this is crucial for the deployment of truly uncertainty-aware control strategies in VPPs.