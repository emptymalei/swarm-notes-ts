---
# CSL-compatible fields
title: "Unsupervised Anomaly Detection in Process-Complex Industrial Time Series: A Real-World Case Study"
author:
  - literal: "Sergej Krasnikov"
  - literal: "Lukas Meitz"
  - literal: "Samineh Bagheri"
  - literal: "Michael Heider"
  - literal: "Thorsten Schöler"
  - literal: "Jörg Hähner"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13928"

# Custom fields
paper_id: "2604.13928"
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
processed_at: "2026-04-16T05:05:50Z"
created_at: "2026-04-16T05:05:50Z"
---

# Unsupervised Anomaly Detection in Process-Complex Industrial Time Series: A Real-World Case Study

**Authors**: Sergej Krasnikov, Lukas Meitz, Samineh Bagheri, Michael Heider, Thorsten Schöler, Jörg Hähner
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13928](https://arxiv.org/abs/2604.13928)

## Summary

This study investigates the challenges of unsupervised anomaly detection in complex, multi-stage industrial environments where process-induced variability hampers traditional methods. By benchmarking various model classes, including Isolation Forest and multiple autoencoder variants, the paper demonstrates that standard techniques often fail to generalize to non-periodic, multi-scale industrial dynamics. The findings highlight the superior robustness of temporal convolutional autoencoders over recurrent and variational counterparts for real-world process monitoring.

## Key Contributions

- Provides a comprehensive empirical study on a unique industrial dataset featuring high process-induced variability from real machinery.
- Demonstrates that Isolation Forest baselines struggle with the multi-scale, non-periodic dynamics inherent in complex industrial processes.
- Establishes that temporal convolutional autoencoders offer superior robustness for anomaly detection compared to recurrent and variational architectures in these settings.

## Open Questions & Future Work

- [[architectural-suitability-constrained-environments]]

## Archivist Review

I have reviewed the paper, which provides an empirical assessment of various model classes for industrial anomaly detection. The analysis provided did not identify any reusable conceptual mechanisms that rise to the level of a standalone vault entry; therefore, I have rejected the potential concept regarding model comparison. I approved one open question that captures the broader, ongoing challenge of reconciling sophisticated time-series architectures with the practical constraints of industrial deployment.

### Approved Open Questions
- Architectural Suitability in Constrained Environments: Understanding how advanced architectures balance performance against the practical, resource-constrained realities of factory-floor deployment is essential for bridging the gap between academic progress and industrial practice.

### Rejected Candidates
- [concept] Temporal Convolutional Autoencoders Robustness (`temporal-convolutional-autoencoders-robustness`) - not_novel: This is a comparative performance finding rather than a foundational concept; standard architecture benchmarking is routine in empirical studies.

## Links

- [Abstract](https://arxiv.org/abs/2604.13928)
- [PDF](https://arxiv.org/pdf/2604.13928)

