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
  - "bayesian-inference"
  - "hidden-markov-model"
architectures:
  []
datasets:
  []
concept_slugs:
  - "modified-parallel-tempering-for-hmms"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:13:24Z"
created_at: "2026-04-29T05:13:24Z"
---

# Bayesian inference for hidden Markov models under genuine multimodality with application to ecological time series

**Authors**: Marco A. Gallegos-Herrada, Vianey Leos-Barajas, Jeffrey S. Rosenthal
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24587](https://arxiv.org/abs/2604.24587)

## Summary

This paper addresses the challenge of multimodality in Bayesian Hidden Markov Model (HMM) inference, which persists even after addressing label switching. The authors demonstrate that standard Parallel Tempering implementations are often insufficient for HMM posterior exploration and propose a modified algorithm incorporating custom non-informative priors. The methodology is validated through the analysis of blue whale dive behavioral patterns, showing significant improvements in posterior exploration compared to standard approaches.

## Key Contributions

- Identifies and characterizes common implementation pitfalls of the Parallel Tempering (PT) algorithm in the context of HMM Bayesian inference.
- Introduces novel non-informative prior distributions specifically tailored to facilitate robust posterior exploration in HMMs.
- Demonstrates that the proposed modified PT approach successfully resolves multimodality issues in complex ecological time series, specifically blue whale dive data.

## Open Questions & Future Work

- [[optimal-swap-rate-hmm]]
- [[hmm-mode-validation-diagnostics]]

## Key Concepts

- [[modified-parallel-tempering-for-hmms]]: An improved Parallel Tempering implementation for HMMs that utilizes specifically designed non-informative priors to ensure robust exploration of complex multimodal posterior distributions.

## Archivist Review

I have approved the modified parallel tempering concept as it addresses a core methodological challenge in HMM inference and the two open questions regarding diagnostic rigor and optimal convergence parameters, which are significant bottlenecks in Bayesian time-series analysis. No datasets were approved as none provided met the high-bar requirement for novel, central, or broadly reusable benchmark contributions.

### Approved Concepts
- Modified Parallel Tempering for HMMs: Addresses the failure of standard Parallel Tempering to explore high-dimensional multimodal posteriors in HMMs, which is critical for robust Bayesian time-series inference.

### Approved Open Questions
- Optimal swap rate for HMMs: Achieving the optimal swap acceptance rate is critical for maximizing the efficiency of parallel tempering and ensuring robust exploration, impacting computational cost and accuracy of inference.
- Diagnostic methods for HMM modes: Distinguishing between genuine and spurious modes is foundational to ensuring that parameter estimates and uncertainty quantifications are valid rather than misleading.

## Links

- [Abstract](https://arxiv.org/abs/2604.24587)
- [PDF](https://arxiv.org/pdf/2604.24587)

