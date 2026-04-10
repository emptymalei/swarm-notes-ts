---
# CSL-compatible fields
title: "Bayesian Tensor-on-Tensor Varying Coefficient Model for Forecasting Alzheimer's Disease Progression"
author:
  - literal: "Yajie Liu"
  - literal: "Hengrui Luo, Suprateek Kundu"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.07764"

# Custom fields
paper_id: "2604.07764"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "adni"
concept_slugs:
  []
dataset_slugs:
  - "adni"
skill: "TimeSeriesSkill"
processed_at: "2026-04-10T15:28:52Z"
created_at: "2026-04-10T15:28:52Z"
---

# Bayesian Tensor-on-Tensor Varying Coefficient Model for Forecasting Alzheimer's Disease Progression

**Authors**: Yajie Liu, Hengrui Luo, Suprateek Kundu
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.07764](https://arxiv.org/abs/2604.07764)

## Summary

This paper introduces a Bayesian tensor-on-tensor varying coefficient model designed to forecast Alzheimer's disease progression through longitudinal MRI analysis. The framework integrates Gaussian process priors for nonlinearity with low-rank tensor coefficients to capture complex spatial structure and heterogeneity at the voxel level. An efficient parallel MCMC algorithm is developed to enable scalable inference, with experimental results on the ADNI dataset confirming the model's accuracy in predicting cortical thickness and neurobiological brain aging.

## Key Contributions

- Proposes a novel Bayesian tensor-on-tensor varying coefficient model for capturing nonlinear voxel-level relationships via GP priors and low-rank tensor coefficients.
- Develops an efficient parallelized MCMC algorithm to handle high-dimensional image data, enabling scalability for voxel-specific spatial modeling.
- Demonstrates superior performance in forecasting cortical thickness and brain aging using longitudinal MRI data from the ADNI dataset compared to baseline methods.

## Open Questions & Future Work

- [[nonlinear-dependency-modeling-in-tot]]

## Archivist Review

I have approved the ADNI dataset as it is a standard, highly identifiable benchmark in longitudinal neuroimaging. The open question on nonlinear modeling in tensor-on-tensor regression was approved for its importance in high-dimensional medical imaging. I rejected the model and MCMC algorithms as they are specific technical implementations rather than general-purpose modeling primitives.

### Approved Open Questions
- Nonlinear dependency modeling in TOT: This question addresses the critical bottleneck of scaling flexible, non-linear Bayesian modeling to high-dimensional tensors, which is central to advancing longitudinal image analysis.

### Rejected Candidates
- [concept] Bayesian Tensor-on-Tensor Varying Coefficient Model (`bayesian-tensor-on-tensor-varying-coefficient-model`) - paper_local: This is a specific model architecture instance rather than a foundational or widely reusable conceptual primitive.
- [concept] Parallelized MCMC for voxel-specific GP atoms (`parallelized-mcmc-for-voxel-specific-gp-atoms`) - subcomponent_of_broader_mechanism: This is an implementation-specific optimization technique rather than a reusable conceptual framework.

## Datasets

- [[adni]]

## Links

- [Abstract](https://arxiv.org/abs/2604.07764)
- [PDF](https://arxiv.org/pdf/2604.07764)

