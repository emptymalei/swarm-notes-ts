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
processed_at: "2026-04-24T05:09:19Z"
created_at: "2026-04-24T05:09:19Z"
---

# Global Offshore Wind Infrastructure: Deployment and Operational Dynamics from Dense Sentinel-1 Time Series

**Authors**: Thorsten Hoeser, Felix Bachofer, Claudia Kuenzer
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20822](https://arxiv.org/abs/2604.20822)

## Summary

This paper introduces a comprehensive global corpus of Sentinel-1 synthetic aperture radar (SAR) time series designed to monitor the construction and operational lifecycles of offshore wind infrastructure. Covering the period from 2016 to 2025, the dataset includes over 14 million individual acquisition events across 15,606 infrastructure locations. The authors provide both raw, analysis-ready SAR backscatter profiles and a curated expert-annotated benchmark to facilitate the development and validation of temporal classification methods for maritime energy infrastructure.

## Key Contributions

- Introduces a global SAR time series corpus of offshore wind infrastructure comprising over 15.6k time series and 14.8M acquisition events spanning 2016-2025.
- Provides a high-quality expert-annotated benchmark dataset of 553 time series and 328k semantic event labels for evaluating construction and operational dynamics monitoring.
- Demonstrates effective baseline classification performance with a macro F1 score of 0.84 and AUC of 0.785 using a rule-based SAR backscatter profile classifier.

## Open Questions & Future Work

- [[early-stage-offshore-infrastructure-detection-bottleneck]]

## Archivist Review

I approved the main Sentinel-1 dataset as a critical, reusable asset for temporal maritime analysis. The open question was reformulated to better align with vault standards for research bottlenecks, specifically focusing on the intersection of spatial search and temporal anomaly detection in high-noise environments. I rejected no concepts as none met the strict criteria for universal reusability beyond the specific domain application.

### Approved Open Questions
- Early-stage offshore infrastructure detection: This is a substantial bottleneck for near-real-time monitoring of maritime industrial activity, as current reliance on post-hoc location validation prevents early-stage impact assessment and comprehensive deployment lifecycle tracking.

### Rejected Candidates
- [open_question] Early-onset offshore construction detection (`early-construction-detection-bottleneck-in-offshore-wind`) - duplicate_existing: Duplicate of the approved reformulated open question with a more concise and descriptive slug.

## Datasets

- [[sentinel-1-offshore-wind-corpus]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20822)
- [PDF](https://arxiv.org/pdf/2604.20822)

