---
# CSL-compatible fields
title: "Pre-localization of Massive Black Hole Binaries in the Millihertz Band"
author:
  - literal: "Xue-Ting Zhang"
  - literal: "Jonathan Gair"
  - literal: "Chris Messenger"
  - literal: "Natalia Korsakova"
  - literal: "Yi-Ming Hu"
  - literal: "Hong-Yu Chen"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24330"

# Custom fields
paper_id: "2604.24330"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "bayesian-inference"
  - "gravitational-wave-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "amortized-bayesian-inference-pipeline"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:14:02Z"
created_at: "2026-04-29T05:14:02Z"
---

# Pre-localization of Massive Black Hole Binaries in the Millihertz Band

**Authors**: Xue-Ting Zhang, Jonathan Gair, Chris Messenger, Natalia Korsakova, Yi-Ming Hu, Hong-Yu Chen
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24330](https://arxiv.org/abs/2604.24330)

## Summary

This paper introduces a fast, amortized Bayesian inference pipeline for early-warning analysis of Massive Black Hole Binary (MBHB) signals in space-borne gravitational-wave detectors like TianQin. By combining a learned embedding of the detector time series with a neural spline flow, the method enables rapid source parameter estimation and sky localization. The pipeline significantly reduces computational overhead, achieving comparable accuracy to parallel-tempered Markov chain Monte Carlo (PTMCMC) methods while providing sufficient lead time for electromagnetic follow-up observations.

## Key Contributions

- Developed a normalizing flow-based inference pipeline using neural spline flows to achieve near-real-time parameter estimation for MBHB gravitational-wave signals.
- Demonstrated the capability to produce sky localizations of ~20 deg^2 roughly 15 minutes before merger for TianQin-like configurations.
- Validated the pipeline against PTMCMC benchmarks, showing comparable parameter recovery accuracy and uncertainty while reducing computational latency to ~1 minute per event.

## Open Questions & Future Work

- [[generalizing-mbhb-inference-pipelines]]

## Key Concepts

- [[amortized-bayesian-inference-pipeline]]: A neural-based pipeline that maps time-series data directly to posterior distributions, enabling near-real-time gravitational wave source characterization.

## Archivist Review

I approved the concept of 'amortized Bayesian inference pipeline' as it captures the architectural shift in GW analysis from slow MCMC to neural-based inference. I also approved the open question regarding the generalization of these pipelines to complex astrophysical parameters and noise, as this is a key barrier to deploying these models on real space-based detector streams. Other candidates were either too local to the paper or subcomponents of the approved overarching framework.

### Approved Concepts
- Amortized Bayesian Inference Pipeline: This represents a shift from iterative sampling (PTMCMC) to amortized neural approaches for gravitational-wave parameter estimation, a pattern likely to recur in low-latency astrophysical forecasting.

### Approved Open Questions
- Generalizing MBHB Inference Pipelines: This question addresses the gap between idealized simulation-based neural inference and the physical complexity required for operational space-based GW observatories.

### Rejected Candidates
- [concept] Normalizing Flow-Based Inference Pipeline (`normalising-flow-based-inference-pipeline`) - subcomponent_of_broader_mechanism: This is a subcomponent or specific implementation of the broader amortized Bayesian inference framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.24330)
- [PDF](https://arxiv.org/pdf/2604.24330)

