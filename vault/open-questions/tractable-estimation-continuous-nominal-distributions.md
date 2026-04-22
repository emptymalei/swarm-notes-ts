---
created_at: '2026-04-22T05:05:47Z'
source_papers:
- '[[arxiv-260418546-wasserstein-distributionally-robust-risk-sensitive-estimatio]]'
title: Tractability for Continuous Nominal Distributions
---

**Background:** The Wasserstein-based distributionally robust estimation framework relies on the assumption that the nominal distribution is finitely supported to derive tractable semidefinite programming reformulations for complex risk-sensitive criteria like Conditional Value-at-Risk (CVaR).

**Question / Future Work:** It remains an open question how to efficiently compute these estimators when the nominal distribution is continuous or lacks a finite support representation, as the current semidefinite programming formulation depends on explicitly summing over N scenarios. Future work is needed to explore approximation schemes or alternative characterizations that can handle general continuous nominal distributions without inducing prohibitive computational costs.

**Why It Matters:** This is a significant bottleneck for applying the method to real-world datasets where continuous distributions are standard and discretizing them into large, finite samples significantly increases the dimensions of the semidefinite program, often rendering it computationally intractable.