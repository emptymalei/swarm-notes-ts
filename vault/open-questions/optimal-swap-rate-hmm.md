---
created_at: '2026-04-29T05:13:24Z'
source_papers:
- '[[arxiv-260424587-bayesian-inference-for-hidden-markov-models-under-genuine-mu]]'
title: Optimal swap rate for HMMs
---

**Background:** The parallel tempering algorithm, a state-space augmentation method used to explore multimodal posterior distributions, relies on an inverse-temperature schedule, typically tuned to achieve a specific swap acceptance rate. The optimal swap acceptance rate for hidden Markov models (HMMs) has not been theoretically established.

**Question / Future Work:** Deriving the theoretically optimal swap acceptance rate specifically for HMMs is necessary, as existing guidelines for other models may not be optimal for the geometry of HMM posterior surfaces.

**Why It Matters:** Achieving the optimal swap acceptance rate is critical for maximizing the efficiency of parallel tempering and ensuring robust exploration, impacting computational cost and accuracy of inference.

**Evidence:** it has not been verified theoretically that 0.234 is the correspond to the value for the optimal solution in the case of hidden Markov models.