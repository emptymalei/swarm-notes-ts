---
# CSL-compatible fields
title: "Reduced-Order Data Assimilation for Thermospheric Density Using Physics-informed SINDyc Models"
author:
  - literal: "Sriram Narayanan"
  - literal: "Daniele Sicoli"
  - literal: "Piyush Mehta"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24646"

# Custom fields
paper_id: "2604.24646"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "physics-informed-machine-learning"
  - "time-series-forecasting"
  - "data-assimilation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sindyc-ar"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-29T05:13:08Z"
created_at: "2026-04-29T05:13:08Z"
---

# Reduced-Order Data Assimilation for Thermospheric Density Using Physics-informed SINDyc Models

**Authors**: Sriram Narayanan, Daniele Sicoli, Piyush Mehta
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24646](https://arxiv.org/abs/2604.24646)

## Summary

This paper introduces a reduced-order modeling framework for thermospheric density estimation by coupling an autoregressive Sparse Identification of Nonlinear Dynamics with control (SINDy$_c$-AR) model with a Kalman filter. Derived from the TIE-GCM, the model captures complex, non-linear atmospheric responses to solar and geomagnetic forcing while maintaining computational efficiency. By assimilating density data from various satellite missions, the approach improves estimation accuracy over open-loop forecasts, especially during geomagnetic disturbances. The study highlights the trade-offs between physics-informed reduced-order models and empirical benchmarks in out-of-training conditions.

## Key Contributions

- Proposed SINDy$_c$-AR for efficient thermospheric mass density modeling, enabling data assimilation at a fraction of the cost of TIE-GCM.
- Demonstrated that assimilating in-situ density observations with SINDy$_c$-AR significantly reduces estimation error compared to open-loop predictions, particularly during geomagnetic storms.
- Compared the proposed physics-informed approach against linear DMDc benchmarks and empirical models (NRLMSIS 2.1, HASDM) across multiple satellite platforms.

## Open Questions & Future Work

- [[adaptive-covariance-tuning-thermospheric-rom]]
- [[ensemble-based-assimilation-latentspace]]

## Key Concepts

- [[sindyc-ar]]: An autoregressive sparse identification model with control used for efficient reduced-order modeling of high-dimensional physical systems.

## Archivist Review

I approved the core method SINDyc-AR as a reusable reduced-order modeling technique and two open questions regarding adaptive covariance tuning and non-linear assimilation methods, which are significant bottlenecks in data-driven physical modeling. Standard satellite datasets were rejected as they are domain-specific evaluation sources rather than novel research benchmarks.

### Approved Concepts
- SINDyc-AR: It is the core model proposed for capturing thermospheric variability at reduced computational cost.

### Approved Open Questions
- Adaptive covariance tuning for ROMs: Manual tuning is suboptimal and labor-intensive; automated adaptive tuning is critical for real-time operational reliability and robustness during extreme events.
- Ensemble-based latent space assimilation: Moving beyond the EKF linear-first-order approximation is essential to better capture non-Gaussian and nonlinear uncertainties inherent in upper atmospheric dynamics.

### Rejected Candidates
- [dataset] CHAMP (`CHAMP`) - not_novel: Standard satellite dataset used for model validation rather than a core research contribution.
- [dataset] GRACE (`GRACE`) - not_novel: Standard satellite dataset used for model validation rather than a core research contribution.
- [dataset] GRACE-FO (`GRACE-FO`) - not_novel: Standard satellite dataset used for model validation rather than a core research contribution.
- [dataset] GOCE (`GOCE`) - not_novel: Standard satellite dataset used for model validation rather than a core research contribution.
- [dataset] Swarm (`Swarm`) - not_novel: Standard satellite dataset used for model validation rather than a core research contribution.

## Links

- [Abstract](https://arxiv.org/abs/2604.24646)
- [PDF](https://arxiv.org/pdf/2604.24646)

