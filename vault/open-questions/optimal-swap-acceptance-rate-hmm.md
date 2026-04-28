---
created_at: '2026-04-28T05:13:50Z'
source_papers:
- '[[arxiv-260424587-bayesian-inference-for-hidden-markov-models-under-genuine-mu]]'
title: Optimal PT swap acceptance rate
---

**Background:** The effectiveness of the parallel tempering (PT) algorithm depends on the selection of an inverse temperature schedule, typically tuned to achieve a specific swap acceptance rate between adjacent replicas. While a rate of 0.234 has been established as optimal for certain classes of MCMC problems, it has not been theoretically verified as the optimal rate for hidden Markov models (HMMs).

**Question / Future Work:** Determine the optimal swap acceptance rate for the parallel tempering algorithm specifically when applied to hidden Markov models, as the standard 0.234 rate—optimal under other regularity conditions—may not hold for this class of models.

**Why It Matters:** Efficient exploration of multimodal posterior distributions in complex models relies on optimizing the PT algorithm, and using suboptimal swap rates can significantly impact computational performance and the ability to explore state spaces.

**Evidence:** While the optimal inverse temperature schedule conveys constant swap acceptance rates, it has not been verified theoretically that 0.234 is the correspond to the value for the optimal solution in the case of hidden Markov models. Consequently, the optimal swap acceptance rate for hidden Markov models remains an open research question.