---
created_at: '2026-04-20T05:10:49Z'
source_papers:
- '[[arxiv-260415620-pg-nodetb-physics-guided-neural-ordinary-differential-equati]]'
title: Parameter Identifiability Under Partial Observability
---

**Background:** Epidemiological modeling often suffers from structural misspecification when real-world dynamics, such as treatment programs or behavioral changes, deviate from simplified mathematical assumptions. Combining mechanistic compartmental models with neural networks enables data-driven corrections, yet the effectiveness of these models relies on their ability to handle partial observability and noisy surveillance streams.

**Question / Future Work:** A key unresolved challenge is determining the parameter identifiability of physics-guided neural ordinary differential equations when only a subset of compartments, such as active infectious individuals, is observable from real-world surveillance data. This requires the development of robust training frameworks that can utilize informative Bayesian priors to constrain neural components and ensure physically plausible behavior under high uncertainty.

**Why It Matters:** Ensuring parameter identifiability is fundamental for the reliability of machine learning models in public health, preventing the neural components from overfitting noise or producing biologically nonsensical results when applied to real-world, sparse data.

**Evidence:** Additional open challenges include parameter identifiability under partial observability (I(t) only), which may require informative Bayesian priors; and model extensions to incorporate spatial heterogeneity, MDR-TB strain dynamics, and TB/HIV co-infection, all of which are critical in high-burden settings.