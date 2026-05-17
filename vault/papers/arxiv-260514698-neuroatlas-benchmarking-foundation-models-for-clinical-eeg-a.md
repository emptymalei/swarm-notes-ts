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
  []
architectures:
  []
datasets:
  - "neuroatlas"
concept_slugs:
  - "neuroatlas"
dataset_slugs:
  - "neuroatlas"
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:23:33Z"
created_at: "2026-05-17T05:23:33Z"
---

# NeuroAtlas: Benchmarking Foundation Models for Clinical EEG and Brain-Computer Interfaces

**Authors**: Konstantinos Kontras, Trui Osselaer, Stylianos G. Mouslech, Angeliki-Ilektra Karaiskou, Guido Gagliardi, Thomas Strypsteen, Mohammad Hossein Badiei, Anku Rani, Maarten Vanmarcke, Miguel Bhagubai, Chanakya Ekbote, Jaedong Hwang, Christos Chatzichristos, Paul Pu Liang, Maarten De Vos
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14698](https://arxiv.org/abs/2605.14698)

## Summary

NeuroAtlas is a large-scale benchmark designed to rigorously evaluate foundation models on 260k hours of clinical EEG and brain-computer interface data. The study reveals that domain-specific EEG foundation models offer minimal performance gains over generic time-series models, indicating that unified EEG modeling remains an open challenge. Furthermore, the authors establish the necessity of using domain-specific clinical metrics rather than standard ML loss metrics to accurately assess the real-world utility of EEG models.

## Key Contributions

- Introduces NeuroAtlas, a comprehensive benchmark featuring 42 clinical EEG datasets and 260k hours of data covering epilepsy, sleep, and brain-age estimation.
- Demonstrates that existing EEG-specific foundation models do not consistently outperform generic time-series models, challenging the assumption that domain-specific pretraining is currently superior.
- Highlights the insufficiency of standard ML metrics and proposes clinical-utility metrics such as event-level decision quality, hypnogram-derived features, and brain-age gap for rigorous EEG evaluation.

## Open Questions & Future Work

- [[clinical-utility-eeg-benchmarking]]

## Key Concepts

- [[neuroatlas]]: A large-scale benchmark comprising 42 datasets and 260k hours of EEG data for evaluating foundation models in clinical and brain-computer interface applications.

## Archivist Review

I approved the NeuroAtlas benchmark and the associated open question regarding the insufficiency of standard ML metrics for clinical utility. These items directly address the need for standardized evaluation practices in clinical AI and are highly reusable. I rejected no candidates as all submitted items were high-quality and unique.

### Approved Concepts
- NeuroAtlas: Provides the largest standardized evaluation suite for EEG foundation models, enabling cross-dataset benchmarking.

### Approved Open Questions
- Benchmarking Clinical EEG Utility: Distinguishing between technical performance and clinical utility is a major bottleneck in adopting foundation models for neurology.

## Datasets

- [[neuroatlas]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14698)
- [PDF](https://arxiv.org/pdf/2605.14698)

