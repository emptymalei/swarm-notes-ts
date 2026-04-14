---
# CSL-compatible fields
title: "Physics-Informed State Space Models for Reliable Solar Irradiance Forecasting in Off-Grid Systems"
author:
  - literal: "Mohammed Ezzaldin Babiker Abdullah"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11807"

# Custom fields
paper_id: "2604.11807"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "physics-informed-machine-learning"
  - "solar-irradiance-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "thermodynamic-liquid-manifold-network"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:01:50Z"
created_at: "2026-04-14T05:01:50Z"
---

# Physics-Informed State Space Models for Reliable Solar Irradiance Forecasting in Off-Grid Systems

**Authors**: Mohammed Ezzaldin Babiker Abdullah
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11807](https://arxiv.org/abs/2604.11807)

## Summary

This paper introduces the Thermodynamic Liquid Manifold Network to address common failures in solar irradiance forecasting, such as phase lags during cloud transients and physically impossible nocturnal generation. By projecting inputs into a Koopman-linearized Riemannian manifold and incorporating thermodynamic gates, the model strictly enforces celestial geometry constraints. The resulting architecture is highly efficient, with approximately 63k parameters, and proves effective for stable, real-time deployment in off-grid photovoltaic microgrid controllers.

## Key Contributions

- Introduced the Thermodynamic Liquid Manifold Network, a model that integrates celestial mechanics and atmospheric thermodynamics into a Koopman-linearized manifold.
- Achieved zero-magnitude nocturnal forecasting error while maintaining sub-30-minute phase response during high-frequency weather transients.
- Demonstrated robust performance in semi-arid climate conditions with an RMSE of 18.31 Wh/m2 and a Pearson correlation of 0.988 over a five-year horizon.

## Limitations

Evaluation is limited to a single five-year dataset in a semi-arid climate; broader generalization to diverse climate types remains to be demonstrated.

## Key Concepts

- [[thermodynamic-liquid-manifold-network]]: A neural network architecture that projects meteorological and geometric variables into a Koopman-linearized Riemannian manifold to enforce atmospheric thermodynamic consistency.

## Archivist Review

The Thermodynamic Liquid Manifold Network is approved as it provides a distinct, theoretically grounded approach to enforcing physical constraints within a neural manifold, which is a reusable pattern for time-series forecasting in scientific domains. Other components (such as the spectral calibration unit or alpha-gate) were rejected as subcomponents of this overarching mechanism. No open questions or datasets met the rigorous threshold for independent long-term tracking.

### Approved Concepts
- Thermodynamic Liquid Manifold Network: This is the central methodological innovation, combining Koopman linearization with Riemannian manifolds to enforce physics constraints in a deep learning framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.11807)
- [PDF](https://arxiv.org/pdf/2604.11807)

