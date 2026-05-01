---
created_at: '2026-05-01T05:22:16Z'
source_papers:
- '[[arxiv-260427967-differentiable-latent-structure-discovery-for-interpretable]]'
title: Non-Gaussian likelihoods for clinical series
---

**Background:** Gaussian process models for time series data rely on likelihood functions to quantify uncertainty and relate latent variables to observations. While Gaussian likelihoods are standard for their analytical tractability, many real-world clinical datasets exhibit heterogeneity or discrete-valued characteristics that deviate from Gaussian assumptions.

**Question / Future Work:** Expanding the likelihood framework is critical for clinical utility, as clinical EHR data is inherently multimodal and rarely strictly Gaussian. Research into non-Gaussian likelihood formulations is needed to improve the model's ability to handle mixed data types such as discrete patient states, intubation status, or mortality indicators.

**Why It Matters:** Expanding the likelihood framework is critical for clinical utility, as clinical EHR data is inherently multimodal and rarely strictly Gaussian.

**Evidence:** ...we restricted our experiments to Gaussian likelihoods... more flexible likelihood formulations would be necessary to capture the heterogeneity of clinical time series and to jointly model discrete patient states, such as intubation status, missingness indicators, or mortality.