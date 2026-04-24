---
created_at: '2026-04-24T05:10:18Z'
source_papers:
- '[[arxiv-260420485-co-state-based-data-fusion-and-risk-aware-filtering-for-spac]]'
title: Robustness to Higher-Order Nonlinearity
---

**Background:** The proposed co-state framework relies on a small-noise operating regime where the Taylor remainder of the measurement function is assumed to be negligible. This assumption limits the framework's applicability to scenarios with significant nonlinearity or large state-measurement increments.

**Question / Future Work:** A more rigorous extension is needed to handle cases where the second-order Taylor remainder of the measurement function is non-negligible, such as in highly nonlinear sensor environments or scenarios involving rapid state transitions. Generalizing the co-state projection to account for these higher-order geometric effects remains an open challenge to ensure accuracy and stability under broader operational conditions.

**Why It Matters:** Extending the validity of the geometric projection beyond the small-noise approximation is crucial for ensuring the robustness and reliability of the co-state based consistency monitoring in highly nonlinear or extreme-dynamics environments.

**Evidence:** To preserve computational tractability and enable instantaneous projection, we adopt the small-noise operating regime in which $r_{t} \\approx 0$ and treat the innovation incrementally... This approximation defines the regime in which Algorithm 1 operates.