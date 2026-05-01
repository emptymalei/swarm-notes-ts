---
created_at: '2026-05-01T05:23:29Z'
source_papers:
- '[[arxiv-260427443-abc-any-subset-autoregression-via-non-markovian-diffusion-br]]'
title: Scalability of Continuous-Time Generative Models
---

**Background:** Continuous-time generative models often face computational bottlenecks when handling long sequences and struggle with temporal coherence across irregular sampling intervals.

**Question / Future Work:** Investigating efficient sampling schemes (e.g., hybrid ODE-SDE, coarse-to-fine generation) and history compression architectures (e.g., SSMs) is essential to scale continuous-time generative models for high-fidelity, long-range stochastic processes.

**Why It Matters:** Addresses critical scalability and sampling efficiency bottlenecks inherent in current diffusion-based continuous-time generative frameworks.

**Evidence:** Future work should investigate alternative sampling schemes, such as hybrid ODE-SDE sampling schemes. Another example is coarse-to-fine generation... there are efficient architectures (e.g., SSMs) that selectively compress the history.