---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Graph-Enhanced Disease Trajectory Discovery and Temporal Endpoint Forecasting from Longitudinal Electronic Health Records"
description: "This paper introduces a graph-enhanced framework for disease trajectory discovery and endpoint forecasting using longitudinal Electronic Health Records (EHR). By employing a 'leakage-controlled' discovery process, the authors construct transition graphs and extract 'branching motifs' solely from training data, which are then integrated into a time-aware Transformer via cross-attention. Evaluation on MIMIC-IV v3.1 shows that while the approach significantly improves Mean Absolute Error (MAE) for long-term event timing (events > 730 days), it offers limited gains in short-term forecasting or overall survival discrimination. These findings suggest that graph-based motifs act primarily as long-range temporal anchors rather than universal enhancers for endpoint classification."
resource: "https://arxiv.org/abs/2610.20502"
tags:
  - "ehr-analysis"
  - "longitudinal-data"
  - "time-series-forecasting"
  - "graph-neural-networks"
  - "transformer"
  - "healthcare-ai"
  - "medical-ai"
  - "long-term-forecasting"
  - "attention-mechanism"
timestamp: "2026-10-18T00:32:37Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jin-Jia Zheng"
  - literal: "Vincent S. Tseng"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20502"
paper_source: "arxiv"
architectures:
  - "graph-neural-networks"
  - "transformer"
concepts:
  - name: "branching-motifs"
    description: "Subgraph-based structural patterns used as trajectory context to represent and retrieve potential disease progression paths in longitudinal records."
datasets:
  []
open_questions:
  - name: "short-vs-long-term-trajectory-tradeoff"
    description: "How can structural trajectory context be refined to improve long-term timing accuracy without introducing noise that degrades short-term forecasting performance?"
  - name: "survival-metric-discrepancy-in-graph-models"
    description: "Why does the addition of structured trajectory context improve specific time-to-event timing metrics while failing to improve standard survival analysis measures like the C-index?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:32:37Z"
created_at: "2026-10-18T00:32:37Z"
---

# Graph-Enhanced Disease Trajectory Discovery and Temporal Endpoint Forecasting from Longitudinal Electronic Health Records

**Authors**: Jin-Jia Zheng, Vincent S. Tseng
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20502](https://arxiv.org/abs/2610.20502)

## Summary

This paper introduces a graph-enhanced framework for disease trajectory discovery and endpoint forecasting using longitudinal Electronic Health Records (EHR). By employing a 'leakage-controlled' discovery process, the authors construct transition graphs and extract 'branching motifs' solely from training data, which are then integrated into a time-aware Transformer via cross-attention. Evaluation on MIMIC-IV v3.1 shows that while the approach significantly improves Mean Absolute Error (MAE) for long-term event timing (events > 730 days), it offers limited gains in short-term forecasting or overall survival discrimination. These findings suggest that graph-based motifs act primarily as long-range temporal anchors rather than universal enhancers for endpoint classification.

## Key Contributions

- Developed a graph-enhanced Transformer framework that utilizes branching motifs from patient transition graphs to provide structured context for disease trajectory forecasting.
- Implemented a leakage-controlled discovery protocol for EHR graph construction, ensuring that transitions and motifs are learned exclusively from training sets to prevent data contamination.
- Demonstrated a 19.2-day reduction in overall event-time Mean Absolute Error (MAE) on MIMIC-IV v3.1, with specific improvements of 58.9 days for long-range events (occurring after 730 days).
- Identified a performance trade-off where branching-motif context improves long-term timing prediction but provides limited benefit for short-term forecasting or standard survival metrics like C-index.

## Limitations

The framework showed degraded performance for short-term events (within 730 days) and failed to outperform history-only discrete-hazard models in macro C-index or integrated Brier scores.

## Open Questions & Future Work

- [[short-vs-long-term-trajectory-tradeoff]]
- [[survival-metric-discrepancy-in-graph-models]]

## Key Concepts

- [[branching-motifs]]: Subgraph-based structural patterns used as trajectory context to represent and retrieve potential disease progression paths in longitudinal records.

## Archivist Review

Approved 'Branching Motifs' as a core conceptual contribution to structural trajectory modeling. Two open questions were approved as they highlight significant unresolved trade-offs in horizon-dependent performance and the gap between timing accuracy and survival discrimination metrics. The dataset and leakage-control methodology were rejected as they represent routine benchmarks and standard experimental best practices, respectively.

### Approved Concepts
- Branching Motifs: Provides a structured, graph-theoretic way to represent and retrieve potential disease progression pathways, moving beyond simple history-based sequence modeling.

### Approved Open Questions
- Horizon Sensitivity in Trajectory Context: Clinical applications require high reliability across both immediate and distant horizons; a model that sacrifices near-term accuracy may be less useful in acute care settings.
- Survival Metric vs. Timing Accuracy Gap: Standard survival metrics are the gold standard for clinical validation; understanding why structural enhancements fail these metrics is key to developing clinically superior models.

### Rejected Candidates
- [concept] Leakage-Controlled Discovery (`leakage-controlled-discovery`) - generic: This describes a standard best practice for experimental design (inductive splitting in graph-based models) rather than a novel conceptual or architectural contribution.
- [dataset] MIMIC-IV v3.1 (`MIMIC-IV v3.1`) - generic: MIMIC-IV is a standard, routine benchmark dataset in the EHR domain and does not require a unique vault entry for this specific version's use here.
- [concept] Time-Aware Transformer (`time-aware-transformer`) - not_novel: Time-aware Transformers are a well-established architectural variant in time-series and EHR literature.

## Links

- [Abstract](https://arxiv.org/abs/2610.20502)
- [PDF](https://arxiv.org/pdf/2610.20502)

