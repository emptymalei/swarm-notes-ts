---
# CSL-compatible fields
title: "Network Structure in UK Payment Flows: Evidence on Economic Interdependencies and Implications for Real-Time Measurement"
author:
  - literal: "Aditya Humnabadkar"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02068"

# Custom fields
paper_id: "2604.02068"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:19:28Z"
created_at: "2026-04-03T05:19:28Z"
---

# Network Structure in UK Payment Flows: Evidence on Economic Interdependencies and Implications for Real-Time Measurement

**Authors**: Aditya Humnabadkar
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02068](https://arxiv.org/abs/2604.02068)

## Summary

This paper investigates the structural properties of UK inter-industry payment flows using a dataset of 532,346 records spanning 2017 to 2024. By augmenting traditional time-series forecasting with graph-theoretic network features such as centrality and clustering coefficients, the author achieves significant accuracy improvements over standard approaches. The study highlights the heightened utility of these network indicators during economic volatility, offering a reliable methodology for nowcasting and monitoring structural economic shifts.

## Key Contributions

- Introduces a graph-theoretic framework for analyzing inter-industry payment flows that reveals structural interdependencies invisible to bilateral measurement.
- Demonstrates that integrating network features (centrality, clustering) improves payment flow forecasting accuracy by 8.8 percentage points.
- Shows that network-enhanced models provide superior robustness during economic disruptions, specifically mitigating performance collapses seen in traditional models during the COVID-19 pandemic.

## Open Questions & Future Work

- [[mechanisms-of-economic-network-shocks]]

## Archivist Review

I have approved the open question regarding the mechanisms of economic network shocks, as it addresses a fundamental limitation in using correlative network indicators for predictive economic monitoring. The proposed concept of 'graph-theoretic economic forecasting' was rejected as it describes a general application area rather than a novel or distinct machine learning methodology suitable for the vault. No new datasets were identified that meet the criteria for a standalone entry.

### Approved Open Questions
- Mechanisms of economic network shocks: Understanding the causal link between structural network evolution and macroeconomic outcomes is critical for developing robust early-warning systems for policymakers. Without this, network-based indicators remain purely correlative and potentially unstable during novel types of economic crises.

### Rejected Candidates
- [concept] Graph-theoretic economic forecasting (`graph-theoretic-economic-forecasting`) - generic: The proposed concept is a generic application of network analysis to time-series and lacks the structural novelty to be a standalone vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.02068)
- [PDF](https://arxiv.org/pdf/2604.02068)

