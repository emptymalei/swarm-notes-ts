---
created_at: '2026-05-03T05:13:44Z'
source_papers:
- '[[arxiv-260428163-sequential-inference-for-gaussian-processes-a-signal-process]]'
title: Flexible kernels for sequential GPs
---

**Background:** Gaussian process inference, particularly in high-dimensional or strongly nonstationary settings, often suffers from computational or representational limitations when using standard stationary kernels and fixed basis expansions.

**Question / Future Work:** Developing flexible kernel parameterizations that adapt to nonstationary systems while maintaining Bayesian structure and efficient sequential inference properties remains a primary research gap. Such methods would ideally integrate data-driven feature maps into the kernel framework without sacrificing the probabilistic interpretability inherent to Gaussian processes.

**Why It Matters:** Improving the expressiveness of sequential GP models is critical for deploying probabilistic models in complex, nonstationary signal processing environments where standard stationary kernels fail.

**Evidence:** Current sequential GP algorithms still depend on stationary kernels or a limited number of basis functions, which restricts their expressiveness in high-dimensional and strongly nonstationary systems.