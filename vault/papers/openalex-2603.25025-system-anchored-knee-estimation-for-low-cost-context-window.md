---
# CSL-compatible fields
title: "System-Anchored Knee Estimation for Low-Cost Context Window Selection in PDE Forecasting"
author:
  - literal: "Wenshuo Wang"
  - literal: "Fan Zhang"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25025"

# Custom fields
paper_id: "2603.25025"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "modeldifferentiable-programming"
  - "neural-operators"
architectures:
  []
datasets:
  - "PDEBench"
concept_slugs:
  - "system-anchored-knee-estimation-sake"
  - "knee-aware-selection"
dataset_slugs:
  - "pdebench"
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:16:11Z"
created_at: "2026-03-29T20:16:11Z"
---

# System-Anchored Knee Estimation for Low-Cost Context Window Selection in PDE Forecasting

**Authors**: Wenshuo Wang, Fan Zhang
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25025](https://arxiv.org/abs/2603.25025)

## Summary

This paper addresses the unformalized problem of selecting an optimal, low-cost context window for autoregressive neural PDE simulators. The authors propose System-Anchored Knee Estimation (SAKE), a novel two-stage approach that first anchors candidate windows based on physical interpretability and then applies knee-aware selection to optimize the cost-accuracy trade-off. Evaluating across eight PDEBench families, SAKE proved to be the strongest low-cost selector under a matched budget constraint. The method significantly reduced search costs (0.051 cost ratio) while maintaining high predictive accuracy, demonstrating a practical solution for deploying such simulators efficiently.

## Key Contributions

- Formalized the problem of context-window selection for fixed-window autoregressive neural PDE simulators as a low-cost algorithmic problem.
- Introduced System-Anchored Knee Estimation (SAKE), a two-stage method combining system anchors with knee-aware selection.
- SAKE achieved superior overall performance as a low-cost selector across eight PDEBench families compared to existing methods.
- Demonstrated significant cost savings, achieving a cost ratio of 0.051 (94.9% search-cost savings) while maintaining high accuracy (67.8% Exact).

## Limitations

The abstract focuses on matched-budget low-cost selection; specific limitations regarding the quality or applicability of the system anchors in non-physical domains are not detailed.

## Open Questions & Future Work

- [[low-cost-context-window-selection-challenge]]
- [[SAKE-extension-to-adaptive-memory]]

## Key Concepts

- [[system-anchored-knee-estimation-sake]]: A two-stage method that identifies a small set of candidate context windows using physically interpretable system anchors before performing knee-aware selection.
- [[knee-aware-selection]]: A selection strategy that prioritizes points on the \"knee\" of a cost-performance curve, balancing computational expense with predictive accuracy.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 2 concept(s), 2 open question(s), and 1 dataset(s), with 3 rejected candidate note(s).

### Approved Concepts
- System-Anchored Knee Estimation (SAKE): It is the proposed novel, two-stage method designed to formally solve the context-window selection problem for autoregressive neural PDE simulators.
- Knee-Aware Selection: This technique is explicitly used to optimize the trade-off between cost and performance (Exact/Within-1 accuracy) when selecting the context window size.

### Approved Open Questions
- Efficient context-window identification: The efficiency of training and tuning neural PDE simulators is bottlenecked by the high cost associated with retraining for every potential context window length. Establishing a low-cost, reliable selection method is crucial for practical deployment.
- Extension to adaptive memory simulators: Adaptive memory models represent a significant architectural direction in time-series forecasting; extending SAKE to select the necessary memory configuration in such models would broaden its utility beyond the current fixed-window scope.

### Rejected Candidates
- [dataset] PDEBench (`pdebenck`) - generic: PDEBench is a benchmark suite, not a single, specific dataset, making it too broad for a dedicated vault entry unless the paper introduces a new subset.
- [open_question] Robustness of system anchors to noise (`SAKE-robustness-to-noisy-anchors`) - low_impact: This is a standard ablation/robustness check (investigating anchor quality under noise) rather than a fundamental, unresolved architectural or theoretical bottleneck.
- [open_question] Resolving difficult selection cases (`unresolved-hard-cases-selection-divergence`) - paper_local: This open question is too local, referencing a specific failure case (RDB/ConvLSTM) that seems related to dataset/model mismatch rather than a universal, unsolved theoretical mechanism for selection.

## Datasets

- [[pdebench]]

## Links

- [Abstract](https://arxiv.org/abs/2603.25025)
- [PDF](https://arxiv.org/pdf/2603.25025)

