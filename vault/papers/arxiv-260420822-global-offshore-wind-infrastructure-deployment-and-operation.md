---
# CSL-compatible fields
title: "Global Offshore Wind Infrastructure: Deployment and Operational Dynamics from Dense Sentinel-1 Time Series"
author:
  - literal: "Thorsten Hoeser"
  - literal: "Felix Bachofer"
  - literal: "Claudia Kuenzer"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20822"

# Custom fields
paper_id: "2604.20822"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "remote-sensing"
  - "time-series-classification"
  - "infrastructure-monitoring"
  - "sar-data-analysis"
architectures:
  []
datasets:
  - "sentinel-1-offshore-wind-time-series-corpus"
concept_slugs:
  - "offshore-wind-sar-corpus"
dataset_slugs:
  - "sentinel-1-offshore-wind-time-series-corpus"
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:55:45Z"
created_at: "2026-04-25T04:55:45Z"
---

# Global Offshore Wind Infrastructure: Deployment and Operational Dynamics from Dense Sentinel-1 Time Series

**Authors**: Thorsten Hoeser, Felix Bachofer, Claudia Kuenzer
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20822](https://arxiv.org/abs/2604.20822)

## Summary

This paper presents a global Sentinel-1 synthetic aperture radar (SAR) time series corpus designed to monitor the construction and operational dynamics of offshore wind infrastructure. By processing over 14 million backscatter profiles from 2016 to 2025, the authors provide a standardized, analysis-ready dataset for tracking wind farm lifecycle stages. The work includes an expert-annotated benchmark for method evaluation and establishes performance baselines using a rule-based classifier, facilitating future research in remote sensing-based infrastructure monitoring.

## Key Contributions

- Released a global Sentinel-1 SAR time series corpus containing 15,606 infrastructure locations and over 14.8 million event-level 1D backscatter profiles.
- Provided an expert-annotated benchmark dataset of 553 time series with 328,657 event labels to support methodological development.
- Established an event-wise baseline classifier achieving a macro F1 score of 0.84 and an AUC of 0.785 for temporal coherence evaluation.

## Open Questions & Future Work

- [[early-construction-detection-bottleneck]]

## Key Concepts

- [[offshore-wind-sar-corpus]]: A global-scale, event-annotated SAR time series corpus of offshore wind infrastructure covering construction and operational phases.

## Archivist Review

I approved the corpus as a core concept and its corresponding dataset. I also approved the open question regarding early-onset detection as it identifies a substantive limitation in current infrastructure monitoring workflows. The question on 1D classification limits was rejected as it describes a standard trade-off inherent in remote sensing dimensionality reduction.

### Approved Concepts
- Offshore Wind Infrastructure SAR Time Series Corpus: Provides the first global-scale, high-temporal-resolution SAR dataset specifically annotated for offshore wind farm life-cycle stages.

### Approved Open Questions
- Early-Onset Construction Detection: This is a fundamental bottleneck for near-real-time monitoring, as current workflows depend on pre-existing knowledge of wind farm locations or rely on quarterly aggregations that suppress early transient signals.

### Rejected Candidates
- [open_question] Limitations of 1D SAR Profile Classification (`sar-profile-classification-limits`) - not_novel: The trade-off between dimensionality and classification accuracy is a standard observation in remote sensing rather than a unique open research problem.

## Datasets

- [[sentinel-1-offshore-wind-time-series-corpus]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20822)
- [PDF](https://arxiv.org/pdf/2604.20822)

