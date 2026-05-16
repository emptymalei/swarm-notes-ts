---
# CSL-compatible fields
title: "WirelessSenseLLM: Zero-Shot Human Activity Understanding by Bridging Wireless Signals and Human Language"
author:
  - literal: "Mahmuda Keya"
  - literal: "Sneh Pillai"
  - literal: "Jiawei Yuan"
  - literal: "Kai Zeng"
  - literal: "Long Jiao"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.14070"

# Custom fields
paper_id: "2605.14070"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "zero-shot-learning"
  - "human-activity-recognition"
  - "multimodal-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "csi-to-language-adapter"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:13:56Z"
created_at: "2026-05-16T05:13:56Z"
---

# WirelessSenseLLM: Zero-Shot Human Activity Understanding by Bridging Wireless Signals and Human Language

**Authors**: Mahmuda Keya, Sneh Pillai, Jiawei Yuan, Kai Zeng, Long Jiao
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.14070](https://arxiv.org/abs/2605.14070)

## Summary

WirelessSenseLLM is a language-driven framework designed to interpret human motion from unsegmented Wi-Fi Channel State Information (CSI) in zero-shot settings. By utilizing a novel CSI-to-Language Adapter and a cross-modal projection mechanism, the model maps continuous sensor data into a language-aligned semantic space. This approach effectively resolves modality mismatches and handles overlapping human actions, allowing for natural language generation and reasoning without requiring segmented training data.

## Key Contributions

- Introduces WirelessSenseLLM, a framework enabling zero-shot human motion understanding from unsegmented Wi-Fi CSI signals without predefined labels.
- Proposes a CSI-to-Language Adapter that maps raw signal features into a language-aligned semantic space to bridge the sensing-language modality gap.
- Achieves 92% accuracy and 91% F1-score on zero-shot motion understanding, with a 12.33% improvement in multi-person motion explanation compared to existing baselines.

## Open Questions & Future Work

- [[multi-person-csi-interference-reasoning]]
- [[csi-cross-environment-generalization]]

## Key Concepts

- [[csi-to-language-adapter]]: A module that projects raw Wi-Fi Channel State Information into a language-aligned latent space for zero-shot reasoning.

## Archivist Review

I approved the CSI-to-Language Adapter as a reusable architectural pattern for bridging time-series sensing data and language models. The two open questions regarding multi-person scaling and environmental generalization identify critical, unresolved barriers for the practical deployment of wireless sensing technologies. I maintained a highly selective approach, rejecting generic or local implementation details that do not generalize.

### Approved Concepts
- CSI-to-Language Adapter: It is the core architectural innovation that addresses the fundamental modality mismatch between continuous time-series channel state information and discrete text embeddings.

### Approved Open Questions
- Scalable Multi-Person CSI Sensing: Scalability in multi-person environments is a critical bottleneck for deploying real-world wireless sensing systems, particularly those attempting to leverage LLMs for fine-grained semantic understanding.
- Environment-Agnostic Wireless Sensing: Generalization across hardware and environments is essential for moving wireless sensing from controlled laboratory experiments to universal, plug-and-play applications.

## Links

- [Abstract](https://arxiv.org/abs/2605.14070)
- [PDF](https://arxiv.org/pdf/2605.14070)

