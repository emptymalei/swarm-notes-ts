---
# CSL-compatible fields
title: "Anticipating tipping in spatiotemporal systems with machine learning"
author:
  - literal: "Smita Deb"
  - literal: "Zheng-Meng Zhai"
  - literal: "Mulugeta Haile"
  - literal: "Ying-Cheng Lai"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.06454"

# Custom fields
paper_id: "2604.06454"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "dynamical-systems"
  - "dimensionality-reduction"
  - "spatiotemporal-forecasting"
architectures:
  []
datasets:
  - "cmip5"
concept_slugs:
  []
dataset_slugs:
  - "cmip5"
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:56:10Z"
created_at: "2026-04-09T04:56:10Z"
---

# Anticipating tipping in spatiotemporal systems with machine learning

**Authors**: Smita Deb, Zheng-Meng Zhai, Mulugeta Haile, Ying-Cheng Lai
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.06454](https://arxiv.org/abs/2604.06454)

## Summary

This paper addresses the challenge of anticipating critical transitions (tipping points) in complex spatiotemporal dynamical systems. By employing non-negative matrix factorization to achieve dimensionality reduction, the authors adapt reservoir computing models to forecast both the occurrence and precise timing of catastrophic shifts. The framework is validated against synthetic dynamical systems and real-world CMIP5 climate projections, demonstrating superior computational efficiency and robust performance under challenging conditions.

## Key Contributions

- Introduces a framework combining non-negative matrix factorization (NMF) with parameter-adaptable reservoir computing for predicting tipping points in complex spatiotemporal systems.
- Demonstrates high-accuracy identification of tipping event timing within narrow prediction windows across various nonlinear dynamical systems.
- Validates the approach on CMIP5 climate projection datasets, showing robustness against high dimensionality and reducing computational overhead compared to full-space modeling.

## Open Questions & Future Work

- [[unsupervised-spatiotemporal-tipping-prediction]]

## Archivist Review

I have approved the CMIP5 dataset as it is a standard, widely-cited benchmark for climate-related spatiotemporal forecasting mentioned as a primary validation target. I also approved one open question regarding unsupervised tipping prediction, as it addresses a fundamental barrier to scaling these models to real-world, black-box systems. Other candidates were rejected for being overly empirical or too localized to standard model tuning practices.

### Approved Open Questions
- Unsupervised Spatiotemporal Tipping Prediction: Expanding forecasting to cases where the driving parameter is unknown is essential for climate and ecological monitoring applications.

### Rejected Candidates
- [open_question] Optimal Training Data Length (`optimal-training-length-tipping-prediction`) - low_impact: Identifying 'optimal' training data size is a routine empirical task in machine learning and lacks a clear path toward a general theoretical resolution.

## Datasets

- [[cmip5]]

## Links

- [Abstract](https://arxiv.org/abs/2604.06454)
- [PDF](https://arxiv.org/pdf/2604.06454)

