---
# CSL-compatible fields
title: "FAST: A Synergistic Framework of Attention and State-space Models for Spatiotemporal Traffic Prediction"
author:
  - literal: "Xinjin Li"
  - literal: "Jinghan Cao"
  - literal: "Mengyue Wang"
  - literal: "Yue Wu"
  - literal: "Longxiang Yan"
  - literal: "Yeyang Zhou"
  - literal: "Ziqi Sha"
  - literal: "Yu Ma"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13453"

# Custom fields
paper_id: "2604.13453"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "fast-architecture"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:08:12Z"
created_at: "2026-04-17T05:08:12Z"
---

# FAST: A Synergistic Framework of Attention and State-space Models for Spatiotemporal Traffic Prediction

**Authors**: Xinjin Li, Jinghan Cao, Mengyue Wang, Yue Wu, Longxiang Yan, Yeyang Zhou, Ziqi Sha, Yu Ma
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13453](https://arxiv.org/abs/2604.13453)

## Summary

FAST is a unified spatiotemporal framework designed to balance predictive expressiveness with computational efficiency in large-scale traffic forecasting. By employing a Temporal-Spatial-Temporal architecture, the model leverages temporal attention for complex sequence patterns and Mamba-based selective state-space layers for linear-complexity spatial dependency modeling. The framework further incorporates a multi-source embedding mechanism and hierarchical skip-connection fusion, demonstrating robust performance improvements across major traffic benchmarks compared to traditional Transformer and GNN architectures.

## Key Contributions

- Introduced FAST, a unified spatiotemporal architecture combining temporal attention modules with linear-complexity Mamba-based spatial modeling.
- Developed a multi-source spatiotemporal embedding to integrate heterogeneous data including historical flow, temporal context, and node-level metadata.
- Achieved superior predictive accuracy on PeMS04, PeMS07, and PeMS08 benchmarks, with up to 4.3% lower RMSE and 2.8% lower MAE compared to state-of-the-art Transformer and GNN-based baselines.

## Open Questions & Future Work

- [[extending-spatiotemporal-frameworks-for-complex-urban-tasks]]

## Key Concepts

- [[fast-architecture]]: A hybrid spatiotemporal architecture that alternates between temporal attention and selective state-space-based spatial modules to achieve scalability and expressiveness.

## Archivist Review

I approved the FAST Architecture as a key concept because it represents a distinct and reusable pattern for merging temporal attention with spatial state-space models. I rejected the original 'FAST framework' candidate in favor of 'FAST Architecture' to better define the technical contribution. I also approved the open question regarding the scalability and extensibility of these models to complex urban settings, which is a substantial bottleneck for practical deployment. PeMS datasets were not approved as they are standard benchmarks in the field.

### Approved Concepts
- FAST Architecture: It provides a reusable architectural template for balancing attention-based temporal modeling with linear-complexity state-space-based spatial modeling in graph-structured time series.

### Approved Open Questions
- Extending Spatiotemporal Forecasting Frameworks: Addressing these challenges is essential for transitioning from specialized traffic forecasting benchmarks to real-world, dynamic urban intelligence systems.

### Rejected Candidates
- [concept] FAST (Framework of Attention and State-space Models for Traffic) (`fast-framework`) - other: Renamed to 'FAST Architecture' to focus on the modular design rather than the specific framework name, and to adhere to better naming conventions.

## Links

- [Abstract](https://arxiv.org/abs/2604.13453)
- [PDF](https://arxiv.org/pdf/2604.13453)

