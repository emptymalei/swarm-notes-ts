---
# CSL-compatible fields
title: "Foundation Models Defining A New Era In Sensor-based Human Activity Recognition: A Survey And Outlook"
author:
  - literal: "Sizhen Bian"
  - literal: "Mengxi Liu"
  - literal: "Siyu Yuan"
  - literal: "Lala Shakti Swarup Ray"
  - literal: "Bo Zhou"
  - literal: "Bin Guo"
  - literal: "Zhiwen Yu"
  - literal: "Thomas Ploetz"
  - literal: "Paul Lukowicz, Vitor Fortes Rey"
issued:
  date-parts:
    - [2026, 4, 3]
url: "https://arxiv.org/abs/2604.02711"

# Custom fields
paper_id: "2604.02711"
paper_source: "arxiv"
domain: "nlp"
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
processed_at: "2026-04-06T05:03:26Z"
created_at: "2026-04-06T05:03:26Z"
---

# Foundation Models Defining A New Era In Sensor-based Human Activity Recognition: A Survey And Outlook

**Authors**: Sizhen Bian, Mengxi Liu, Siyu Yuan, Lala Shakti Swarup Ray, Bo Zhou, Bin Guo, Zhiwen Yu, Thomas Ploetz, Paul Lukowicz, Vitor Fortes Rey
**Date**: 2026-04-03
**Paper ID**: [arxiv:2604.02711](https://arxiv.org/abs/2604.02711)

## Summary

This survey examines the paradigm shift toward using foundation models to overcome traditional limitations in sensor-based Human Activity Recognition (HAR), such as label scarcity and poor cross-context generalization. By synthesizing current research, the authors introduce a lifecycle-oriented taxonomy and analyze nine technical axes that define model architecture and deployment strategies. The paper categorizes the field into three primary trajectories—native HAR pretraining, adaptation of general models, and LLM integration—while identifying critical open challenges for the future of general-purpose, human-centered activity understanding.

## Key Contributions

- Provides a comprehensive survey and lifecycle-oriented taxonomy of foundation models applied to sensor-based human activity recognition (HAR).
- Identifies three primary development trajectories: HAR-specific foundation models, adaptation of general time-series models, and LLM-integrated reasoning systems.
- Analyzes design patterns across nine technical axes, including modality scope, tokenization, and adaptation mechanisms to address data scarcity and generalization hurdles.

## Open Questions & Future Work

- [[scaling-har-pretraining-fragmentation-privacy]]
- [[representation-limits-temporal-semantic-abstraction]]

## Archivist Review

I reviewed the survey's proposed research frontiers, selecting the two most substantial bottlenecks for sensor-based HAR foundation models: scaling under data fragmentation and the hierarchical representation challenge. I rejected broader taxonomic concepts as they describe the scope of the field rather than providing the specific, reusable mechanism required for a concept entry.

### Approved Open Questions
- Scaling HAR Pretraining Under Fragmentation: This is a fundamental bottleneck for HAR foundation models, as their ability to generalize across real-world deployments is strictly limited by the current data landscape. Addressing this is necessary for moving from small, task-specific models to true foundation models.
- Representation Limits: Temporal Hierarchy: Robust activity understanding requires the model to comprehend the temporal context of human behavior. Without effective hierarchical and semantic abstraction, models remain limited to short-window classification and cannot reason about intent or complex behavioral patterns.

### Rejected Candidates
- [concept] Sensor-based HAR Foundation Models (`sensor-based-har-foundation-models`) - generic: The concept is too broad and describes the domain of the survey rather than a specific, reusable methodological contribution.

## Links

- [Abstract](https://arxiv.org/abs/2604.02711)
- [PDF](https://arxiv.org/pdf/2604.02711)

