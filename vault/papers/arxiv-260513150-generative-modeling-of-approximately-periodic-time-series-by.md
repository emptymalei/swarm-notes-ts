---
# CSL-compatible fields
title: "Generative Modeling of Approximately Periodic Time Series by a Posterior-Weighted Gaussian Process"
author:
  - literal: "Elias Reich"
  - literal: "Saverio Messineo"
  - literal: "Stefan Huber"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13150"

# Custom fields
paper_id: "2605.13150"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "posterior-weighted-gaussian-process"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:24:47Z"
created_at: "2026-05-14T05:24:47Z"
---

# Generative Modeling of Approximately Periodic Time Series by a Posterior-Weighted Gaussian Process

**Authors**: Elias Reich, Saverio Messineo, Stefan Huber
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13150](https://arxiv.org/abs/2605.13150)

## Summary

This paper addresses the challenge of modeling approximately periodic time series, such as those found in industrial processes, where signals follow a common structural trajectory but vary in duration and fine-scale dynamics. The authors propose a stochastic generative model based on a Gaussian Process with a custom-designed kernel that modulates the posterior. This approach enables the decoupling of stable intra-repetition structural features from inter-repetition variability, allowing for the generation of realistic synthetic data. The methodology demonstrates superior handling of structural regularities compared to standard strictly periodic or non-periodic modeling approaches.

## Key Contributions

- Introduces a stochastic generative model that decouples intra-repetition structure from inter-repetition variability in approximately periodic signals.
- Proposes a two-stage GP construction using a novel kernel to modulate the posterior for consistent mean behavior across repetitions.
- Demonstrates that the model effectively generates realistic synthetic trajectories for repetitive processes while accounting for variations in duration and amplitude.

## Open Questions & Future Work

- [[scalable-likelihood-approx-periodic-gp]]

## Key Concepts

- [[posterior-weighted-gaussian-process]]: A Gaussian process variant using a modulated posterior kernel to model approximately periodic time series with inter-repetition variability.

## Archivist Review

I approved the 'Posterior-Weighted Gaussian Process' as a distinct, novel approach to modeling quasi-periodic temporal structure, and the open question regarding its likelihood scalability as it addresses a fundamental bottleneck in the proposed framework. I applied a strict filter to ensure only the central methodological contribution and its primary limitation were retained, consistent with the goal of tracking reusable techniques in time series forecasting. No datasets were identified for approval as none were distinct or core to the work.

### Approved Concepts
- Posterior-Weighted Gaussian Process: Provides a principled mechanism for decoupling stable intra-repetition structural features from inter-repetition variability in quasi-periodic time series.

### Approved Open Questions
- Scaling Likelihood for Many Repetitions: The current likelihood evaluation mechanism precludes the application of the model to industrial systems with long sequences of repetitions, limiting its practical utility.

## Links

- [Abstract](https://arxiv.org/abs/2605.13150)
- [PDF](https://arxiv.org/pdf/2605.13150)

