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
  - "polymarket-lifecycle-dataset-suite"
concept_slugs:
  - "prediction-market-lifecycle-dataset-suite"
dataset_slugs:
  - "polymarket-lifecycle-dataset-suite"
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:57:01Z"
created_at: "2026-04-25T04:57:01Z"
---

# Unlocking the Forecasting Economy: A Suite of Datasets for the Full Lifecycle of Prediction Market: [Experiments & Analysis]

**Authors**: Huaiyu Jia, Luofeng Zhou, Wentao Zhang, Lin William Cong, Siguang Li, Shuo Sun
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20421](https://arxiv.org/abs/2604.20421)

## Summary

This paper introduces the first continuously maintained dataset suite for the full lifecycle of decentralized prediction markets, leveraging data from the Polymarket platform. The authors address data fragmentation by integrating heterogeneous on-chain and off-chain sources into a unified relational system featuring market metadata, trading records, and oracle resolution events. Spanning over five years of data, this suite enables comprehensive empirical research into market dynamics and collective belief formation in prediction markets.

## Key Contributions

- Presents a comprehensive dataset suite covering the full lifecycle of decentralized prediction markets from October 2020 to March 2026.
- Develops a unified relational data system that integrates heterogeneous on-chain and off-chain data through identifier resolution and incremental synchronization.
- Demonstrates dataset utility through NBA outcome calibration and CPI expectation reconstruction case studies.

## Open Questions & Future Work

- [[oracle-risk-trading-behavior]]

## Key Concepts

- [[prediction-market-lifecycle-dataset-suite]]: A comprehensive, continuously updated dataset covering the full lifecycle of decentralized prediction markets, including market creation, trading, and resolution.

## Archivist Review

The approval focused on the unique contribution of integrating disparate on-chain and off-chain data sources to create a unified lifecycle view of prediction markets. The identified open question regarding market behavior during oracle disputes was retained as it addresses a fundamental structural vulnerability in decentralized forecasting mechanisms. Other potential candidates were deemed either redundant or insufficiently distinct for permanent vault status.

### Approved Concepts
- Prediction Market Lifecycle Dataset Suite: This is the primary contribution, providing a unified, multi-source dataset for the entire lifecycle of decentralized prediction markets.

### Approved Open Questions
- Market behavior during oracle disputes: Understanding market behavior during oracle disputes is critical for designing more robust decentralized resolution mechanisms and assessing the resilience of prediction markets to oracle-level adversarial or technical risks.

## Datasets

- [[polymarket-lifecycle-dataset-suite]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20421)
- [PDF](https://arxiv.org/pdf/2604.20421)

