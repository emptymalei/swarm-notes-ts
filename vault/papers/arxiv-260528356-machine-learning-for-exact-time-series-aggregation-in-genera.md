---
# CSL-compatible fields
title: "Machine Learning for Exact Time Series Aggregation in Generation Expansion Planning with Energy Storage"
author:
  - literal: "Jakub Rybka"
  - literal: "Luca Santosuosso"
  - literal: "Thomas Klatzer"
  - literal: "Sonja Wogrin"
issued:
  date-parts:
    - [2026, 5, 27]
url: "https://arxiv.org/abs/2605.28356"

# Custom fields
paper_id: "2605.28356"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "ml-guided-constraint-preserving-temporal-aggregation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-28T05:31:20Z"
created_at: "2026-05-28T05:31:20Z"
---

# Machine Learning for Exact Time Series Aggregation in Generation Expansion Planning with Energy Storage

**Authors**: Jakub Rybka, Luca Santosuosso, Thomas Klatzer, Sonja Wogrin
**Date**: 2026-05-27
**Paper ID**: [arxiv:2605.28356](https://arxiv.org/abs/2605.28356)

## Summary

This paper addresses the computational complexity of Generation Expansion Planning (GEP) by proposing an iterative time series aggregation method that bridges the gap between heuristic reduction and exact solutions. By training an ML model to estimate the marginal costs of the full-scale GEP, the proposed approach identifies and preserves critical active constraints during temporal clustering. This method effectively reduces the GEP model size while providing a rigorous assessment of the optimality gap compared to standard heuristic aggregation techniques. Evaluation shows that including marginal cost features significantly enhances the representation of system dynamics compared to traditional input-only clustering.

## Key Contributions

- Introduces an iterative time series aggregation (TSA) method for Generation Expansion Planning (GEP) that quantifies the optimality gap relative to full-scale models.
- Achieves exact temporal aggregation by incorporating ML-based marginal cost estimates as features to guide clustering toward preserving active constraints.
- Demonstrates that feature-guided clustering using marginal cost estimates significantly outperforms traditional TSA methods reliant solely on input data distribution.

## Key Concepts

- [[ml-guided-constraint-preserving-temporal-aggregation]]: A technique that uses ML-estimated marginal costs as features for temporal clustering to ensure that aggregated time-series models retain the active constraints of the original, full-scale planning problems.

## Archivist Review

I approved the overarching mechanism for ML-guided constraint-preserving temporal aggregation as it provides a principled approach to dimensionality reduction in optimization, which is a significant and reusable concept. I rejected the initial candidate because the approved version more accurately captures the core technical novelty: bridging the gap between heuristic reduction and exact constraint retention via surrogate modeling. No datasets or open questions were proposed, and none were added to maintain scarcity.

### Approved Concepts
- ML-Guided Constraint-Preserving Temporal Aggregation: It bridges the gap between heuristic aggregation and exact solutions in complex optimization tasks by using surrogate models to identify and preserve the active constraint set.

### Rejected Candidates
- [concept] Machine Learning-based Marginal Cost Estimation for Time Series Aggregation (`ml-based-marginal-cost-estimation-for-tsa`) - duplicate_existing: This is largely synonymous with the approved, more precisely named mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2605.28356)
- [PDF](https://arxiv.org/pdf/2605.28356)

