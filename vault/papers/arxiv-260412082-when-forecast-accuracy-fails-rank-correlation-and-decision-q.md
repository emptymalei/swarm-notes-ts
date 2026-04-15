---
# CSL-compatible fields
title: "When Forecast Accuracy Fails: Rank Correlation and Decision Quality in Multi-Market Battery Storage Optimization"
author:
  - literal: "Alessandro Falezza"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.12082"

# Custom fields
paper_id: "2604.12082"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "optimization"
  - "decision-making"
architectures:
  []
datasets:
  []
concept_slugs:
  - "tau-sufficiency"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-15T05:05:27Z"
created_at: "2026-04-15T05:05:27Z"
---

# When Forecast Accuracy Fails: Rank Correlation and Decision Quality in Multi-Market Battery Storage Optimization

**Authors**: Alessandro Falezza
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.12082](https://arxiv.org/abs/2604.12082)

## Summary

This paper investigates the relationship between electricity price forecast accuracy and revenue performance in multi-market battery energy storage optimization. Through a hierarchical trading framework applied to German and Swiss markets, the research reveals that standard metrics like MAE fail to account for the ordinal requirements of dispatch decisions. The author proposes 'tau-sufficiency' as a superior metric, showing that achieving a specific Kendall tau threshold is critical for capturing near-optimal revenue and remains robust across different market volatility regimes.

## Key Contributions

- Demonstrates that forecast rank correlation (Kendall tau) is a stronger predictor of intraday dispatch value than traditional metrics like MAE for battery storage systems.
- Establishes an empirical tau-sufficiency threshold (0.85-0.95) capable of capturing nearly 100% of perfect-foresight revenue in electricity market trading.
- Identifies that total revenue is primarily driven by capacity allocation across reserve markets rather than marginal improvements in forecast accuracy.

## Open Questions & Future Work

- [[tau-sufficiency-generalizability-thresholds]]

## Key Concepts

- [[tau-sufficiency]]: A decision-centric forecast evaluation criterion based on achieving a critical threshold of rank correlation (Kendall's tau) to ensure optimal action sequences.

## Archivist Review

The concept of tau-sufficiency is approved because it articulates a fundamental shift in forecast evaluation for decision-making tasks, which is highly reusable across time-series applications. The open question regarding the universality of this threshold is approved as it addresses a core bottleneck in transferring decision-centric metrics across diverse economic environments. Datasets were rejected as they represent public market data sources rather than benchmarked artifacts.

### Approved Concepts
- tau-sufficiency: Shifts focus from cardinal forecast error (like MAE) to ordinal rank preservation in decision-making contexts, providing a more direct metric for utility-based evaluation.

### Approved Open Questions
- Universality of tau-sufficiency thresholds: Standardizing forecast metrics around decision-utility rather than statistical error is a high-leverage move for energy market operations.

### Rejected Candidates
- [dataset] Regelleistung.net (`regelleistung.net`) - not_reusable: Routine source of market data rather than a curated research dataset or benchmark.
- [dataset] Swissgrid (`swissgrid`) - not_reusable: Routine source of grid data rather than a research-grade dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.12082)
- [PDF](https://arxiv.org/pdf/2604.12082)

