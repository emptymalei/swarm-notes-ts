---
# CSL-compatible fields
title: "CANDI: Curated Test-Time Adaptation for Multivariate Time-Series Anomaly Detection Under Distribution Shift"
author:
  - literal: "HyunGi Kim"
  - literal: "Jisoo Mok"
  - literal: "Hyungyu Lee"
  - literal: "Juhyeon Shin"
  - literal: "Sungroh Yoon"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.01845"

# Custom fields
paper_id: "2604.01845"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "false-positive-mining-fpm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:19:40Z"
created_at: "2026-04-03T05:19:40Z"
---

# CANDI: Curated Test-Time Adaptation for Multivariate Time-Series Anomaly Detection Under Distribution Shift

**Authors**: HyunGi Kim, Jisoo Mok, Hyungyu Lee, Juhyeon Shin, Sungroh Yoon
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.01845](https://arxiv.org/abs/2604.01845)

## Summary

CANDI is a novel test-time adaptation framework designed to mitigate performance degradation of multivariate time-series anomaly detectors under distribution shift. The method employs a False Positive Mining (FPM) strategy to selectively curate informative samples from unlabeled test streams and uses a Spatiotemporally-Aware Normality Adaptation (SANA) module to update model parameters. Experimental results show that CANDI significantly outperforms existing adaptation approaches by effectively preserving pre-trained knowledge while successfully adapting to shifted data distributions.

## Key Contributions

- Introduces CANDI, a test-time adaptation framework that enhances MTSAD robustness to distribution shifts by selectively mining and adapting to samples.
- Develops the False Positive Mining (FPM) strategy, which filters unlabeled test data to focus adaptation on false positives while protecting pre-trained knowledge.
- Proposes the SANA module for structured adaptation, demonstrating up to 14% improvement in AUROC across multivariate time-series benchmarks.

## Open Questions & Future Work

- [[contaminated-training-data-mtsad]]
- [[dynamic-threshold-adaptation-mtsad]]

## Key Concepts

- [[false-positive-mining-fpm]]: A strategy that selectively curates adaptation samples from unlabeled test data based on anomaly scores and latent feature similarity to refine models under distribution shift.

## Archivist Review

The approved concepts and questions focus on the core challenges of test-time adaptation in anomaly detection: managing sample selection to preserve knowledge and addressing the shift in detection thresholds. I rejected the 'SANA' module as it is a system-specific architectural detail rather than a distinct, reusable methodology. The open questions were selected for their foundational relevance to real-world deployment limitations.

### Approved Concepts
- False Positive Mining (FPM): Selective sample curation is a crucial mechanism in test-time adaptation for time-series to avoid the catastrophic forgetting of pre-trained normality features.

### Approved Open Questions
- Contaminated Training Data in MTSAD: This is a fundamental limitation for applying unsupervised methods to real-world industrial or medical time-series data, where labels are often scarce and data quality is inconsistent.
- Dynamic Threshold Adaptation in MTSAD: Thresholding is the final step in anomaly detection, and static thresholds become unreliable under non-stationary conditions, making dynamic adaptation a potential key to better performance.

### Rejected Candidates
- [concept] Spatiotemporally-Aware Normality Adaptation (SANA) (`spatiotemporally-aware-normality-adaptation-sana`) - subcomponent_of_broader_mechanism: This module is presented as a specific architectural implementation of a broader adaptation objective and does not represent a sufficiently distinct or portable mechanism beyond the specific system in the paper.

## Links

- [Abstract](https://arxiv.org/abs/2604.01845)
- [PDF](https://arxiv.org/pdf/2604.01845)

