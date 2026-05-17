---
created_at: '2026-05-17T05:23:47Z'
source_papers:
- '[[arxiv-260514642-distributionally-robust-model-predictive-control-for-virtual]]'
title: Joint Ambiguity Sets for Temporal Dependencies
---

**Background:** In distributionally robust model predictive control (DR-MPC), ambiguity sets are often constructed stage-wise using marginal distributions to maintain computational tractability. This approach ignores potential temporal dependencies within the stochastic processes over the control horizon.

**Question / Future Work:** Developing methods to incorporate joint Wasserstein ambiguity sets over price trajectories that explicitly account for temporal dependencies is a necessary next step to reduce the conservatism inherent in independent stage-wise formulations for systems with energy storage.

**Why It Matters:** Addressing temporal correlation is critical for improving the accuracy and reducing the conservatism of DR-MPC in systems with energy storage, as current independent stage-wise formulations fail to leverage the full structure of the underlying uncertainty.

**Evidence:** Constructing joint Wasserstein ambiguity sets over price trajectories, for instance via scenario-based representations of temporal dependencies represents an important direction for future work.