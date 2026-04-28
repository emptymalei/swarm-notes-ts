---
# CSL-compatible fields
title: "Bayesian inference for hidden Markov models under genuine multimodality with application to ecological time series"
author:
  - literal: "Marco A. Gallegos-Herrada"
  - literal: "Vianey Leos-Barajas"
  - literal: "Jeffrey S. Rosenthal"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24587"

# Custom fields
paper_id: "2604.24587"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:13:50Z"
created_at: "2026-04-28T05:13:50Z"
---

# Bayesian inference for hidden Markov models under genuine multimodality with application to ecological time series

**Authors**: Marco A. Gallegos-Herrada, Vianey Leos-Barajas, Jeffrey S. Rosenthal
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24587](https://arxiv.org/abs/2604.24587)

## Summary

This paper addresses the significant challenge of multimodality in Bayesian hidden Markov model (HMM) posterior distributions, which often hinders traditional inference methods even after label switching adjustments. The authors demonstrate that standard parallel tempering (PT) implementations frequently fail in these high-dimensional contexts and propose a modified PT approach alongside new non-informative priors to improve posterior exploration. Validated on blue whale dive behavior datasets, the study highlights how these refinements lead to more reliable inference of underlying movement patterns and state-transition dynamics.

## Key Contributions

- Identifies and formalizes common implementation pitfalls of parallel tempering (PT) algorithms when applied to multimodal HMM posterior distributions.
- Introduces novel non-informative prior distributions designed to stabilize and facilitate MCMC exploration in high-dimensional HMM parameter spaces.
- Demonstrates the effectiveness of the proposed methodological improvements on real-world blue whale dive time series data with covariate-dependent transition matrices.

## Open Questions & Future Work

- [[optimal-swap-acceptance-rate-hmm]]
- [[hmm-multimodality-validation-diagnostics]]

## Archivist Review

The paper provides a focused analysis on the limitations of parallel tempering (PT) for multimodal HMMs and proposes prior refinements. The identified open questions address fundamental challenges in MCMC efficiency and validation for this specific model class, which are significant in Bayesian time-series analysis. No new concepts were approved because the core contribution (PT modifications) is an implementation refinement rather than a reusable architectural concept.

### Approved Open Questions
- Optimal PT swap acceptance rate: Efficient exploration of multimodal posterior distributions in complex models relies on optimizing the PT algorithm, and using suboptimal swap rates can significantly impact computational performance and the ability to explore state spaces.
- Validation of HMM multimodality: Misinterpreting computational artifacts as structural modes can lead to biased scientific conclusions; distinguishing between the two is critical for reliable ecological and behavioral inference.

## Links

- [Abstract](https://arxiv.org/abs/2604.24587)
- [PDF](https://arxiv.org/pdf/2604.24587)

