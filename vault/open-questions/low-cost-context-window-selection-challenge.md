---
created_at: '2026-03-29T20:16:11Z'
source_papers:
- '[[openalex-2603.25025-system-anchored-knee-estimation-for-low-cost-context-window]]'
title: Efficient context-window identification
---

**Background:** Autoregressive neural PDE simulators predict future states based on a finite sequence of past states, necessitating the selection of an optimal context window length from a candidate set.

**Question / Future Work:** Identifying the performance-critical context window length for a fixed-window autoregressive neural PDE simulator without incurring the high computational cost of an exhaustive search over all candidate lengths remains an open challenge, as the optimal window depends jointly on system dynamics, simulator architecture, and rollout objective.

**Why It Matters:** The efficiency of training and tuning neural PDE simulators is bottlenecked by the high cost associated with retraining for every potential context window length. Establishing a low-cost, reliable selection method is crucial for practical deployment.

**Evidence:** As a result, a basic question remains open: can we identify the performance-critical window for a given autoregressive neural simulator without paying the cost of exhaustive search? The problem is challenging because the best window depends jointly on the underlying system dynamics, the simulator architecture, and the downstream rollout objective.