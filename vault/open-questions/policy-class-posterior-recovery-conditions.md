---
created_at: '2026-04-15T05:05:06Z'
source_papers:
- '[[arxiv-260412158-reinforcement-learning-optimal-control-and-bayesian-filterin]]'
title: Posterior Recovery by Policies
---

**Background:** The KL-regularized control framework aims to solve optimal control problems by rewriting them as inference problems, often using rewards to mimic the likelihood term in Bayesian data assimilation. It remains unclear under what minimal conditions a policy class, restricted by fixed transition kernels and finite representability, can exactly recover the Bayesian posterior law rather than a different Gibbs law or a restricted projection.

**Question / Future Work:** Further theoretical development is required to define the specific conditions under which these control-based objectives can be guaranteed to produce the Bayesian posterior law, as opposed to a different Gibbs law or a restricted-family projection. This is particularly important for reinforcement learning-based data assimilation where practitioners often assume these objectives are equivalent to posterior inference.

**Why It Matters:** This is a fundamental bottleneck for bridging reinforcement learning with Bayesian data assimilation. It determines whether RL-learned policies are scientifically valid as Bayesian estimators or merely effective heuristics, which has significant implications for high-stakes domains like numerical weather prediction.

**Evidence:** Second, exact posterior recovery by a policy class is a reachability statement on state-action laws and is therefore not automatic under fixed transition kernels. ... Outside that calibrated setting one obtains either a different Gibbs law or a restricted-family projection.