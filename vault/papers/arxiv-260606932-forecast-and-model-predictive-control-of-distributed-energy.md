---
# CSL-compatible fields
title: "Forecast and Model Predictive Control of Distributed Energy Resource Aggregators for Net-Demand Balancing"
author:
  - literal: "Obai Bahwal"
  - literal: "Oliver Kosut"
  - literal: "LalithaSankar"
issued:
  date-parts:
    - [2026, 6, 5]
url: "https://arxiv.org/abs/2606.06932"

# Custom fields
paper_id: "2606.06932"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "control-systems"
  - "energy-systems"
architectures:
  []
datasets:
  []
concept_slugs:
  - "virtual-battery-dera-modeling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-08T05:48:38Z"
created_at: "2026-06-08T05:48:38Z"
---

# Forecast and Model Predictive Control of Distributed Energy Resource Aggregators for Net-Demand Balancing

**Authors**: Obai Bahwal, Oliver Kosut, LalithaSankar
**Date**: 2026-06-05
**Paper ID**: [arxiv:2606.06932](https://arxiv.org/abs/2606.06932)

## Summary

This paper introduces a framework for controlling Distributed Energy Resource Aggregators (DERAs) by modeling them as virtual batteries with capacity constraints. The methodology integrates net-demand forecasting with a rolling-horizon model predictive control (MPC) to optimize dispatch and tracking of net-load patterns. Evaluations using high-resolution CAISO data compare the efficacy of linear regression versus LSTM forecasting, highlighting how the choice of predictive model and update frequency impacts system performance.

## Key Contributions

- Proposed a joint forecasting and model predictive control (MPC) framework for managing Distributed Energy Resource Aggregators (DERAs) as virtual batteries.
- Formulated a rolling-horizon MPC task to minimize net-load tracking errors, output ramping, and deviations from desired state-of-charge.
- Benchmarked LSTM against linear regression models on CAISO net-demand data, revealing performance tradeoffs between forecasting horizons and MPC update rates.

## Key Concepts

- [[virtual-battery-dera-modeling]]: An abstraction of distributed energy resource aggregators as flexible virtual batteries with operational capacity and state-of-charge constraints.

## Archivist Review

The concept of modeling energy aggregators as virtual batteries is a distinct, domain-specific abstraction that facilitates the integration of forecasting and control, making it worthy of a permanent vault entry. I rejected the CAISO data as a dataset candidate because it is a general public utility dataset used for routine benchmarking, which fails the requirement for unique or highly specialized critical importance to the field. No open questions were approved as the paper describes a specific application trade-off rather than a fundamental unresolved research bottleneck.

### Approved Concepts
- Virtual Battery DERA Modeling: Provides a robust framework for abstracting complex decentralized energy sources into a unified control entity for grid balancing.

## Links

- [Abstract](https://arxiv.org/abs/2606.06932)
- [PDF](https://arxiv.org/pdf/2606.06932)

