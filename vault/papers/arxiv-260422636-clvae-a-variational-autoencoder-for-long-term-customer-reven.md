---
# CSL-compatible fields
title: "CLVAE: A Variational Autoencoder for Long-Term Customer Revenue Forecasting"
author:
  - literal: "Jeffrey Näf"
  - literal: "Riana Valera Mbelson"
  - literal: "Markus Meierer"
issued:
  date-parts:
    - [2026, 4, 24]
url: "https://arxiv.org/abs/2604.22636"

# Custom fields
paper_id: "2604.22636"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "econometrically-informed-vae"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-27T05:10:46Z"
created_at: "2026-04-27T05:10:46Z"
---

# CLVAE: A Variational Autoencoder for Long-Term Customer Revenue Forecasting

**Authors**: Jeffrey Näf, Riana Valera Mbelson, Markus Meierer
**Date**: 2026-04-24
**Paper ID**: [arxiv:2604.22636](https://arxiv.org/abs/2604.22636)

## Summary

CLVAE is a variational autoencoder designed for long-term customer revenue forecasting in non-contractual business settings, bridging the gap between rigid structural probabilistic models and flexible machine learning approaches. The framework preserves the likelihood structure of traditional attrition-transaction-spend models while utilizing encoder-decoder networks to learn latent representations of customer heterogeneity. This hybrid design allows for robust, reliable forecasts even with sparse data, while seamlessly incorporating nonlinear effects and rich covariates when available. The method consistently outperforms current benchmarks in long-horizon predictive accuracy.

## Key Contributions

- Proposes CLVAE, a VAE-based architecture that integrates process-based probabilistic customer models with flexible latent representations.
- Enables a unified approach to modeling customer attrition, transaction frequency, and spending without requiring restrictive parametric assumptions for customer heterogeneity.
- Demonstrates superior performance over traditional customer base models and machine learning benchmarks across multiple real-world datasets for long-term revenue forecasting.

## Open Questions & Future Work

- [[integrating-time-varying-covariates-in-vae-customer-models]]

## Key Concepts

- [[econometrically-informed-vae]]: A hybrid modeling architecture that embeds structural, domain-specific likelihood functions into the variational autoencoder framework to combine model interpretability with flexible representation learning.

## Archivist Review

The review approved the core methodological contribution—the integration of structural domain likelihoods into VAEs—which provides a scalable design pattern for future research. The open question regarding time-varying covariates was retained as it addresses the fundamental tension between model flexibility and structural reliability in latent-variable forecasting models. Other candidates were rejected for being too model-specific or routine.

### Approved Concepts
- Econometrically-Informed VAE: This approach represents a significant paradigm for combining structural domain models (where causality and interpretability are core) with deep latent variable modeling, which is highly reusable across scientific and business forecasting domains.

### Approved Open Questions
- Integrating Time-Varying Covariates: This addresses a fundamental tension between capturing complex, external temporal dynamics and maintaining the reliable, structure-aware forecasting performance essential for high-stakes business decision-making.

### Rejected Candidates
- [concept] CLVAE (`clvae`) - paper_local: This is a specific model architecture instance rather than a broader reusable methodological framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.22636)
- [PDF](https://arxiv.org/pdf/2604.22636)

