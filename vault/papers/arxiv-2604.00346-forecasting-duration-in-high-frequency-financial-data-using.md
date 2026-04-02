---
# CSL-compatible fields
title: "Forecasting duration in high-frequency financial data using a self-exciting flexible residual point process"
author:
  - literal: "Kyungsub Lee"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.00346"

# Custom fields
paper_id: "2604.00346"
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
processed_at: "2026-04-02T05:38:50Z"
created_at: "2026-04-02T05:38:50Z"
---

# Forecasting duration in high-frequency financial data using a self-exciting flexible residual point process

**Authors**: Kyungsub Lee
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.00346](https://arxiv.org/abs/2604.00346)

## Summary

This paper introduces a self-exciting flexible residual point process designed to forecast interarrival times in limit order books, addressing the challenge of heavy-tailed distributions in high-frequency trading. The model preserves essential self-exciting and decay properties while integrating empirical distributional characteristics of the duration data. The author provides a rigorous analysis of the process's stochastic stability, establishing its status as a positive Harris recurrent Markov chain. Empirical evaluations demonstrate that this framework offers robust predictive accuracy in complex, ultra-high-frequency financial environments.

## Key Contributions

- Introduces a self-exciting flexible residual point process to model limit order book durations while capturing heavy-tailed interarrival dynamics.
- Provides theoretical proofs for stochastic stability, demonstrating that the process is irreducible, aperiodic, and positive Harris recurrent.
- Achieves superior predictive performance in duration forecasting for ultra-high-frequency financial data compared to standard alternatives.

## Open Questions & Future Work

- [[refining-intensity-latent-dynamics]]

## Archivist Review

I approved one open question regarding the modeling of high-frequency durations, as it addresses a significant, recurring bottleneck in financial econometrics. I rejected the proposed model architecture as it is a specialized technical construction specific to this paper's domain rather than a general-purpose methodology.

### Approved Open Questions
- Improving duration model dynamics: This is a fundamental bottleneck in the field of financial econometrics where current models fail to fully capture the empirical reality of ultra-high-frequency data, necessitating structural innovations to improve both forecasting and risk assessment.

### Rejected Candidates
- [concept] Self-exciting flexible residual point process (`self-exciting-flexible-residual-point-process`) - not_reusable: This is a specific model architecture tailored to a single paper's application rather than a broadly reusable methodological framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.00346)
- [PDF](https://arxiv.org/pdf/2604.00346)

