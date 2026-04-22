---
created_at: '2026-04-22T05:03:45Z'
source_papers:
- '[[arxiv-260419442-state-forecasting-in-an-estimation-framework-with-surrogate]]'
title: Bias in iterative surrogate training
---

**Background:** In filtering frameworks where data-driven surrogate models are used for measurement forecasting, recurrent updates to the surrogate model are necessary to maintain accuracy as the system evolves. Iterative retraining of these surrogates introduces the potential for 'double dipping', where information from the same measurement batch is used multiple times in the estimation process, leading to biased estimates.

**Question / Future Work:** There is a need to develop formal methods for handling potential biases, such as 'double dipping', that arise when retraining surrogate models within an iterative filtering framework as new measurements become available. Addressing this requires a rigorous investigation into how to incorporate new data to maintain predictive accuracy without compromising the statistical integrity of the estimation process.

**Why It Matters:** This is a fundamental challenge in combining machine learning-based surrogate modeling with traditional state estimation (filtering), as it directly affects the validity and consistency of the resulting state estimates.

**Evidence:** Future work will focus on ... addressing potential biases like ”double dipping” when retraining surrogate models.