---
# CSL-compatible fields
title: "Forecasting with Bayesian Panel Vector Autoregressions Using the R Package bpvars"
author:
  - literal: "Miguel Sanchez-Martinez"
  - literal: "Tomasz Woźniak"
issued:
  date-parts:
    - [2026, 6, 12]
url: "https://arxiv.org/abs/2606.14143"

# Custom fields
paper_id: "2606.14143"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "econometrics"
  - "bayesian-inference"
architectures:
  []
datasets:
  []
concept_slugs:
  - "bayesian-hierarchical-panel-var"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-15T06:02:15Z"
created_at: "2026-06-15T06:02:15Z"
---

# Forecasting with Bayesian Panel Vector Autoregressions Using the R Package bpvars

**Authors**: Miguel Sanchez-Martinez, Tomasz Woźniak
**Date**: 2026-06-12
**Paper ID**: [arxiv:2606.14143](https://arxiv.org/abs/2606.14143)

## Summary

The paper introduces the bpvars R package, which facilitates Bayesian hierarchical panel Vector Autoregression (VAR) modeling for dynamic panel data. The framework features country-specific models with hierarchical priors centered on global counterparts, allowing for effective parameter shrinkage and information sharing. Additionally, the package includes a model-coherent Bayesian approach for handling missing data and supports efficient recursive out-of-sample forecasting, achieving high performance through C++ backend integration.

## Key Contributions

- Introduces the bpvars R package for flexible Bayesian hierarchical panel VAR modeling and forecasting.
- Implements a model-coherent Bayesian approach for robust treatment of missing observations in panel data.
- Provides automated pseudo-out-of-sample recursive forecasting routines with high computational performance enabled by C++ optimization.

## Key Concepts

- [[bayesian-hierarchical-panel-var]]: A hierarchical modeling framework that uses global-counterpart-centered priors for country-specific panel VAR models to improve estimation and forecasting.

## Archivist Review

The approval focused on the central modeling framework of the paper, while software and standard statistical implementation details were rejected as they do not meet the criteria for permanent knowledge vault entries. The chosen concept of Bayesian hierarchical panel VAR is a robust, reusable methodology for time series modeling under unit heterogeneity.

### Approved Concepts
- Bayesian Hierarchical Panel Vector Autoregressions: This framework enables effective parameter shrinkage and information sharing across heterogeneous units in panel time series.

### Rejected Candidates
- [concept] bpvars R Package (`bpvars-r-package`) - not_reusable: Software implementations are generally considered tools rather than conceptual contributions in this vault.
- [concept] Model-coherent Bayesian missing data treatment (`model-coherent-missing-data-treatment`) - not_novel: This is a standard methodological detail in Bayesian inference rather than a novel conceptual contribution.

## Links

- [Abstract](https://arxiv.org/abs/2606.14143)
- [PDF](https://arxiv.org/pdf/2606.14143)

