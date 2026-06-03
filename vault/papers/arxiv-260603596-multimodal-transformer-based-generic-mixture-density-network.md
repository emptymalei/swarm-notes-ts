---
# CSL-compatible fields
title: "Multimodal Transformer Based Generic Mixture Density Network for Scattering Timescale Estimation of Fast Radio Bursts"
author:
  - literal: "Bikash Kharel"
  - literal: "Emmanuel Fonseca"
  - literal: "Srinjoy Das"
  - literal: "Mason Ng"
  - literal: "Paul Scholz"
  - literal: "Mawson W. Simmons"
  - literal: "Lordrick Kahinga"
  - literal: "Afrokk Khan"
issued:
  date-parts:
    - [2026, 6, 2]
url: "https://arxiv.org/abs/2606.03596"

# Custom fields
paper_id: "2606.03596"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "multimodal-learning"
  - "uncertainty-estimation"
  - "transformer-based-modeling"
architectures:
  []
datasets:
  - "chime-frb-cat2"
concept_slugs:
  - "mt-gmdn"
dataset_slugs:
  - "chime-frb-cat2"
skill: "TimeSeriesSkill"
processed_at: "2026-06-03T05:45:40Z"
created_at: "2026-06-03T05:45:40Z"
---

# Multimodal Transformer Based Generic Mixture Density Network for Scattering Timescale Estimation of Fast Radio Bursts

**Authors**: Bikash Kharel, Emmanuel Fonseca, Srinjoy Das, Mason Ng, Paul Scholz, Mawson W. Simmons, Lordrick Kahinga, Afrokk Khan
**Date**: 2026-06-02
**Paper ID**: [arxiv:2606.03596](https://arxiv.org/abs/2606.03596)

## Summary

The authors present MT-GMDN, a deep learning framework designed to accelerate the estimation of scattering timescales (τ) for fast radio bursts. By processing dynamic spectra and timeseries profiles through parallel transformer encoders, the model effectively fuses multimodal information. The architecture uses a generic mixture-density output layer to address zero-inflated populations, enabling both accurate parameter prediction and heteroskedastic uncertainty quantification. Trained on the CHIME/FRB Cat2 dataset, the model significantly outperforms traditional iterative fitting methods in speed and robustness.

## Key Contributions

- Introduced MT-GMDN, a multimodal transformer model that integrates dynamic spectra and timeseries profiles to estimate FRB scattering timescales.
- Achieved 94% R^2 on scattering timescale estimation and 90% recall for measurable scattering events.
- Employed a generic mixture-density formulation that effectively handles zero-inflated populations and provides heteroskedastic uncertainty quantification.

## Key Concepts

- [[mt-gmdn]]: A deep learning architecture that fuses dynamic spectra and timeseries data using parallel transformer encoders and a generic mixture-density output layer to estimate scattering timescales.

## Archivist Review

I approved the MT-GMDN concept because it represents a specialized yet reusable pattern for scientific parameter estimation in multimodal, zero-inflated settings. I rejected the dataset because it is a domain-specific catalog rather than a broadly applicable benchmark dataset. No open questions were proposed, so none were approved.

### Approved Concepts
- Multimodal Transformer Based Generic Mixture Density Network: It provides a specialized architecture for integrating time-series and spectral data with a density-based output layer designed to handle zero-inflated phenomena, which is a common challenge in astrophysical parameter estimation.

### Rejected Candidates
- [dataset] CHIME/FRB Cat2 (`chime-frb-cat2`) - low_impact: The dataset is a specific catalog for a sub-domain and is not broadly reusable across different time-series or machine learning fields.

## Datasets

- [[chime-frb-cat2]]

## Links

- [Abstract](https://arxiv.org/abs/2606.03596)
- [PDF](https://arxiv.org/pdf/2606.03596)

