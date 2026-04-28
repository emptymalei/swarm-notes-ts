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
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "sindyc-ar"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-28T05:13:30Z"
created_at: "2026-04-28T05:13:30Z"
---

# Reduced-Order Data Assimilation for Thermospheric Density Using Physics-informed SINDyc Models

**Authors**: Sriram Narayanan, Daniele Sicoli, Piyush Mehta
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24646](https://arxiv.org/abs/2604.24646)

## Summary

This paper proposes SINDyc-AR, an autoregressive, physics-informed reduced-order modeling framework for thermospheric mass density estimation. By extracting dominant modes from the TIE-GCM, the approach enables computationally efficient modeling of nonlinear atmospheric responses to space weather drivers. The framework is coupled with a Kalman filter to assimilate multi-satellite density observations, significantly reducing estimation error compared to open-loop forecasts during extreme geomagnetic conditions.

## Key Contributions

- Introduces SINDyc-AR, a reduced-order model derived from TIE-GCM, enabling efficient atmospheric density estimation while maintaining nonlinear response to solar and geomagnetic forcing.
- Integrates the SINDyc-AR model with a Kalman filter for real-time assimilation of in situ density observations from multiple satellite constellations.
- Demonstrates improved density estimation performance over open-loop predictions, particularly during geomagnetic storms and scenarios with sparse satellite coverage.

## Open Questions & Future Work

- [[adaptive-covariance-tuning-thermospheric-assimilation]]
- [[ensemble-filter-extensions-thermospheric-assimilation]]

## Key Concepts

- [[sindyc-ar]]: An autoregressive extension of the Sparse Identification of Nonlinear Dynamics with control (SINDyc) framework for efficient, physics-informed reduced-order modeling.

## Archivist Review

The paper's core contribution is the SINDyc-AR framework, which is a reusable architectural pattern for physics-informed reduced-order modeling of dynamical systems. The approved open questions represent significant, well-defined bottlenecks in data assimilation for non-stationary, complex physical systems that extend beyond the immediate scope of thermospheric density estimation. Satellite constellations were rejected as routine observational datasets rather than being central, monolithic benchmarks deserving of individual permanent notes.

### Approved Concepts
- SINDyc-AR: It provides a novel approach to reduced-order modeling for high-dimensional physical systems by integrating autoregressive structures with SINDy control.

### Approved Open Questions
- Adaptive Covariance Tuning: Manual tuning is a bottleneck for operational scalability and accuracy; automated adaptive tuning would allow the filter to better respond to the non-stationary stochastic uncertainty inherent in geomagnetically disturbed conditions.
- Ensemble Filter Extensions: Replacing linearization-based filters with ensemble-based or sampling-based alternatives can improve performance in highly nonlinear dynamical regimes typical of severe space weather events.

## Links

- [Abstract](https://arxiv.org/abs/2604.24646)
- [PDF](https://arxiv.org/pdf/2604.24646)

