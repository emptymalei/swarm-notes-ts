---
created_at: '2026-03-29T20:15:29Z'
source_papers:
- '[[openalex-2603.25010-bayesian-propensity-score-augmented-latent-factor-models-for]]'
title: Parametric sensitivity of PS-LFM
---

**Background:** Identifying treatment effects in time-series cross-sectional data requires controlling for unobserved, time-invariant unit-specific confounders, often modeled using latent factors or interactive fixed effects.

**Question / Future Work:** The proposed Bayesian propensity score–augmented latent factor model (PS-LFM) relies on parametric assumptions for both the treatment assignment and outcome models. Specifically, the functional form through which the propensity score enters the outcome model is prespecified (e.g., subclassification thresholds or inclusion as a continuous covariate), and mis-specification of this functional form, such as selecting incorrect thresholds for propensity score stratification, may lead to biased treatment effect estimates. A future direction involves developing methods that are less reliant on these specific parametric specifications, potentially through non-parametric or more flexible functional forms for the propensity score augmentation.

**Why It Matters:** The reliance on parametric specifications for how propensity scores interact with latent factors limits the model's robustness to true data-generating processes where this relationship is complex or unknown.

**Evidence:** First, although the propensity score–augmented specification allows for heterogeneous effects across propensity score strata, it still relies on parametric assumptions for both the treatment assignment and outcome models. In particular, because the effect of the propensity score in the outcome model is assumed to follow a prespecified functional form, mis-specification, such as incorrect thresholds used for propensity score stratification, may lead to biased treatment effect estimates.