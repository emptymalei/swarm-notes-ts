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
  - "time-series"
  - "healthcare"
  - "interpretability"
  - "uncertainty-estimation"
architectures:
  []
datasets:
  - "mimic-iv"
  - "physionet-challenge"
concept_slugs:
  - "structgp"
dataset_slugs:
  - "mimic-iv"
  - "physionet-challenge"
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:22:16Z"
created_at: "2026-05-01T05:22:16Z"
---

# Differentiable latent structure discovery for interpretable forecasting in clinical time series

**Authors**: Ivan Lerner, Jean Feydy, Alexandre Kalimouttou, Anita Burgun, Francis Bach
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27967](https://arxiv.org/abs/2604.27967)

## Summary

StructGP is a continuous-time multi-task Gaussian process model designed for forecasting irregular clinical time series while maintaining interpretability and uncertainty calibration. By coupling process convolutions with differentiable DAG structure learning, the model recovers interpretable inter-variable dependencies. The LP-StructGP variant further enhances predictive performance by incorporating latent pathways to model cross-patient progression patterns. Experiments on MIMIC-IV and PhysioNet datasets demonstrate that these models improve forecasting accuracy and calibration compared to unstructured and graph-based baselines.

## Key Contributions

- Introduced StructGP, a continuous-time multi-task Gaussian process that enables interpretable, sparse DAG structure learning on irregular EHR data.
- Proposed LP-StructGP, which uses latent pathways and subject-specific coupling filters to capture complex cross-patient progression patterns.
- StructGP achieves a 6h forecasting RMSE of 0.68 on the MIMIC-IV septic shock cohort, significantly outperforming independent-task and unstructured baselines.

## Open Questions & Future Work

- [[non-gaussian-clinical-likelihoods]]

## Key Concepts

- [[structgp]]: A continuous-time multi-task Gaussian process framework for discovering sparse, ordered DAGs of inter-variable dependencies in irregular time series.

## Archivist Review

I approved the core StructGP framework and the specific open problem of non-Gaussian likelihoods for clinical time-series, as these provide the most value for future longitudinal forecasting research. I rejected LP-StructGP as a standalone concept because it is a subcomponent extension of the primary StructGP model, and I rejected the latent pathway scalability question as it is primarily a localized performance concern rather than a fundamental scientific bottleneck. The datasets MIMIC-IV and PhysioNet Challenge are accepted as they are industry-standard benchmarks in the healthcare forecasting domain.

### Approved Concepts
- StructGP: It introduces a novel framework for learning interpretable, sparse DAG dependencies within a continuous-time Gaussian process for irregular time series.

### Approved Open Questions
- Non-Gaussian likelihoods for clinical series: Expanding the likelihood framework is critical for clinical utility, as clinical EHR data is inherently multimodal and rarely strictly Gaussian.

## Datasets

- [[mimic-iv]]
- [[physionet-challenge]]

## Links

- [Abstract](https://arxiv.org/abs/2604.27967)
- [PDF](https://arxiv.org/pdf/2604.27967)

