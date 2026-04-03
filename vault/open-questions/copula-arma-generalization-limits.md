---
created_at: '2026-04-03T05:20:31Z'
source_papers:
- '[[arxiv-2604.01500-copula-based-time-series-for-non-gaussian-and-non-markovian]]'
title: Limits of copula-based ARMA generalization
---

**Background:** The model framework for copula-based time series allows for the construction of processes with infinite memory by combining autoregressive and moving aggregate copula components.

**Question / Future Work:** While the framework can recover certain Gaussian ARMA and GARCH-like processes as special cases, it is not established whether there exists a general copula-based construction that can recover an arbitrary Gaussian ARMA(p, q) process for all orders p and q without the emergence of additional, unintended terms that distort the model order. Defining such a universal construction would unify the theory of copula-based time series with classical linear time series models.

**Why It Matters:** Resolving this would determine the limits of the copula-based approach in replicating the flexibility of classical linear models and would clarify if the current model structures are truly sufficient or if more advanced constructions are required.

**Evidence:** This finding brings up the question whether there is a process composed of MA-type and AR-type parts that yields a Gaussian ARMA(p, q) as a special case for all (p, q) in N^2.