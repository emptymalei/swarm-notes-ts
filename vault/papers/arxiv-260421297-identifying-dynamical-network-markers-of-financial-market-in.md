---
# CSL-compatible fields
title: "Identifying dynamical network markers of financial market instability"
author:
  - literal: "Mariko I. Ito"
  - literal: "Hiroyuki Hasada"
  - literal: "Yudai Honma"
  - literal: "Takaaki Ohnishi"
  - literal: "Tsutomu Watanabe"
  - literal: "Kazuyuki Aihara"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21297"

# Custom fields
paper_id: "2604.21297"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dynamical-network-marker-dnm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:09:24Z"
created_at: "2026-04-26T05:09:24Z"
---

# Identifying dynamical network markers of financial market instability

**Authors**: Mariko I. Ito, Hiroyuki Hasada, Yudai Honma, Takaaki Ohnishi, Tsutomu Watanabe, Kazuyuki Aihara
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21297](https://arxiv.org/abs/2604.21297)

## Summary

This study investigates early warning signals for financial market instability by applying Dynamical Network Marker (DNM) theory to high-dimensional order book data. By modeling market participants as interacting elements through virtual server IDs, the authors characterize precursors to structural market transitions known as critical slowing down. Results indicate that the proposed DNM-based framework can successfully detect signals of large price movements at a daily time scale, suggesting its viability for practical early-warning systems.

## Key Contributions

- Adapts the Dynamical Network Marker (DNM) theory to analyze high-dimensional financial order data from the Tokyo Stock Exchange.
- Demonstrates that early warning signals for large price movements can be detected on a daily time scale by identifying critical slowing down among market participants.
- Provides a framework for constructing multivariate time series from virtual server IDs to represent market participant interactions.

## Open Questions & Future Work

- [[dnm-financial-practical-robustness]]

## Key Concepts

- [[dynamical-network-marker-dnm]]: A mathematical framework identifying precursors to critical transitions in high-dimensional systems by detecting critical slowing down among interacting elements.

## Archivist Review

The Dynamical Network Marker (DNM) concept is approved as a reusable framework for regime-shift detection, already present in the vault but validated here as a robust research direction. The open question is focused on the core limitation of applying closed-system dynamics to open market environments, which is a significant bottleneck in this field. I have renamed the open question to be more concise and standard.

### Approved Concepts
- Dynamical Network Marker (DNM): The paper adapts DNM theory—originally developed for biological transitions—to financial markets to identify critical slowing down as a precursor to market instability.

### Approved Open Questions
- Robustness of DNM Financial Indicators: The current framework suffers from sensitivity to exogenous factors and requires better calibration for practical real-time application in dynamic, open financial markets.

### Rejected Candidates
- [open_question] Improving Robustness of DNM Indicators (`robust-dnm-financial-forecasting`) - duplicate_existing: This is a duplicate of the newly created canonical slug, which is more descriptive.

## Links

- [Abstract](https://arxiv.org/abs/2604.21297)
- [PDF](https://arxiv.org/pdf/2604.21297)

