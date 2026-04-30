---
# CSL-compatible fields
title: "On the Role of Time Series Clustering in Traffic Matrix Prediction"
author:
  - literal: "Martha Cash"
  - literal: "Charlotte Fowler"
  - literal: "Alexander M. Wyglinski"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.26081"

# Custom fields
paper_id: "2604.26081"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "abilene"
  - "geant"
concept_slugs:
  []
dataset_slugs:
  - "abilene"
  - "geant"
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:14:35Z"
created_at: "2026-04-30T05:14:35Z"
---

# On the Role of Time Series Clustering in Traffic Matrix Prediction

**Authors**: Martha Cash, Charlotte Fowler, Alexander M. Wyglinski
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.26081](https://arxiv.org/abs/2604.26081)

## Summary

This paper investigates the impact of time-series clustering on the prediction accuracy of traffic matrices (TMs). By grouping heterogeneous traffic flows into smaller, more homogeneous clusters, the authors propose a framework that trains specialized predictors for each group, thereby bypassing the limitations of monolithic global models. Experimental results on the Abilene and GÉANT datasets show that this clustering-based approach provides substantial performance improvements over global baselines with moderate computational overhead. Findings reveal that while various feature representations for clustering yield different partitions, the performance improvements are largely robust to the specific clustering structure, suggesting that the primary advantage is efficient task decomposition.

## Key Contributions

- Proposes a clustering-based prediction framework to decompose heterogeneous traffic matrix (TM) forecasting into smaller, more manageable subproblems.
- Demonstrates that clustering traffic flows based on representations like ACF and PSD consistently outperforms global forecasting models while maintaining lower computational costs than full local prediction.
- Finds that while clustering representations significantly affect flow grouping, their impact on overall RMSE is marginal, indicating that task decomposition is the primary driver of performance gains.

## Open Questions & Future Work

- [[tm-prediction-clustering-granularity-optimization]]

## Archivist Review

The paper investigates the impact of clustering representations on TM prediction accuracy. I have approved the Abilene and GÉANT datasets as they are established benchmarks for this specific domain. The proposed open question was rewritten to clarify the bottleneck regarding task decomposition, granularity, and predictability. Concepts were rejected as the clustering approach described is a well-known methodology in time-series decomposition.

### Approved Open Questions
- Optimizing TM Clustering Granularity: This addresses the fundamental trade-off between model granularity, computational cost, and performance in network traffic engineering, providing a roadmap for developing adaptive prediction frameworks.

### Rejected Candidates
- [open_question] Optimization of TM Clustering (`traffic-matrix-clustering-optimization`) - other: The proposed question was rewritten for clarity and to better align with vault naming conventions while avoiding overly descriptive titles.

## Datasets

- [[abilene]]
- [[geant]]

## Links

- [Abstract](https://arxiv.org/abs/2604.26081)
- [PDF](https://arxiv.org/pdf/2604.26081)

