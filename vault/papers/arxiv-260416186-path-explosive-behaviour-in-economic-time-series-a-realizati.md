---
# CSL-compatible fields
title: "Path-Explosive Behaviour in Economic Time Series: A Realization-Centred Exploratory Framework"
author:
  - literal: "José Francisco Perles-Ribes"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.16186"

# Custom fields
paper_id: "2604.16186"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "path-explosive-behaviour"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:08:49Z"
created_at: "2026-04-20T05:08:49Z"
---

# Path-Explosive Behaviour in Economic Time Series: A Realization-Centred Exploratory Framework

**Authors**: José Francisco Perles-Ribes
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.16186](https://arxiv.org/abs/2604.16186)

## Summary

This paper introduces a realization-centred framework for detecting path-explosive behaviour in economic time series, departing from traditional DGP-based recursive unit root testing. By applying four diagnostic layers—level geometry, growth rate dynamics, normalised curvature, and log-space behaviour—the framework isolates self-reinforcing growth episodes without requiring asymptotic distributional assumptions. It further enables the detection of co-explosive dependencies between series using non-parametric concordance measures. The approach is validated through simulation and applied to diverse domains including house prices, commodity prices, and public debt.

## Key Contributions

- Introduces a non-parametric, realization-centred framework to detect and characterise path-explosive behaviour in time series through four diagnostic layers: level geometry, growth rate dynamics, normalised curvature, and log-space behaviour.
- Proposes Jaccard co-occurrence and non-parametric intensity concordance measures to assess co-explosive dependencies between series at the episode level.
- Demonstrates that the framework distinguishes between genuine self-reinforcing growth and I(2) dynamics without requiring asymptotic critical values or specific DGP assumptions.

## Open Questions & Future Work

- [[real-time-path-explosive-monitoring]]
- [[multivariate-co-explosive-analysis]]

## Key Concepts

- [[path-explosive-behaviour]]: A realization-centred diagnostic framework for identifying self-reinforcing explosive and co-explosive growth patterns in time series without relying on DGP-based assumptions.

## Archivist Review

I have approved the core 'Path-Explosive Behaviour' framework as a distinct, reusable diagnostic method for non-parametric time series analysis. I also approved two research directions that address the inherent limitations of the current retrospective, pairwise implementation: real-time monitoring and multivariate extension, both of which are high-impact bottlenecks for its practical utility in systemic economic assessment. No datasets were approved as they were used merely for empirical validation.

### Approved Concepts
- Path-Explosive Behaviour: It shifts the focus from traditional DGP-based unit root testing to observable path properties, providing a novel diagnostic framework for self-reinforcing dynamics.

### Approved Open Questions
- Real-time Path-Explosive Monitoring: Extending the framework to support real-time detection is critical for policy intervention and infrastructure capacity planning, where decisions are time-sensitive.
- Multivariate Path-Co-Explosive Analysis: Multivariate analysis is essential for understanding systemic risk and spillover effects in interconnected economic networks which cannot be captured by pairwise analysis alone.

## Links

- [Abstract](https://arxiv.org/abs/2604.16186)
- [PDF](https://arxiv.org/pdf/2604.16186)

