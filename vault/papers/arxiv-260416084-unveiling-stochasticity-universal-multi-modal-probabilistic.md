---
# CSL-compatible fields
title: "Unveiling Stochasticity: Universal Multi-modal Probabilistic Modeling for Traffic Forecasting"
author:
  - literal: "Weijiang Xiong"
  - literal: "Robert Fonod"
  - literal: "Nikolas Geroliminis"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.16084"

# Custom fields
paper_id: "2604.16084"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "probabilistic-forecasting"
  - "spatio-temporal-forecasting"
  - "uncertainty-quantification"
  - "traffic-management"
architectures:
  []
datasets:
  []
concept_slugs:
  - "gmm-probabilistic-output-layer"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:09:22Z"
created_at: "2026-04-20T05:09:22Z"
---

# Unveiling Stochasticity: Universal Multi-modal Probabilistic Modeling for Traffic Forecasting

**Authors**: Weijiang Xiong, Robert Fonod, Nikolas Geroliminis
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.16084](https://arxiv.org/abs/2604.16084)

## Summary

This paper addresses the limitation of deterministic predictions in spatio-temporal traffic forecasting by introducing a universal, drop-in Gaussian Mixture Model (GMM) layer. This lightweight modification allows existing architectures to provide uncertainty-aware probabilistic outputs without requiring changes to their base training pipelines. The approach is evaluated against multiple benchmarks, demonstrating improved predictive accuracy and superior uncertainty quantification compared to unimodal or deterministic alternatives. Furthermore, the authors establish a robust evaluation procedure and validate the method's performance under imperfect data conditions in a dense urban traffic network.

## Key Contributions

- Proposes a universal, drop-in GMM output layer that enables probabilistic forecasting for existing deterministic spatio-temporal models.
- Enables training of probabilistic models using only NLL loss, eliminating the need for auxiliary regularization or architectural modifications.
- Introduces a systematic evaluation framework for probabilistic traffic forecasting utilizing cumulative distribution functions and confidence intervals.

## Open Questions & Future Work

- [[multi-modal-probabilistic-forecasting-limits]]

## Key Concepts

- [[gmm-probabilistic-output-layer]]: A drop-in Gaussian Mixture Model output layer that enables probabilistic forecasting for existing deterministic spatio-temporal architectures.

## Archivist Review

I approved the GMM-based output layer as a reusable architectural pattern for probabilistic forecasting. The open question was refined to focus on the fundamental challenge of multi-modal stochasticity in time-series rather than generic future work. No datasets were approved as none were specifically named as novel contributions or critical benchmarks unique to this study.

### Approved Concepts
- GMM-based Probabilistic Output Layer: Provides a universal, architecture-agnostic mechanism to transform deterministic spatio-temporal models into probabilistic ones without pipeline changes.

### Approved Open Questions
- Multi-modal Probabilistic Modeling Limits: Essential for scaling probabilistic forecasting, as moving beyond basic distributional assumptions remains a critical challenge in spatio-temporal modeling.

## Links

- [Abstract](https://arxiv.org/abs/2604.16084)
- [PDF](https://arxiv.org/pdf/2604.16084)

