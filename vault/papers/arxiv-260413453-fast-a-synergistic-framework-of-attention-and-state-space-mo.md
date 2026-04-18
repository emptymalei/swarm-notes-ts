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
  - "time-series"
  - "attention"
  - "traffic-forecasting"
  - "state-space-models"
architectures:
  []
datasets:
  - "pems04"
  - "pems08"
concept_slugs:
  - "temporal-spatial-temporal-architecture"
dataset_slugs:
  - "pems04"
  - "pems08"
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:54:50Z"
created_at: "2026-04-18T04:54:50Z"
---

# FAST: A Synergistic Framework of Attention and State-space Models for Spatiotemporal Traffic Prediction

**Authors**: Xinjin Li, Jinghan Cao, Mengyue Wang, Yue Wu, Longxiang Yan, Yeyang Zhou, Ziqi Sha, Yu Ma
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13453](https://arxiv.org/abs/2604.13453)

## Summary

FAST addresses the trade-off between Transformer expressiveness and state-space efficiency in traffic forecasting by employing a Temporal-Spatial-Temporal architecture. By leveraging temporal attention for pattern extraction and Mamba-based modules for linear-complexity spatial dependency modeling, the framework effectively handles large sensor networks. Evaluation on standard traffic benchmarks demonstrates that FAST provides consistent improvements in accuracy over diverse baseline architectures.

## Key Contributions

- Introduces FAST, a hybrid spatiotemporal framework that integrates temporal attention and Mamba-based spatial modeling to achieve linear complexity.
- Employs a learnable multi-source spatiotemporal embedding to effectively incorporate historical traffic flow, temporal context, and static node information.
- Achieves superior performance on PeMS04, PeMS07, and PeMS08 datasets, reducing RMSE by up to 4.3% and MAE by 2.8% compared to state-of-the-art baselines.

## Open Questions & Future Work

- [[multitask-urban-spatiotemporal-forecasting-challenges]]

## Key Concepts

- [[temporal-spatial-temporal-architecture]]: A hybrid neural architecture that interleaves temporal attention and selective state-space modeling to capture complex spatiotemporal dependencies with linear computational complexity.

## Archivist Review

The 'Temporal-Spatial-Temporal Architecture' was approved as it encapsulates a highly reusable hybrid approach to spatiotemporal modeling. Only two core datasets were kept to satisfy the strict limit on dataset additions. The open question was refined to better characterize the challenge of scaling to diverse urban tasks, avoiding generic terminology.

### Approved Concepts
- Temporal-Spatial-Temporal Architecture: This architecture provides a structured, reusable design pattern for balancing temporal expressiveness and spatial efficiency in spatiotemporal forecasting tasks.

### Approved Open Questions
- Multitask urban spatiotemporal forecasting: This addresses the transition from constrained benchmark performance to real-world, complex urban environment modeling.

### Rejected Candidates
- [open_question] Challenges in complex spatiotemporal forecasting (`challenges-in-complex-spatiotemporal-forecasting`) - duplicate_existing: The title was overly generic and the description duplicated themes already captured in existing vault entries.
- [dataset] PeMS07 (`pems07`) - low_impact: Limit of 2 datasets reached; prioritize more common benchmarks.

## Datasets

- [[pems04]]
- [[pems08]]

## Links

- [Abstract](https://arxiv.org/abs/2604.13453)
- [PDF](https://arxiv.org/pdf/2604.13453)

