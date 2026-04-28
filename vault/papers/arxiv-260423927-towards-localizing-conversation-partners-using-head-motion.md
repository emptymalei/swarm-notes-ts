---
# CSL-compatible fields
title: "Towards Localizing Conversation Partners using Head Motion"
author:
  - literal: "Payal Mohapatra"
  - literal: "Calvin Murdock"
  - literal: "Ali Aroudi"
  - literal: "Ishwarya Ananthabhotla"
  - literal: "Anjali Menon"
  - literal: "Buye Xu"
  - literal: "Morteza Khaleghimeybodi"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.23927"

# Custom fields
paper_id: "2604.23927"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "head-orientation-based-acoustic-localization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:16:10Z"
created_at: "2026-04-28T05:16:10Z"
---

# Towards Localizing Conversation Partners using Head Motion

**Authors**: Payal Mohapatra, Calvin Murdock, Ali Aroudi, Ishwarya Ananthabhotla, Anjali Menon, Buye Xu, Morteza Khaleghimeybodi
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.23927](https://arxiv.org/abs/2604.23927)

## Summary

This paper presents a behavioral-cue-driven approach to enhancing speech intelligibility in noisy environments using wearable smartglasses. By leveraging IMU-based head-orientation data, the authors introduce HALo for acoustic zone localization and CoCo for partner counting. These models enable a personalized auditory enhancement system that outperforms conventional audio-only spatial methods in multi-party settings.

## Key Contributions

- Introduces HALo, a neural network for acoustic zone localization that improves performance by 21% over baseline methods.
- Develops CoCo, a partner-counting classification model that achieves 0.74 accuracy, outperforming rule-based systems by 35%.
- Demonstrates an end-to-end speech enhancement system integrating head-orientation tracking for improved listening in multi-speaker, noisy environments.

## Open Questions & Future Work

- [[dynamic-acoustic-localization-bottlenecks]]

## Key Concepts

- [[head-orientation-based-acoustic-localization]]: A framework for inferring a listener's acoustic zones of interest from IMU sensor data on smartglasses.

## Archivist Review

I have approved a consolidated concept for head-orientation-based acoustic localization and a broad open question regarding the challenges of real-time dynamic acoustic localization. The specific model names were rejected in favor of more descriptive, generalized concepts, and the partner-counting task was deemed a local implementation detail rather than a permanent knowledge artifact.

### Approved Concepts
- Head-Orientation-Based Acoustic Localization: It establishes the use of non-invasive behavioral cues (head orientation) as a primary modality for spatial filtering in assistive wearables, shifting focus from purely audio-based spatial techniques.

### Approved Open Questions
- Dynamic Acoustic Localization Bottlenecks: This is a fundamental bottleneck for deploying assistive hearing and AR systems in real-world, unconstrained social settings compared to the static environments used in current research.

### Rejected Candidates
- [concept] HALo (`halo-acoustic-localization`) - other: Renamed and abstracted to a more descriptive concept name for vault permanence.
- [concept] CoCo (`coco-partner-counting`) - subcomponent_of_broader_mechanism: This is a task-specific classification submodule that is not sufficiently distinct or reusable outside of this specific pipeline as a standalone concept.
- [open_question] Dynamic Acoustic Zone Localization (`dynamic-acoustic-zone-localization`) - other: Renamed to a more standard bottleneck naming convention for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.23927)
- [PDF](https://arxiv.org/pdf/2604.23927)

