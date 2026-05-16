---
created_at: '2026-05-16T05:12:14Z'
source_papers:
- '[[arxiv-260514632-drl-staf-a-deep-reinforcement-learning-framework-for-state-a]]'
title: Scalability of High-Dimensional HMMs
---

**Background:** High-dimensional multivariate Hidden Markov Models (HMMs) are prone to a combinatorial explosion of the joint state space, which complicates exact inference and limits scalability.

**Question / Future Work:** Scalability of RL-based state estimation in high-dimensional multivariate systems remains a critical bottleneck, particularly regarding training efficiency in resource-constrained environments.

**Why It Matters:** This is a persistent challenge for deep HMM hybrids that scale linearly or super-linearly with state-space cardinality.

**Evidence:** While relatively long training times can be acceptable in many practical applications, its absolute training cost remains high when N becomes large, which may limit its practicality in time-sensitive or resource-constrained large-scale settings.