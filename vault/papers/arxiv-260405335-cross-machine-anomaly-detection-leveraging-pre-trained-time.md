---
# CSL-compatible fields
title: "Cross-Machine Anomaly Detection Leveraging Pre-trained Time-series Model"
author:
  - literal: "Yangmeng Li"
  - literal: "Kei Sano"
  - literal: "Toshihiro Kitao"
  - literal: "Ryoji Anzaki"
  - literal: "Yukiya Saitoh"
  - literal: "Hironori Moki"
  - literal: "Dragan Djurdjanovic"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.05335"

# Custom fields
paper_id: "2604.05335"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "anomaly-detection"
  - "industrial-iot"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "cross-machine-anomaly-detection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:56:29Z"
created_at: "2026-04-08T04:56:29Z"
---

# Cross-Machine Anomaly Detection Leveraging Pre-trained Time-series Model

**Authors**: Yangmeng Li, Kei Sano, Toshihiro Kitao, Ryoji Anzaki, Yukiya Saitoh, Hironori Moki, Dragan Djurdjanovic
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.05335](https://arxiv.org/abs/2604.05335)

## Summary

This paper introduces a cross-machine anomaly detection framework designed to overcome behavioral variations in nominally identical industrial machines. By leveraging the MOMENT foundation model, the approach utilizes a Random Forest-based feature disentanglement technique to isolate condition-related features from machine-specific noise. This extraction of domain-invariant representations enables significantly improved generalization for anomaly detection on unseen target machines compared to existing baseline methods.

## Key Contributions

- Proposes a framework that disentangles machine-specific and process-condition-specific features using pre-trained foundation models.
- Integrates Random Forest-based feature disentanglement with MOMENT embeddings to produce domain-invariant representations.
- Demonstrates superior cross-machine generalization in anomaly detection tasks compared to raw-signal and standard pre-trained embedding baselines on industrial datasets.

## Key Concepts

- [[cross-machine-anomaly-detection]]: A framework for anomaly detection that disentangles machine-specific noise from process-condition-specific features to enable generalization across nominally identical machines.

## Archivist Review

The paper proposes a specific approach to domain-invariant feature extraction for industrial time-series data. I approved 'Cross-Machine Anomaly Detection' as a central concept because it addresses the well-known and recurring challenge of distributional shifts between nominally identical physical assets. The implementation technique, Random Forest disentanglement, was rejected as it is a subcomponent of the broader mechanism and does not warrant a permanent entry on its own.

### Approved Concepts
- Cross-Machine Anomaly Detection: Addresses the critical industrial problem of domain shift between nominally identical machines, which is a central challenge in generalizing predictive models to new hardware.

### Rejected Candidates
- [concept] Random Forest Feature Disentanglement (`random-forest-feature-disentanglement`) - subcomponent_of_broader_mechanism: This is an implementation detail for isolating features, which is not sufficiently distinct or universally applicable compared to more generalized domain adaptation techniques.

## Links

- [Abstract](https://arxiv.org/abs/2604.05335)
- [PDF](https://arxiv.org/pdf/2604.05335)

