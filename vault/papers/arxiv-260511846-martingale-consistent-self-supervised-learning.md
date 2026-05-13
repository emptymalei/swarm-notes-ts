---
# CSL-compatible fields
title: "Martingale-Consistent Self-Supervised Learning"
author:
  - literal: "Moritz Gögl"
  - literal: "Hanwen Xing"
  - literal: "Christopher Yau"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11846"

# Custom fields
paper_id: "2605.11846"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "martingale-consistent-ssl"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:24:28Z"
created_at: "2026-05-13T05:24:28Z"
---

# Martingale-Consistent Self-Supervised Learning

**Authors**: Moritz Gögl, Hanwen Xing, Christopher Yau
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11846](https://arxiv.org/abs/2605.11846)

## Summary

This paper introduces a martingale-consistent self-supervised learning (SSL) framework designed to ensure coherence between predictions made under varying levels of information granularity, such as coarse versus refined views. Unlike standard invariance objectives, this method enforces that coarse predictions match the expected refined predictions, preventing systematic drift without forcing identical representations. The framework is supported by an unbiased two-sample Monte Carlo estimator and shows significant robustness gains in partial-observation settings across multiple data modalities.

## Key Contributions

- Introduces a martingale-consistent SSL framework that constrains the expected refined prediction to ensure coherence across information levels.
- Provides an unbiased two-sample Monte Carlo estimator based on stochastic refinement for practical implementation.
- Demonstrates improved robustness and calibration in semi-self-supervised and label-free regimes across time-series, tabular, and image data under partial observation.

## Open Questions & Future Work

- [[martingale-ssl-refinement-scaling]]

## Key Concepts

- [[martingale-consistent-ssl]]: A self-supervised learning framework that enforces martingale coherence between predictions across different information granularities.

## Archivist Review

The paper is approved for its novel framing of SSL coherence as a martingale property, which provides a principled alternative to standard invariance objectives. The selected open question addresses the practical scalability bottlenecks associated with the refinement mechanism, which is central to the viability of this approach in large-scale settings. No datasets were approved as they were generic categories rather than specific, novel benchmarks.

### Approved Concepts
- Martingale-Consistent Self-Supervised Learning: It formalizes coherence between coarse and refined information views as a martingale, preventing systematic drift in SSL.

### Approved Open Questions
- Scalable Refinement Mechanisms for SSL: As the authors state, the dependence on the refinement mechanism is a primary bottleneck for scaling martingale-based objectives, making it a critical path for research in foundation models.

## Links

- [Abstract](https://arxiv.org/abs/2605.11846)
- [PDF](https://arxiv.org/pdf/2605.11846)

