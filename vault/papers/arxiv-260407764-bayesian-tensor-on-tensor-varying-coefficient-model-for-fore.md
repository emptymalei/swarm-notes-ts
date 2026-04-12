---
# CSL-compatible fields
title: "Bayesian Tensor-on-Tensor Varying Coefficient Model for Forecasting Alzheimer's Disease Progression"
author:
  - literal: "Yajie Liu"
  - literal: "Hengrui Luo"
  - literal: "Suprateek Kundu"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.07764"

# Custom fields
paper_id: "2604.07764"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "bayesian-inference"
  - "longitudinal-data"
  - "medical-imaging"
architectures:
  []
datasets:
  - "adni"
concept_slugs:
  - "bayesian-tensor-on-tensor-varying-coefficient-model"
dataset_slugs:
  - "adni"
skill: "TimeSeriesSkill"
processed_at: "2026-04-12T05:04:34Z"
created_at: "2026-04-12T05:04:34Z"
---

# Bayesian Tensor-on-Tensor Varying Coefficient Model for Forecasting Alzheimer's Disease Progression

**Authors**: Yajie Liu, Hengrui Luo, Suprateek Kundu
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.07764](https://arxiv.org/abs/2604.07764)

## Summary

This paper introduces a Bayesian tensor-on-tensor varying coefficient model designed to forecast Alzheimer's disease progression through longitudinal MRI data. The framework models nonlinear voxel-level relationships using Gaussian process priors while preserving spatial information through low-rank tensor-based coefficients. An efficient MCMC algorithm is developed to handle the high-dimensional computations required for image-level forecasting. Evaluation on the ADNI dataset demonstrates the model's effectiveness in accurately predicting future cortical thickness and biological brain aging.

## Key Contributions

- Introduces a Bayesian tensor-on-tensor framework that captures nonlinear relationships using Gaussian process priors and spatial structures via low-rank coefficients.
- Develops an efficient MCMC algorithm leveraging parallel structures for voxel-specific GP atoms and low-rank tensor coefficient updates.
- Demonstrates superior performance in forecasting cortical thickness and brain aging on T1-weighted MRIs from the ADNI dataset compared to existing methods.

## Open Questions & Future Work

- [[advancing-longitudinal-image-forecasting]]

## Key Concepts

- [[bayesian-tensor-on-tensor-varying-coefficient-model]]: A Bayesian modeling framework that relates input and output tensors by integrating Gaussian process priors with low-rank tensor-based coefficient structures to capture spatial dependencies.

## Archivist Review

Approved the core Bayesian tensor-on-tensor modeling framework and the primary ADNI dataset used for evaluation. The open question was approved for its focus on the architectural challenges of scaling longitudinal, multi-modal, nonlinear image regression.

### Approved Concepts
- Bayesian Tensor-on-Tensor Varying Coefficient Model: This is the central contribution of the paper, providing a novel framework for high-dimensional image forecasting that explicitly accounts for spatial heterogeneity and nonlinearity.

### Approved Open Questions
- Advancing Longitudinal Image Forecasting: Addressing these limitations is critical for developing prognostic models that can reliably forecast future neurobiological changes in neurodegenerative diseases like Alzheimer's, as current methods fail to capture the complex, nonlinear evolution of biomarkers over time.

## Datasets

- [[adni]]

## Links

- [Abstract](https://arxiv.org/abs/2604.07764)
- [PDF](https://arxiv.org/pdf/2604.07764)

