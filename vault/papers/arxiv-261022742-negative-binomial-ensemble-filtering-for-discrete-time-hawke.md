---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Negative-binomial ensemble filtering for discrete-time Hawkes network reconstruction"
description: "This paper introduces a sequential ensemble filter designed for reconstructing directed networks from overdispersed multivariate count data. Using a discrete-time negative-binomial Hawkes process, the authors derive formal stability conditions and implement an online learning framework for network structure and dispersion. Results on synthetic experiments and Chicago crime data show that while Poisson models can match point accuracy, the proposed negative-binomial filter provides significantly better calibrated uncertainty estimates and recovers dynamic changes in network influence."
resource: "https://arxiv.org/abs/2610.22742"
tags:
  - "multivariate-time-series"
  - "network-analysis"
  - "probabilistic-forecasting"
  - "uncertainty-quantification"
  - "online-learning"
  - "count-data"
  - "stability-analysis"
  - "ensemble-learning"
  - "time-series-analysis"
timestamp: "2026-10-19T04:37:24Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Naratip Santitissadeekorn"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22742"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "discrete-time-negative-binomial-hawkes-process"
    description: "A variant of the Hawkes process for discrete-time multivariate counts that incorporates the negative-binomial distribution to handle overdispersion and provides exact moment stability conditions."
datasets:
  []
open_questions:
  - name: "contemporaneous-dependence-self-exciting-counts"
    description: "Current sequential filtering approaches for discrete-time Hawkes processes typically assume that observations are conditionally independent across nodes given the past. Developing filters that relax this cross-node independence assumption is necessary to accurately model networks where nodes are subject to persistent common drivers or simultaneous excitation."
  - name: "hybrid-batch-sequential-network-estimation"
    description: "There is a need for hybrid estimation frameworks that combine batch methods with sequential filtering. Batch methods could be used to estimate aggregate properties like row totals of the excitation matrix (which are more stable), while sequential filters resolve the dynamic composition and redistribution of influence within those totals."
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:37:24Z"
created_at: "2026-10-19T04:37:24Z"
---

# Negative-binomial ensemble filtering for discrete-time Hawkes network reconstruction

**Authors**: Naratip Santitissadeekorn
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22742](https://arxiv.org/abs/2610.22742)

## Summary

This paper introduces a sequential ensemble filter designed for reconstructing directed networks from overdispersed multivariate count data. Using a discrete-time negative-binomial Hawkes process, the authors derive formal stability conditions and implement an online learning framework for network structure and dispersion. Results on synthetic experiments and Chicago crime data show that while Poisson models can match point accuracy, the proposed negative-binomial filter provides significantly better calibrated uncertainty estimates and recovers dynamic changes in network influence.

## Key Contributions

- Derivation of exact first- and second-moment stability conditions for the discrete-time negative-binomial Hawkes process.
- Development of a sequential ensemble filter that simultaneously learns directed network connections and dispersion parameters online.
- Introduction of a row-composition parameter forecast mechanism to maintain ensemble variation, allowing the model to adapt to abrupt structural changes in influence.
- Demonstration of superior predictive and parameter uncertainty calibration compared to Poisson-based filtering methods on both synthetic and real-world datasets.

## Limitations

The paper primarily focuses on regular time grids and may require extensions for continuous-time or irregularly sampled data.

## Open Questions & Future Work

- [[contemporaneous-dependence-self-exciting-counts]]
- [[hybrid-batch-sequential-network-estimation]]

## Key Concepts

- [[discrete-time-negative-binomial-hawkes-process]]: A variant of the Hawkes process for discrete-time multivariate counts that incorporates the negative-binomial distribution to handle overdispersion and provides exact moment stability conditions.

## Archivist Review

I approved the Discrete-time Negative-Binomial Hawkes Process as a concept because it represents a significant theoretical extension (with stability proofs) to standard point process models. I approved two open questions that address fundamental technical bottlenecks: the handling of contemporaneous dependence in multivariate counts and the identifiability of global vs. local parameters in sequential network estimation. I rejected the Chicago crime dataset as it is a routine application case rather than a reusable benchmark.

### Approved Concepts
- Discrete-time Negative-Binomial Hawkes Process: It provides a mathematically rigorous framework for modeling overdispersed multivariate count data with self-excitation, including crucial stability proofs for first and second moments.

### Approved Open Questions
- Contemporaneous Dependence in Exciting Processes: Ignoring contemporaneous dependence can lead to biased network reconstruction, as shared external influences may be incorrectly attributed to direct excitation between nodes.
- Hybrid Batch-Sequential Network Estimation: Sequential filters often struggle to update global parameter scales (total excitation) even when the relative influence of source nodes is correctly tracked, suggesting a fundamental limitation in using only local innovations for global parameter scaling.

### Rejected Candidates
- [dataset] Chicago Community Area Property-Crime Counts (`chicago-community-area-property-crime-counts`) - paper_local: This is an application of publicly available crime data for validation rather than a standardized, widely-reused benchmark dataset in the ML community.

## Links

- [Abstract](https://arxiv.org/abs/2610.22742)
- [PDF](https://arxiv.org/pdf/2610.22742)

