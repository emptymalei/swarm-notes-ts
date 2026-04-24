---
# CSL-compatible fields
title: "Unlocking the Forecasting Economy: A Suite of Datasets for the Full Lifecycle of Prediction Market: [Experiments & Analysis]"
author:
  - literal: "Huaiyu Jia"
  - literal: "Luofeng Zhou"
  - literal: "Wentao Zhang"
  - literal: "Lin William Cong"
  - literal: "Siguang Li"
  - literal: "Shuo Sun"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20421"

# Custom fields
paper_id: "2604.20421"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "polymarket-lifecycle-dataset-suite"
concept_slugs:
  - "prediction-market-lifecycle-dataset-suite"
dataset_slugs:
  - "polymarket-lifecycle-dataset-suite"
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:10:48Z"
created_at: "2026-04-24T05:10:48Z"
---

# Unlocking the Forecasting Economy: A Suite of Datasets for the Full Lifecycle of Prediction Market: [Experiments & Analysis]

**Authors**: Huaiyu Jia, Luofeng Zhou, Wentao Zhang, Lin William Cong, Siguang Li, Shuo Sun
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20421](https://arxiv.org/abs/2604.20421)

## Summary

This paper addresses the lack of integrated data for decentralized prediction markets by introducing a comprehensive dataset suite spanning market creation through settlement. The authors build a unified relational system to bridge fragmented off-chain and on-chain data, ensuring reproducibility and continuous updates for massive datasets. The contribution includes a rigorous data collection pipeline and demonstrations of its utility in complex downstream forecasting tasks.

## Key Contributions

- Introduces the first continuously updated, full-lifecycle dataset for decentralized prediction markets, comprising over 770k market records and 943M fill records from Polymarket.
- Develops a unified relational data system that integrates heterogeneous cross-source data (metadata, trading records, oracle events) through novel identifier resolution and on-chain recovery.
- Validates the dataset utility via descriptive market analysis and downstream forecasting tasks, including NBA outcome calibration and CPI expectation reconstruction.

## Open Questions & Future Work

- [[cross-platform-forecasting-integration-protocol-standardization]]

## Key Concepts

- [[prediction-market-lifecycle-dataset-suite]]: A unified, large-scale, and multi-layered dataset suite for the entire lifecycle of decentralized prediction markets.

## Archivist Review

The paper provides a foundational dataset for decentralized prediction markets, which is a valuable resource for time-series forecasting and collective intelligence research. I have approved the dataset and the core concept of a lifecycle-aware market dataset. The open question was reframed to emphasize the need for protocol standardization rather than just generic data integration.

### Approved Concepts
- prediction-market-lifecycle-dataset-suite: This is the first comprehensive, continuously updated, and multi-layered dataset for decentralized prediction markets, which are critical for collective belief forecasting.

### Approved Open Questions
- Cross-Platform Forecasting Integration: Generalizing across platforms is essential to decouple platform-specific artifacts from underlying forecasting signals and to evaluate market efficiency at scale.

## Datasets

- [[polymarket-lifecycle-dataset-suite]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20421)
- [PDF](https://arxiv.org/pdf/2604.20421)

