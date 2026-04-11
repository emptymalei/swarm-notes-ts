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
  - "medical-imaging"
  - "longitudinal-forecasting"
  - "bayesian-inference"
  - "spatial-modeling"
  - "neuroscience"
architectures:
  []
datasets:
  - "adni"
concept_slugs:
  - "bayesian-tensor-on-tensor-varying-coefficient-model"
dataset_slugs:
  - "adni"
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:45:44Z"
created_at: "2026-04-11T04:45:44Z"
---

# Bayesian Tensor-on-Tensor Varying Coefficient Model for Forecasting Alzheimer's Disease Progression

**Authors**: Yajie Liu, Hengrui Luo, Suprateek Kundu
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.07764](https://arxiv.org/abs/2604.07764)

## Summary

This paper introduces a Bayesian tensor-on-tensor varying coefficient model designed to forecast longitudinal neuroimaging data, such as cortical thickness. The framework leverages Gaussian process priors to capture nonlinear relationships while utilizing low-rank tensor structures to account for spatial dependencies. An efficient parallel MCMC algorithm is developed to handle the computational demands of high-dimensional imaging data. Experimental results on the ADNI dataset demonstrate the model's effectiveness in predicting future biological changes and its potential for early clinical detection of Alzheimer's disease.

## Key Contributions

- Introduces a Bayesian tensor-on-tensor model that captures nonlinearity and spatial heterogeneity in longitudinal medical image data.
- Develops an MCMC algorithm with parallel structure for scalable estimation of voxel-specific GP atoms and low-rank tensor coefficients.
- Demonstrates superior performance in forecasting cortical thickness and brain aging using the ADNI longitudinal dataset.

## Open Questions & Future Work

- [[non-linear-tot-modeling-limitations]]

## Key Concepts

- [[bayesian-tensor-on-tensor-varying-coefficient-model]]: A Bayesian modeling framework that forecasts longitudinal voxel-level data by combining Gaussian process priors for nonlinearity with low-rank tensor decompositions for spatial structure.

## Archivist Review

The paper introduces a structured Bayesian approach for high-dimensional longitudinal forecasting. I approved the proposed model framework as a reusable concept for spatial-temporal modeling and the ADNI dataset as it is a standard, critical benchmark for neuroimaging forecasting. I also approved the open question regarding non-linear TOT modeling, as it identifies a clear, persistent theoretical limitation in current tensor regression literature.

### Approved Concepts
- Bayesian Tensor-on-Tensor Varying Coefficient Model: This framework introduces a principled way to integrate Gaussian processes into tensor-on-tensor structures for spatial-temporal forecasting in high-dimensional domains like neuroimaging.

### Approved Open Questions
- Non-linear TOT Modeling Limitations: This is a critical limitation for applying tensor models to real-world, complex longitudinal datasets where physical or biological change is non-linear.

## Datasets

- [[adni]]

## Links

- [Abstract](https://arxiv.org/abs/2604.07764)
- [PDF](https://arxiv.org/pdf/2604.07764)

