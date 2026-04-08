---
# CSL-compatible fields
title: "Scientific Validation of the SPARC4 Pipeline: Multi-band Imaging, Polarimetry, and Photometric Time Series for Improved Characterization of Transiting Exoplanets"
author:
  - literal: "Eder Martioli"
  - literal: "Claudia V. Rodrigues"
  - literal: "Julio C. N. Campagnolo"
  - literal: "Francisco J. Jablonski"
  - literal: "Ana Carolina Mattiuci"
  - literal: "Fernando Falkenberg"
  - literal: "Gustavo H. S. Santos"
  - literal: "Marina M. C. Mello"
  - literal: "Isabel J. Lima"
  - literal: "Filipe V. M. Monteiro"
  - literal: "Luciano Fraga"
  - literal: "Leandro de Almeida"
  - literal: "Diego Lorenzo-Oliveira"
  - literal: "Hélio D. Perottoni"
  - literal: "Laerte Andrade"
  - literal: "Wagner Schlindwein"
  - literal: "Denis Bernardes"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.05305"

# Custom fields
paper_id: "2604.05305"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:56:40Z"
created_at: "2026-04-08T04:56:40Z"
---

# Scientific Validation of the SPARC4 Pipeline: Multi-band Imaging, Polarimetry, and Photometric Time Series for Improved Characterization of Transiting Exoplanets

**Authors**: Eder Martioli, Claudia V. Rodrigues, Julio C. N. Campagnolo, Francisco J. Jablonski, Ana Carolina Mattiuci, Fernando Falkenberg, Gustavo H. S. Santos, Marina M. C. Mello, Isabel J. Lima, Filipe V. M. Monteiro, Luciano Fraga, Leandro de Almeida, Diego Lorenzo-Oliveira, Hélio D. Perottoni, Laerte Andrade, Wagner Schlindwein, Denis Bernardes
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.05305](https://arxiv.org/abs/2604.05305)

## Summary

This paper presents the SPARC4 Pipeline, a robust data reduction and analysis suite for multi-band imaging and polarimetry focused on characterizing transiting exoplanets. The pipeline enables high-cadence time series generation, achieving a photometric precision of 0.02% and polarimetric precision of ~0.02% at the 1.6 m Pico dos Dias Observatory telescope. By jointly modeling these high-precision ground-based observations with space-based mission data (TESS, K2) via a Bayesian MCMC framework, the authors improve the constraints on the orbital and physical parameters of seven hot Jupiter systems.

## Key Contributions

- Introduces the SPARC4 Pipeline for processing high-cadence multi-band imaging, polarimetry, and photometric time series.
- Demonstrates achieving an average photometric precision of 0.02% for 15-minute cadence observations and a polarimetric precision of ~0.02%.
- Refines physical and orbital parameters of seven hot Jupiter exoplanets by integrating SPARC4 observations with TESS/K2 space-based data using a Bayesian MCMC framework.

## Open Questions & Future Work

- [[exoplanetary-polarimetry-sensitivity-limits]]

## Archivist Review

The paper presents an instrumental validation suite for a specific telescope (SPARC4) and uses existing mission data (TESS/K2) to perform joint modeling. While the observational results are scientifically valuable, the pipeline itself is highly localized to the specific hardware. I have approved a single open question regarding the persistent sensitivity limits of exoplanetary polarimetry, as it captures a broader, unresolved physical and instrumental challenge in observational time-series science.

### Approved Open Questions
- Exoplanetary Polarimetry Sensitivity Limits: Advancing polarimetric precision is a critical bottleneck for characterization of exoplanetary atmospheres, representing a frontier in observational astronomy.

### Rejected Candidates
- [concept] SPARC4 Pipeline (`sparc4-pipeline`) - paper_local: The SPARC4 pipeline is an instrument-specific data reduction software suite, lacking the generalization or broad methodological contribution required for a vault entry.
- [dataset] TESS (`tess`) - not_reusable: TESS is a massive, widely-used space-based mission data archive rather than a specific research dataset for a vault entry.
- [dataset] K2 (`k2`) - not_reusable: K2 is a broad mission data archive rather than a specific research dataset for a vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.05305)
- [PDF](https://arxiv.org/pdf/2604.05305)

