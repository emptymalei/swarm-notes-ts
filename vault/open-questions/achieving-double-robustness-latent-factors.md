---
created_at: '2026-03-29T20:15:29Z'
source_papers:
- '[[openalex-2603.25010-bayesian-propensity-score-augmented-latent-factor-models-for]]'
title: Achieving Double Robustness
---

**Background:** The Bayesian procedure proposed to mitigate model feedback involves estimating latent factor loadings ($\Gamma$) solely from the outcome model, and then inserting the resulting structure into the treatment assignment model for parameter updates.

**Question / Future Work:** The proposed PS-LFM does not fully satisfy the classical double-robustness property because the latent factor loadings, estimated from the outcome model, are incorporated into the treatment assignment model. A major area for future research is to develop an estimation strategy that achieves double robustness (consistency if either the treatment assignment or outcome model is correct) while still explicitly modeling treatment assignment under latent ignorability, which is necessary for identification in the presence of unobserved confounding.

**Why It Matters:** Double robustness is a desirable property in causal inference as it increases robustness against model misspecification in either the treatment mechanism or the outcome process. Losing this property due to linking latent factor estimation across models is a significant methodological limitation.

**Evidence:** Second, because latent factor loadings are estimated from the outcome model and subsequently incorporated into the treatment assignment model, the proposed approach does not fully satisfy the classical double-robustness property: correct specification of either the treatment or outcome model alone is insufficient for consistent estimation. Nevertheless, this dependence reflects the latent ignorability assumption required for identification in the presence of unobserved confounding. Future research aimed at addressing these limitations is worth pursuing.