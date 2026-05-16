---
# CSL-compatible fields
title: "Fusion-fission forecasts when AI will shift to undesirable behavior"
author:
  - literal: "Neil F. Johnson"
  - literal: "Frank Yingjie Huo"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14218"

# Custom fields
paper_id: "2605.14218"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "stanford-delusional-spirals-corpus"
concept_slugs:
  - "fusion-fission-behavioral-forecasting"
dataset_slugs:
  - "stanford-delusional-spirals-corpus"
skill: "GeneralMLSkill"
processed_at: "2026-05-16T05:13:49Z"
created_at: "2026-05-16T05:13:49Z"
---

# Fusion-fission forecasts when AI will shift to undesirable behavior

**Authors**: Neil F. Johnson, Frank Yingjie Huo
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14218](https://arxiv.org/abs/2605.14218)

## Summary

This paper addresses the challenge of predicting undesirable behavioral shifts in LLMs by applying a vector generalization of fusion-fission dynamics from active matter systems. By modeling conversational history alongside desirable and undesirable response basins, the authors derive a universal condition for behavioral shifts that is independent of model size or specific architecture. This framework provides a real-time, pre-alignment safety signal that is validated against seven models, ten production chatbots, and a large-scale human-AI interaction corpus.

## Key Contributions

- Introduces a mathematical framework derived from fusion-fission dynamics that forecasts behavioral shifts in AI models from desirable to undesirable.
- Demonstrates 90% accuracy in identifying shifts across seven AI models ranging from 124M to 12B parameters and 10 production-scale chatbots.
- Validates predictive capabilities via a priori time-stamped forecasting confirmed by the Stanford 'Delusional Spirals' corpus.

## Open Questions & Future Work

- [[mitigating-behavioral-tipping-mechanisms]]

## Key Concepts

- [[fusion-fission-behavioral-forecasting]]: A framework for forecasting undesirable AI behavioral shifts by modeling the dynamics of response categories as competing basins in a vector-generalized fusion-fission model.

## Archivist Review

The paper presents a physically-inspired framework for predicting behavioral shifts in AI, which is both innovative and distinct from standard alignment methods. I have approved the framework and the associated dataset used for validation. I have also framed the core research challenge as an open question regarding the structural nature of these tipping mechanisms to focus on the technical bottleneck identified by the authors.

### Approved Concepts
- Fusion-fission behavioral forecasting: The paper proposes a novel, architecture-agnostic mechanism borrowed from active matter physics to predict AI behavioral shifts by modeling response trajectories as competing basins.

### Approved Open Questions
- Mitigating behavioral tipping mechanisms: If tipping dynamics are intrinsic to the model architecture, current safety alignment practices may be fundamentally limited in ensuring long-term, robust AI safety.

## Datasets

- [[stanford-delusional-spirals-corpus]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14218)
- [PDF](https://arxiv.org/pdf/2605.14218)

