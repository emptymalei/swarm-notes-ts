---
# CSL-compatible fields
title: "Differentiable latent structure discovery for interpretable forecasting in clinical time series"
author:
  - literal: "Ivan Lerner"
  - literal: "Jean Feydy"
  - literal: "Alexandre Kalimouttou"
  - literal: "Anita Burgun"
  - literal: "Francis Bach"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27967"

# Custom fields
paper_id: "2604.27967"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "clinical-data"
  - "gaussian-processes"
  - "interpretability"
  - "uncertainty-estimation"
  - "structure-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "structgp"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T05:14:20Z"
created_at: "2026-05-03T05:14:20Z"
---

# Differentiable latent structure discovery for interpretable forecasting in clinical time series

**Authors**: Ivan Lerner, Jean Feydy, Alexandre Kalimouttou, Anita Burgun, Francis Bach
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27967](https://arxiv.org/abs/2604.27967)

## Summary

StructGP and its extension LP-StructGP provide a framework for interpretable, uncertainty-aware forecasting of irregular clinical time series by learning sparse DAG structures of variable dependencies. By integrating continuous-time Gaussian processes with differentiable structure learning and subject-specific coupling filters, these models effectively capture complex inter-variable and cross-patient dynamics. Empirical validation on MIMIC-IV and the PhysioNet Challenge demonstrates significant improvements in predictive accuracy and calibration over standard baselines.

## Key Contributions

- Introduces StructGP, which uses process convolutions and differentiable DAG learning to recover inter-variable clinical dependencies.
- Develops LP-StructGP to capture cross-patient disease progression patterns through subject-specific latent pathway filtering.
- Achieves superior forecasting RMSE and uncertainty calibration on MIMIC-IV septic shock patients compared to unstructured kernel baselines.

## Open Questions & Future Work

- [[non-gaussian-likelihoods-clinical-time-series]]
- [[scalability-of-latent-pathway-models]]

## Key Concepts

- [[structgp]]: A continuous-time multi-task Gaussian process that uses differentiable structure learning to discover sparse DAGs of inter-variable dependencies in clinical data.

## Archivist Review

I approved the StructGP framework as a novel synthesis of process convolutions and differentiable DAG learning for clinical time series. The two open questions address fundamental limitations in GP modeling (likelihood constraints and computational scalability) that are common across high-dimensional clinical applications. LP-StructGP was rejected as a concept because it is essentially a specific architectural extension of the primary StructGP mechanism.

### Approved Concepts
- StructGP: It is the central methodological contribution of the paper, enabling interpretable structure learning within a continuous-time Gaussian process framework.

### Approved Open Questions
- Non-Gaussian Clinical GP Likelihoods: Clinical data is inherently multi-modal and non-Gaussian; overcoming the limitation to Gaussian likelihoods is essential for the practical deployment of these models in real-world healthcare settings.
- Latent Pathway Model Scalability: As clinical datasets grow in both the number of patients and the number of physiological variables monitored, the computational bottleneck in latent pathway models limits their applicability to high-dimensional clinical monitoring.

### Rejected Candidates
- [concept] LP-StructGP (`lp-structgp`) - subcomponent_of_broader_mechanism: LP-StructGP is presented as a subcomponent or direct extension of the StructGP framework rather than a distinct, widely applicable methodology.

## Links

- [Abstract](https://arxiv.org/abs/2604.27967)
- [PDF](https://arxiv.org/pdf/2604.27967)

