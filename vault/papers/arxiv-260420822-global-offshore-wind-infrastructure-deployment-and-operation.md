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
  []
architectures:
  []
datasets:
  - "sentinel-1-offshore-wind-corpus"
concept_slugs:
  []
dataset_slugs:
  - "sentinel-1-offshore-wind-corpus"
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:05:22Z"
created_at: "2026-04-23T05:05:22Z"
---

# Global Offshore Wind Infrastructure: Deployment and Operational Dynamics from Dense Sentinel-1 Time Series

**Authors**: Thorsten Hoeser, Felix Bachofer, Claudia Kuenzer
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20822](https://arxiv.org/abs/2604.20822)

## Summary

This paper presents a large-scale Sentinel-1 synthetic aperture radar (SAR) time series corpus designed to monitor the construction and operational phases of offshore wind infrastructure globally. By analyzing over 15,000 infrastructure locations with dense temporal coverage from 2016 to 2025, the authors address the scarcity of high-resolution, semantically fine-grained data in current monitoring efforts. The work includes an expert-annotated benchmark dataset and baseline classifiers, providing a robust foundation for future research in time series classification for renewable energy infrastructure.

## Key Contributions

- Introduction of a global Sentinel-1 SAR time series corpus tracking offshore wind infrastructure deployment and operations from 2016 to 2025.
- Release of an expert-annotated benchmark dataset comprising 553 time series and over 328,000 event labels for classification tasks.
- Demonstration of high temporal coherence using a baseline classifier achieving 0.84 macro F1 score and 0.785 AUC on the developed dataset.

## Open Questions & Future Work

- [[early-detection-offshore-infrastructure]]
- [[learned-temporal-classification]]

## Archivist Review

I approved the dataset (renamed for consistency) and the two open questions, as they delineate clear research boundaries for the field of SAR-based infrastructure monitoring. I rejected the concept candidates as none were proposed by the user, and no sub-modules in the paper were deemed sufficiently novel or reusable for standalone conceptual status.

### Approved Open Questions
- Early-stage offshore infrastructure detection: Spatial detection serves as the fundamental prerequisite for time series analysis; without efficient early-stage detection, the ability to monitor the full lifecycle of offshore wind energy infrastructure in near-real-time is limited.
- Learned temporal infrastructure classification: Developing learned temporal models is essential for overcoming the limitations of heuristic, manual-threshold-based approaches, potentially leading to more accurate, automated, and globally scalable infrastructure monitoring.

### Rejected Candidates
- [dataset] Sentinel-1 time series data corpus (`sentinel-1-time-series-data-corpus`) - other: Renamed for clarity and uniqueness in the vault.

## Datasets

- [[sentinel-1-offshore-wind-corpus]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20822)
- [PDF](https://arxiv.org/pdf/2604.20822)

