---
created_at: '2026-05-03T05:15:22Z'
source_papers:
- '[[arxiv-260427443-abc-any-subset-autoregression-via-non-markovian-diffusion-br]]'
title: Efficient Conditioning for Any-Subset Autoregression
---

**Background:** Conditioning SDE-based generative models on arbitrary subsets of history and future states requires path-dependent score estimation, which currently lacks efficient scaling strategies.

**Question / Future Work:** Explore alternative architectures and sampling schemes, such as hybrid ODE-SDE solvers or selective state space models, to optimize the compression of long-range, irregularly-sampled temporal information for path-dependent diffusion bridges.

**Why It Matters:** Bridging the computational gap between path-dependent conditioning and efficient inference is crucial for scaling continuous-time generative models to complex, high-resolution time-series data.

**Evidence:** Future work should investigate alternative sampling schemes, such as hybrid ODE-SDE sampling schemes... there are efficient architectures (e.g., SSMs) that selectively compress the history.