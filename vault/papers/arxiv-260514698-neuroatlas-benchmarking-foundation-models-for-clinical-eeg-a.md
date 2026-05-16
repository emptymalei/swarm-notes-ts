---
# CSL-compatible fields
title: "NeuroAtlas: Benchmarking Foundation Models for Clinical EEG and Brain-Computer Interfaces"
author:
  - literal: "Konstantinos Kontras"
  - literal: "Trui Osselaer"
  - literal: "Stylianos G. Mouslech"
  - literal: "Angeliki-Ilektra Karaiskou"
  - literal: "Guido Gagliardi"
  - literal: "Thomas Strypsteen"
  - literal: "Mohammad Hossein Badiei"
  - literal: "Anku Rani"
  - literal: "Maarten Vanmarcke"
  - literal: "Miguel Bhagubai"
  - literal: "Chanakya Ekbote"
  - literal: "Jaedong Hwang"
  - literal: "Christos Chatzichristos"
  - literal: "Paul Pu Liang"
  - literal: "Maarten De Vos"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14698"

# Custom fields
paper_id: "2605.14698"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "neuroatlas"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:11:54Z"
created_at: "2026-05-16T05:11:54Z"
---

# NeuroAtlas: Benchmarking Foundation Models for Clinical EEG and Brain-Computer Interfaces

**Authors**: Konstantinos Kontras, Trui Osselaer, Stylianos G. Mouslech, Angeliki-Ilektra Karaiskou, Guido Gagliardi, Thomas Strypsteen, Mohammad Hossein Badiei, Anku Rani, Maarten Vanmarcke, Miguel Bhagubai, Chanakya Ekbote, Jaedong Hwang, Christos Chatzichristos, Paul Pu Liang, Maarten De Vos
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14698](https://arxiv.org/abs/2605.14698)

## Summary

NeuroAtlas is a comprehensive benchmark for evaluating foundation models in clinical EEG and brain-computer interfaces, aggregating 42 datasets to assess model performance across diverse tasks. The paper reveals that current EEG-specialized models lack consistent advantages over generic time-series models and emphasizes that standard machine learning metrics fail to capture clinical utility. By proposing task-specific clinical evaluation metrics, the authors expose significant gaps in the current state of unified EEG foundation models.

## Key Contributions

- Introduces NeuroAtlas, a large-scale benchmark for EEG foundation models containing 42 datasets and 260k hours of data.
- Demonstrates that specialized EEG foundation models do not consistently outperform generic time-series foundation models.
- Establishes that traditional machine learning metrics are inadequate for clinical EEG and proposes domain-specific metrics for epilepsy, sleep medicine, and brain age estimation.

## Open Questions & Future Work

- [[clinically-relevant-eeg-metrics]]
- [[eeg-fm-vs-ts-fm-utility]]

## Key Concepts

- [[neuroatlas]]: A comprehensive large-scale benchmark for EEG foundation models aggregating multiple clinical datasets and task-specific clinical evaluation metrics.

## Archivist Review

Approved the NeuroAtlas benchmark and two related open questions that directly address the core methodological critiques of the paper regarding clinical utility and the necessity of domain-specific architectures. I applied a restrictive filter, focusing only on the high-level benchmark contribution and the two fundamental research questions identified in the abstract and findings. No specific datasets were approved as 'NeuroAtlas' functions as the aggregate benchmark itself.

### Approved Concepts
- NeuroAtlas: It establishes a standardized large-scale evaluation suite for EEG foundation models, addressing the lack of clinical-relevance in existing metrics.

### Approved Open Questions
- Clinically Relevant EEG Benchmarking: This question is crucial for bridging the gap between algorithmic performance in benchmarks and actual effectiveness in clinical settings.
- Necessity of Specialized EEG Architectures: This addresses a fundamental efficiency and design question: whether the field should invest in domain-specific EEG models or focus on improving general-purpose temporal models.

## Links

- [Abstract](https://arxiv.org/abs/2605.14698)
- [PDF](https://arxiv.org/pdf/2605.14698)

