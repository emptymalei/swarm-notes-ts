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
  []
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
processed_at: "2026-05-02T05:07:35Z"
created_at: "2026-05-02T05:07:35Z"
---

# Differentiable latent structure discovery for interpretable forecasting in clinical time series

**Authors**: Ivan Lerner, Jean Feydy, Alexandre Kalimouttou, Anita Burgun, Francis Bach
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27967](https://arxiv.org/abs/2604.27967)

## Summary

StructGP is a continuous-time multi-task Gaussian process model designed for forecasting irregular clinical time series while maintaining interpretability and uncertainty estimation. By learning sparse, ordered DAGs of dependencies, the model effectively captures variable interactions without resorting to standard grid-based imputation. The extended LP-StructGP variant further incorporates latent pathways to model shared cross-patient progression patterns, providing a scalable and highly calibrated solution validated on the MIMIC-IV and PhysioNet Challenge datasets.

## Key Contributions

- Introduces StructGP, a continuous-time multi-task Gaussian process that combines process convolutions with differentiable DAG structure learning.
- Proposes LP-StructGP, which uses latent pathways and subject-specific coupling filters to model complex cross-patient progression patterns.
- Demonstrates significant performance gains and superior uncertainty calibration over unstructured baseline kernels on the MIMIC-IV septic shock cohort.

## Open Questions & Future Work

- [[scalability-of-gp-models-in-clinical-settings]]
- [[non-gaussian-likelihoods-clinical-time-series]]

## Key Concepts

- [[structgp]]: A continuous-time multi-task Gaussian process that learns inter-variable DAG dependencies through differentiable structure learning.

## Archivist Review

The paper introduces a novel approach to combining structure learning with Gaussian process convolutions. I approved the core framework (StructGP) and two open questions regarding the scalability and likelihood flexibility of these models. The variant 'LP-StructGP' was rejected as it is a specific extension of the overarching StructGP framework. MIMIC-IV and PhysioNet Challenge were approved as they are standard, central datasets in the clinical time-series forecasting literature.

### Approved Concepts
- StructGP: Provides a novel framework for combining differentiable DAG structure learning with Gaussian process convolutions to maintain uncertainty estimation in time-series forecasting.

### Approved Open Questions
- Scalability of GP Clinical Models: Scalability is a primary bottleneck for adopting principled, uncertainty-aware GP models in large-scale settings, which often forces a trade-off between statistical rigor and computational feasibility.
- Non-Gaussian Clinical Likelihoods: Clinical data is rarely purely Gaussian; bridging this gap is essential for building models that can handle the complex, real-world constraints of intensive care unit data.

### Rejected Candidates
- [concept] LP-StructGP (`lp-structgp`) - subcomponent_of_broader_mechanism: This is a sub-module or specific variant of the broader StructGP framework, which is already being approved as the primary contribution.

## Datasets

- [[mimic-iv]]
- [[physionet-challenge]]

## Links

- [Abstract](https://arxiv.org/abs/2604.27967)
- [PDF](https://arxiv.org/pdf/2604.27967)

