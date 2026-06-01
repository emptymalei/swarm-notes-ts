---
# CSL-compatible fields
title: "GETA: Generalized Encrypted Traffic Analysis"
author:
  - literal: "Ransika Gunasekara"
  - literal: "Rahat Masood"
  - literal: "Salil Kanhere"
issued:
  date-parts:
    - [2026, 5, 29]
url: "https://arxiv.org/abs/2605.31277"

# Custom fields
paper_id: "2605.31277"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "machine-learning"
  - "network-analysis"
  - "few-shot-learning"
  - "time-series-classification"
architectures:
  []
datasets:
  []
concept_slugs:
  - "geta-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-01T05:44:33Z"
created_at: "2026-06-01T05:44:33Z"
---

# GETA: Generalized Encrypted Traffic Analysis

**Authors**: Ransika Gunasekara, Rahat Masood, Salil Kanhere
**Date**: 2026-05-29
**Paper ID**: [arxiv:2605.31277](https://arxiv.org/abs/2605.31277)

## Summary

GETA is a protocol-agnostic framework for encrypted traffic analysis that addresses the limitations of payload-dependent Deep Packet Inspection in modern network environments. By modeling network flows as multivariate time series derived exclusively from traffic metadata, the framework operates effectively without accessing sensitive payload content. GETA leverages meta-learning and self-attention mechanisms to enable few-shot adaptation to new, heterogeneous network domains, demonstrating robust performance improvements across nine diverse traffic classification and detection benchmarks.

## Key Contributions

- Presents GETA, a protocol-agnostic framework that models encrypted flows as multivariate time series using only metadata to avoid dependency on payloads.
- Integrates meta-learning, embedding refinement, and self-attention to achieve few-shot adaptation for unseen network domains.
- Outperforms state-of-the-art baselines across nine distinct public datasets encompassing application identification, VPN traffic, IoT fingerprinting, and attack detection.

## Key Concepts

- [[geta-framework]]: A protocol-agnostic framework for traffic analysis that leverages meta-learning and multivariate time series representation to enable few-shot domain adaptation.

## Archivist Review

I have approved the GETA framework as a distinct approach to protocol-agnostic traffic analysis, as it frames the problem as a few-shot multivariate time series classification task. No other candidates were provided or met the threshold for standalone note-worthy status.

### Approved Concepts
- Generalized Encrypted Traffic Analysis (GETA): Establishes a methodology for classifying encrypted network traffic by treating metadata as multivariate time series, removing the need for payload inspection.

### Rejected Candidates
- [concept] Generalized Encrypted Traffic Analysis (GETA) (`geta-framework`) - other: The framework is approved, but the request asks for specific note-worthy concepts. It is included as an approved concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.31277)
- [PDF](https://arxiv.org/pdf/2605.31277)

