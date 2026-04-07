---
# CSL-compatible fields
title: "A Family of Open Time-Series Foundation Models for the Radio Access Network"
author:
  - literal: "Ioannis Panitsas"
  - literal: "Leandros Tassiulas"
issued:
  date-parts:
    - [2026, 4, 5]
url: "https://arxiv.org/abs/2604.04271"

# Custom fields
paper_id: "2604.04271"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "timeran-datapile"
concept_slugs:
  []
dataset_slugs:
  - "timeran-datapile"
skill: "TimeSeriesSkill"
processed_at: "2026-04-07T04:53:55Z"
created_at: "2026-04-07T04:53:55Z"
---

# A Family of Open Time-Series Foundation Models for the Radio Access Network

**Authors**: Ioannis Panitsas, Leandros Tassiulas
**Date**: 2026-04-05
**Paper ID**: [arxiv:2604.04271](https://arxiv.org/abs/2604.04271)

## Summary

This paper introduces TimeRAN, a unified time-series foundation model designed to overcome the fragmentation of task-specific models in Radio Access Networks (RAN). By leveraging a lightweight architecture with task-specific heads, the framework enables efficient knowledge transfer across heterogeneous RAN analytics tasks, including forecasting and anomaly detection. To facilitate broad adoption and large-scale pretraining, the authors release the TimeRAN DataPile, the largest known time-series corpus for RAN telemetry. Empirical results on both synthetic and 5G testbed environments show that the model achieves state-of-the-art performance with limited fine-tuning.

## Key Contributions

- Introduces TimeRAN, a multi-task learning framework for time-series modeling in RAN infrastructures.
- Curates and releases TimeRAN DataPile, a large-scale corpus containing 355K time series and 0.56B measurements across diverse RAN telemetry sources.
- Demonstrates state-of-the-art performance in anomaly detection, classification, forecasting, and imputation with minimal task-specific fine-tuning.

## Open Questions & Future Work

- [[automated-anomaly-thresholding-ran]]

## Archivist Review

I approved the TimeRAN DataPile as a significant domain-specific dataset for RAN telemetry. I also approved the open question regarding automated anomaly thresholding, as it represents a persistent challenge for autonomous operational ML systems across multiple domains, not just radio networks. I rejected the 'TimeRAN' framework itself, as it is presented primarily as an application-specific architecture for RAN rather than a fundamental methodological advancement.

### Approved Open Questions
- Automated Anomaly Thresholding for RAN: Without robust, automated thresholding, the practical, autonomous application of foundation models for anomaly detection in production networks remains constrained by the need for expert-in-the-loop configuration.

### Rejected Candidates
- [concept] TimeRAN (`timeran`) - paper_local: TimeRAN is a specific architectural framework for a specific domain (RAN) rather than a reusable methodological concept or technique applicable across broader time-series contexts.

## Datasets

- [[timeran-datapile]]

## Links

- [Abstract](https://arxiv.org/abs/2604.04271)
- [PDF](https://arxiv.org/pdf/2604.04271)

