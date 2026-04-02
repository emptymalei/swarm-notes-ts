---
created_at: '2026-04-02T05:38:42Z'
source_papers:
- '[[arxiv-2604.00390-causal-inference-for-unobservable-multivariate-outcomes-with]]'
title: Uncertainty in derived outcomes
---

**Background:** Causal inference with derived outcomes often involves model-based estimation, which introduces potential bias and uncertainty that propagates to the causal effect estimation.

**Question / Future Work:** There is a need to develop estimation procedures that explicitly quantify the additional variability and potential bias introduced by the multi-stage process of deriving outcomes from time-series data and performing downstream causal inference. Standard variance estimators may not fully capture the dependencies and errors stemming from the initial model construction and subsequent sample-splitting or selection procedures.

**Why It Matters:** Accurate variance estimation is crucial for valid hypothesis testing and the construction of reliable confidence intervals in causal inference, particularly when outcomes are not directly observed. Failure to account for multistage uncertainty can lead to invalid statistical inference and incorrect conclusions about causal effects.

**Evidence:** Second, the proposed variance estimator does not explicitly account for the additional variability introduced by the sample-splitting procedure, although we acknowledge discrepancies between $\\widehat{\\bm{\\tau}}^{*}$ and $\\widehat{\\bm{\\tau}}$, as well as between their corresponding variance estimators.