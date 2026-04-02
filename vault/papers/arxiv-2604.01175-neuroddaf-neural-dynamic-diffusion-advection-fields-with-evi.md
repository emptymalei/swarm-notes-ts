---
# CSL-compatible fields
title: "NeuroDDAF: Neural Dynamic Diffusion-Advection Fields with Evidential Fusion for Air Quality Forecasting"
author:
  - literal: "Prasanjit Dey"
  - literal: "Soumyabrata Dev"
  - literal: "Angela Meyer"
  - literal: "Bianca Schoen-Phelan"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.01175"

# Custom fields
paper_id: "2604.01175"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "neuroddaf"
  - "evidential-fusion-mechanism"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-02T05:37:11Z"
created_at: "2026-04-02T05:37:11Z"
---

# NeuroDDAF: Neural Dynamic Diffusion-Advection Fields with Evidential Fusion for Air Quality Forecasting

**Authors**: Prasanjit Dey, Soumyabrata Dev, Angela Meyer, Bianca Schoen-Phelan
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.01175](https://arxiv.org/abs/2604.01175)

## Summary

NeuroDDAF is a hybrid forecasting framework that integrates neural representation learning with physics-based diffusion-advection modeling to address spatiotemporal air quality challenges. The architecture leverages a GRU-Graph Attention encoder for temporal and spatial dynamics, a Fourier-domain transport module, and a wind-modulated latent Neural ODE. An evidential fusion mechanism is employed to adaptively combine neural and physical forecasts, simultaneously delivering high predictive accuracy and well-calibrated uncertainty estimates across diverse urban environments.

## Key Contributions

- Proposed NeuroDDAF, a hybrid physics-informed model combining GRU-GAT encoders, Fourier-domain transport modules, and latent Neural ODEs.
- Introduced an evidential fusion mechanism to blend data-driven and physics-based forecasts with calibrated uncertainty quantification.
- Achieved state-of-the-art performance on four urban air quality datasets, with up to 9.7% reduction in RMSE compared to baselines like AirPhyNet.

## Limitations

Computational overhead of the latent Neural ODE compared to purely feedforward neural architectures; sensitivity to the quality of external wind field data.

## Open Questions & Future Work

- [[incorporating-chemical-transformations-air-quality]]
- [[real-time-heterogeneous-data-integration]]

## Key Concepts

- [[neuroddaf]]: A physics-informed forecasting framework that unifies neural representation learning with open-system transport modeling.
- [[evidential-fusion-mechanism]]: A mechanism that adaptively combines physics-guided and neural forecasts while quantifying uncertainty.

## Archivist Review

The paper introduces a hybrid architecture (NeuroDDAF) and a specific uncertainty-quantifying fusion mechanism (Evidential Fusion) that are valuable for the physics-informed ML community. I have approved these as high-level architectural patterns. The open questions regarding chemical transformation and heterogeneous data integration address significant, broader research bottlenecks in atmospheric modeling beyond this specific implementation. All urban air quality datasets listed were rejected as they are domain-specific regional datasets that do not constitute a generalizable, reusable benchmark.

### Approved Concepts
- Neural Dynamic Diffusion-Advection Fields: It is the core architectural innovation of the paper, combining neural ODEs with physics-based transport modeling.
- Evidential Fusion Mechanism: It provides a novel way to combine physics-informed and data-driven outputs with uncertainty quantification.

### Approved Open Questions
- Modeling Chemical Transformations: Incorporating chemical kinetics is critical for bridging the gap between simplified physical transport models and the complex, reactive nature of real-world atmospheric pollution.
- Real-time Heterogeneous Data Integration: Robust, real-time integration of heterogeneous data is essential for the practical deployment of air quality forecasting systems in dynamic, decision-critical urban environments.

## Links

- [Abstract](https://arxiv.org/abs/2604.01175)
- [PDF](https://arxiv.org/pdf/2604.01175)

