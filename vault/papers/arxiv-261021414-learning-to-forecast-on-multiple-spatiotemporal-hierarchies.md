---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Learning to Forecast on Multiple Spatiotemporal Hierarchies"
description: "This paper introduces a graph deep learning framework designed for hierarchical spatiotemporal forecasting that leverages multiple aggregation structures simultaneously. By treating different hierarchies as multi-task regularization signals, the model avoids over-fitting to a single view of the data and learns representations that generalize across various spatial and temporal scales. To ensure computational feasibility, the authors introduce a top-down reconciliation operator that guarantees forecast coherence with linear complexity, making it suitable for large-scale and multi-hierarchy settings."
resource: "https://arxiv.org/abs/2610.21414"
tags:
  - "time-series-forecasting"
  - "spatio-temporal-forecasting"
  - "graph-neural-networks"
  - "multi-task-learning"
  - "generalization"
  - "hierarchical-forecasting"
timestamp: "2026-10-18T00:21:26Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Valentina Moretti"
  - literal: "Cesare Alippi"
  - literal: "Andrea Cini"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21414"
paper_source: "arxiv"
architectures:
  - "graph-neural-networks"
concepts:
  - name: "multi-hierarchy-regularization"
    description: "A training strategy for spatiotemporal forecasting that treats multiple distinct aggregation structures as concurrent tasks to improve model generalization."
  - name: "linear-top-down-reconciliation"
    description: "A reconciliation operator for hierarchical time series that ensures coherence across different aggregation levels with O(N) time and space complexity."
datasets:
  []
open_questions:
  - name: "automated-hierarchy-discovery"
    description: "How can optimal spatiotemporal hierarchies be automatically discovered or learned from data when structural relationships are latent or not explicitly provided by domain experts?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:21:26Z"
created_at: "2026-10-18T00:21:26Z"
---

# Learning to Forecast on Multiple Spatiotemporal Hierarchies

**Authors**: Valentina Moretti, Cesare Alippi, Andrea Cini
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21414](https://arxiv.org/abs/2610.21414)

## Summary

This paper introduces a graph deep learning framework designed for hierarchical spatiotemporal forecasting that leverages multiple aggregation structures simultaneously. By treating different hierarchies as multi-task regularization signals, the model avoids over-fitting to a single view of the data and learns representations that generalize across various spatial and temporal scales. To ensure computational feasibility, the authors introduce a top-down reconciliation operator that guarantees forecast coherence with linear complexity, making it suitable for large-scale and multi-hierarchy settings.

## Key Contributions

- Developed a graph deep learning framework that treats different spatiotemporal hierarchies as multi-task regularization signals to improve model generalization.
- Proposed a novel top-down reconciliation operator that achieves coherent forecasts with linear time and space complexity ($O(N)$), overcoming the scalability issues of traditional matrix-based reconciliation.
- Demonstrated that training across multiple hierarchies reduces over-specialization to a single structure and yields forecasting performance competitive with state-of-the-art methods.

## Limitations

The framework requires the definition or sampling of multiple valid aggregation hierarchies, which may rely on domain-specific knowledge or pre-existing spatial/temporal metadata.

## Open Questions & Future Work

- [[automated-hierarchy-discovery]]

## Key Concepts

- [[multi-hierarchy-regularization]]: A training strategy for spatiotemporal forecasting that treats multiple distinct aggregation structures as concurrent tasks to improve model generalization.
- [[linear-top-down-reconciliation]]: A reconciliation operator for hierarchical time series that ensures coherence across different aggregation levels with O(N) time and space complexity.

## Archivist Review

I have approved two concepts and one open question. Multi-Hierarchy Regularization is approved as a novel training paradigm that improves generalization by leveraging structural diversity. Linear Top-Down Reconciliation is approved as it provides a necessary computational advancement for scaling hierarchical models. The open question on Automated Hierarchy Discovery addresses the fundamental bottleneck of reliance on fixed, manually defined structures.

### Approved Concepts
- Multi-Hierarchy Regularization: Addresses the limitation of current hierarchical forecasting models that over-specialize to a single fixed aggregation structure, allowing for more robust and generalizable representations.
- Linear Top-Down Reconciliation: Provides a solution to the scalability bottleneck in hierarchical forecasting, where traditional reconciliation methods often suffer from high computational complexity.

### Approved Open Questions
- Automated Spatiotemporal Hierarchy Discovery: Automated discovery would extend hierarchical forecasting to domains where hierarchies are unknown or change dynamically over time.

## Links

- [Abstract](https://arxiv.org/abs/2610.21414)
- [PDF](https://arxiv.org/pdf/2610.21414)

