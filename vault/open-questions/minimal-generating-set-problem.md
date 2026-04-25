---
created_at: '2026-04-25T04:54:45Z'
source_papers:
- '[[arxiv-260421292-large-values-in-time-series-and-additive-combinatorics]]'
title: Minimal Generating Set Construction
---

**Background:** Additive combinatorics suggests that extreme values in certain signals can be reconstructed from a small set of base values (generators), but algorithms for identifying the optimal set remain heuristic.

**Question / Future Work:** The problem of finding the minimal set of generators required to span the set of extreme values is a computationally hard optimization problem (set cover), limiting the ability to empirically verify the theoretical lower bounds proposed by the additive structure framework.

**Why It Matters:** This represents the core computational bottleneck in validating the tightness of the additive structure theory in practical scenarios.

**Evidence:** Algorithm 1 produces some Λ that spans Γ, but not necessarily the minimal such set. The true minimal |Λ| may be smaller than reported. Finding the minimal Λ is a set cover problem that is computationally hard in general.