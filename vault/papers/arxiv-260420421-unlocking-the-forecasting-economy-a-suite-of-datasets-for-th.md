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
  - "time-series"
architectures:
  []
datasets:
  - "Polymarket-Lifecycle-Dataset"
concept_slugs:
  - "prediction-market-lifecycle-dataset-suite"
dataset_slugs:
  - "polymarket-lifecycle-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:06:54Z"
created_at: "2026-04-23T05:06:54Z"
---

# Unlocking the Forecasting Economy: A Suite of Datasets for the Full Lifecycle of Prediction Market: [Experiments & Analysis]

**Authors**: Huaiyu Jia, Luofeng Zhou, Wentao Zhang, Lin William Cong, Siguang Li, Shuo Sun
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20421](https://arxiv.org/abs/2604.20421)

## Summary

This paper addresses the data fragmentation challenge in decentralized prediction markets by introducing a comprehensive dataset suite built on Polymarket. The authors construct a unified relational system that integrates disparate on-chain and off-chain data sources—including market metadata, high-frequency trading records, and oracle events—across a five-year period. By implementing rigorous identifier resolution and consistency mechanisms, the work enables reproducible research into the full lifecycle of prediction market activity. The utility of this dataset is demonstrated through predictive calibration studies and macroeconomic expectation reconstruction.

## Key Contributions

- Developed the first unified, continuously updated relational dataset for decentralized prediction markets, covering market creation, trading, and oracle settlement.
- Engineered a scalable cross-source integration pipeline capable of handling large-scale on-chain recovery and incremental updates.
- Validated the dataset's utility through comprehensive descriptive analysis and application to NBA outcome calibration and CPI expectation reconstruction.

## Open Questions & Future Work

- [[continuous-cpi-forecast-reconstruction]]

## Key Concepts

- [[prediction-market-lifecycle-dataset-suite]]: A unified, multi-layer longitudinal dataset covering the entire lifecycle of decentralized prediction markets from creation to settlement.

## Archivist Review

I approved the dataset suite and the dataset as they represent a significant, non-trivial contribution to the collection of decentralized market data. I also approved the open question regarding continuous forecast reconstruction, as it addresses the fundamental challenge of mapping discrete probability distributions to continuous numerical predictions in financial markets. Other candidates were not deemed necessary for the permanent vault.

### Approved Concepts
- Prediction Market Lifecycle Dataset Suite: It provides a standardized, unified relational data structure for the fragmented, multi-layer life cycle of decentralized prediction markets, enabling large-scale analysis.

### Approved Open Questions
- Continuous CPI Forecast Reconstruction: This is technically critical because the choice of distribution (e.g., Gaussian) directly influences the resulting point forecast, potentially introducing bias if the actual market-implied belief is skewed, multi-modal, or has fat tails, which is common in macroeconomic expectations.

## Datasets

- [[polymarket-lifecycle-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20421)
- [PDF](https://arxiv.org/pdf/2604.20421)

