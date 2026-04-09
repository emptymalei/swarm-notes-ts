---
# CSL-compatible fields
title: "Decision-focused Conservation Voltage Reduction to Consider the Cascading Impact of Forecast Errors"
author:
  - literal: "Qintao Du"
  - literal: "Ran Li"
  - literal: "Weiyi Lv"
  - literal: "Huan Zhou"
  - literal: "Moduo Yu"
  - literal: "Jianzhe Liu"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07106"

# Custom fields
paper_id: "2604.07106"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "decision-focused-learning"
  - "optimization"
  - "volt-var-control"
  - "energy-systems"
architectures:
  []
datasets:
  []
concept_slugs:
  - "bi-level-multi-timescale-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:53:56Z"
created_at: "2026-04-09T04:53:56Z"
---

# Decision-focused Conservation Voltage Reduction to Consider the Cascading Impact of Forecast Errors

**Authors**: Qintao Du, Ran Li, Weiyi Lv, Huan Zhou, Moduo Yu, Jianzhe Liu
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07106](https://arxiv.org/abs/2604.07106)

## Summary

This paper addresses the limitation of traditional sequential Conservation Voltage Reduction (CVR) methods which fail to account for the cascading impact of forecast errors across hierarchical multi-stage Volt-Var Control. The authors propose a Bi-level Multi-timescale Forecasting (Bi-MTF) framework that embeds downstream optimization objectives directly into the upstream forecasting model training to minimize decision regret. To address the resulting computational complexity, a modified sensitivity-driven integer L-shaped method using hybrid gradient feedback is introduced. Numerical experiments show that this decision-focused approach significantly improves energy savings and safety compared to standard mean-squared error (MSE) based paradigms.

## Key Contributions

- Introduces a bi-level multi-timescale forecasting (Bi-MTF) framework that incorporates downstream Volt-Var Control (VVC) objectives into upstream forecast training.
- Develops a modified sensitivity-driven integer L-shaped method using hybrid gradient feedback to solve complex bi-level multi-stage optimization problems.
- Demonstrates superior performance on the IEEE 33-bus system, achieving 3.41% energy savings compared to 1.76% with conventional MSE-based paradigms.

## Key Concepts

- [[bi-level-multi-timescale-forecasting]]: A decision-focused forecasting framework that embeds multi-stage downstream optimization objectives into the upstream training process to mitigate the cascading impact of forecast errors.

## Archivist Review

The paper presents a clear contribution in the form of a decision-focused forecasting framework that integrates downstream optimization into the forecasting loss. I have approved the framework concept as it represents a generalizable approach for bridging the gap between predictive modeling and operational decision-making. Other candidates were rejected for being routine test systems rather than distinct datasets or because they were insufficiently unique for archival.

### Approved Concepts
- Bi-level Multi-timescale Forecasting: It shifts the forecasting paradigm from minimizing generic prediction error to minimizing decision-making regret in multi-stage power grid voltage control.

### Rejected Candidates
- [dataset] IEEE 33-bus system (`ieee-33-bus-system`) - not_novel: This is a standard synthetic power network model used for testing rather than a unique, archival-grade dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.07106)
- [PDF](https://arxiv.org/pdf/2604.07106)

