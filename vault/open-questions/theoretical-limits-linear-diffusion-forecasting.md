---
created_at: '2026-04-30T05:14:08Z'
source_papers:
- '[[arxiv-260426365-beyond-fixed-formulas-data-driven-linear-predictor-for-effic]]'
title: Theoretical limits of linear diffusion forecasting
---

**Background:** Diffusion transformers achieve high-quality visual synthesis but are computationally intensive, typically necessitating numerous iterative denoising steps. Feature caching methods aim to accelerate this process by reusing or predicting hidden representations without model retraining.

**Question / Future Work:** While current linear predictor frameworks effectively approximate feature evolution, there is a lack of rigorous theoretical characterization of the limits of linear representability for diverse diffusion architectures. Research is needed to determine whether the performance gain of linear caching is fundamentally limited by the underlying non-linearity of the SDEs governing the diffusion process or if it generalizes across wider domains like high-resolution video.

**Why It Matters:** Understanding these limits is crucial for determining if performance scaling in diffusion acceleration will eventually require more complex, non-linear predictive mechanisms.