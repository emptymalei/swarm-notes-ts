---
# CSL-compatible fields
title: "Federated Learning for Early Prediction of EV Charging Demand"
author:
  - literal: "Vasilis Perifanis"
  - literal: "Foteini Nikolaidou"
  - literal: "Nikolaos Pavlidis"
  - literal: "Panagiotis Thomakos"
  - literal: "Andreas Sendros"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04993"

# Custom fields
paper_id: "2605.04993"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "federated-learning"
  - "forecasting"
  - "smart-grid"
architectures:
  []
datasets:
  - "Adaptive Charging Network (ACN)"
concept_slugs:
  - "participant-failure-impact-analysis-fl"
dataset_slugs:
  - "adaptive-charging-network-acn"
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:14:04Z"
created_at: "2026-05-07T05:14:04Z"
---

# Federated Learning for Early Prediction of EV Charging Demand

**Authors**: Vasilis Perifanis, Foteini Nikolaidou, Nikolaos Pavlidis, Panagiotis Thomakos, Andreas Sendros
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04993](https://arxiv.org/abs/2605.04993)

## Summary

This paper addresses the challenge of early electric vehicle (EV) charging demand forecasting by utilizing only session plug-in data and initial charging measurements. The authors construct a dataset from the Adaptive Charging Network (ACN) and evaluate several model families within a federated learning framework. The approach effectively models intra-depot station heterogeneity to provide reliable, privacy-aware demand estimates suitable for real-time grid optimization.

## Key Contributions

- Demonstrates that accurate EV charging demand forecasts can be generated early in a session using only plug-in and initial charging data.
- Validates that federated learning models achieve predictive performance comparable to centralized models while ensuring data privacy within individual charging depots.
- Develops a methodology for managing intra-depot heterogeneity by partitioning charging stations as distinct clients in a federated setting.

## Open Questions & Future Work

- [[scaling-fl-to-cross-depot-ev-networks]]

## Key Concepts

- [[participant-failure-impact-analysis-fl]]: A methodology for modeling heterogeneity in federated charging infrastructure by treating individual charging stations as distinct client partitions.

## Archivist Review

I have approved the core concept of station-level client partitioning in federated learning and the open question regarding the scalability of such models to cross-depot networks, as these address significant, recurring challenges in decentralized forecasting. I also approved the Adaptive Charging Network (ACN) dataset as it serves as a central, specific domain-benchmarking resource for this work. Other candidates were deemed either paper-specific implementation details or too generic for standalone vault inclusion.

### Approved Concepts
- Participant Failure Impact Analysis (FL): The paper explicitly models station-level heterogeneity as client partitions within a Federated Learning framework, which is a critical aspect of real-world FL for distributed infrastructure.

### Approved Open Questions
- Cross-depot federated learning scalability: Scaling federated learning from single sites to wider, multi-depot networks is essential for building real-world, industry-scale predictive systems that remain privacy-compliant.

## Datasets

- [[adaptive-charging-network-acn]]

## Links

- [Abstract](https://arxiv.org/abs/2605.04993)
- [PDF](https://arxiv.org/pdf/2605.04993)

