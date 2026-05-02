---
created_at: '2026-05-02T05:09:05Z'
source_papers:
- '[[arxiv-260427182-preserving-temporal-dynamics-in-time-series-generation]]'
title: MCMC-diffusion model integration
---

**Background:** Autoregressive generative models often suffer from cumulative distribution shift and drift where sequence-level statistics deviate from empirical transition laws over time. Post-generation correction modules have been developed to mitigate this, yet it remains unclear how these techniques generalize to non-autoregressive paradigms.

**Question / Future Work:** Investigate the integration of MCMC-based correction mechanisms into diffusion-based generative models to determine if they can effectively mitigate distribution shift within non-autoregressive time-series generation.

**Why It Matters:** Diffusion models represent a state-of-the-art approach to generative modeling; understanding if post-hoc correction mechanisms apply to them is essential for future synthetic data reliability.