---
# CSL-compatible fields
title: "Improving Machine Learning Performance with Synthetic Augmentation"
author:
  - literal: "Mel Sohm"
  - literal: "Charles Dezons"
  - literal: "Sami Sellami"
  - literal: "Oscar Ninou"
  - literal: "Axel Pincon"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.14498"

# Custom fields
paper_id: "2604.14498"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "data-augmentation"
  - "finance"
  - "bias-variance-tradeoff"
architectures:
  []
datasets:
  []
concept_slugs:
  - "size-matched-null-augmentation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:52:39Z"
created_at: "2026-04-18T04:52:39Z"
---

# Improving Machine Learning Performance with Synthetic Augmentation

**Authors**: Mel Sohm, Charles Dezons, Sami Sellami, Oscar Ninou, Axel Pincon
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.14498](https://arxiv.org/abs/2604.14498)

## Summary

This paper examines the statistical foundations of synthetic data augmentation in financial machine learning, characterizing it as a structural bias-variance trade-off. The authors develop a robust evaluation framework, centered on a size-matched null augmentation and a non-parametric block permutation test, to differentiate true informational gains from trivial sample-size effects. Their empirical analysis across multiple synthetic generators and financial tasks reveals that while augmentation helps in variance-dominant regimes, it often induces harmful distributional distortion in bias-dominant settings.

## Key Contributions

- Formalizes synthetic augmentation as a modification of the effective training distribution, identifying a structural bias-variance trade-off induced by distributional shifts.
- Introduces a size-matched null augmentation framework and a non-parametric block permutation test to isolate genuine informational gains from mechanical sample-size effects.
- Demonstrates through extensive experiments that synthetic augmentation benefits variance-dominant regimes (e.g., volatility forecasting) but degrades performance in bias-dominant tasks (e.g., directional prediction).

## Open Questions & Future Work

- [[optimal-synthetic-augmentation-alignment]]

## Key Concepts

- [[size-matched-null-augmentation]]: A statistical framework used to disentangle the informational gains of synthetic data augmentation from mechanical sample-size effects.

## Archivist Review

The paper provides a rigorous statistical framework for isolating the impacts of synthetic data augmentation. I have approved the 'size-matched null augmentation' concept as it represents a reusable experimental control for evaluating synthetic data in forecasting, and the 'optimal-synthetic-augmentation-alignment' open question as it frames the fundamental challenge of bias-variance management in augmentation. No new datasets were identified that were not already generic or excluded.

### Approved Concepts
- Size-matched null augmentation: This is a novel statistical control designed specifically to isolate the informational benefits of synthetic data from simple increases in training sample size.

### Approved Open Questions
- Optimal Synthetic Augmentation Alignment: This is central to the paper's core finding that augmentation is conditional rather than universal, and it addresses the fundamental difficulty of selecting synthetic data generators without explicit access to the unknown future test distribution.

## Links

- [Abstract](https://arxiv.org/abs/2604.14498)
- [PDF](https://arxiv.org/pdf/2604.14498)

