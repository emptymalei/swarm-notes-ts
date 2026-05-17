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
  []
concept_slugs:
  - "fusion-fission-behavioral-forecasting"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-17T05:25:33Z"
created_at: "2026-05-17T05:25:33Z"
---

# Fusion-fission forecasts when AI will shift to undesirable behavior

**Authors**: Neil F. Johnson, Frank Yingjie Huo
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14218](https://arxiv.org/abs/2605.14218)

## Summary

This paper addresses the critical challenge of predicting shifts in AI behavior from desirable to undesirable by applying concepts from fusion-fission group dynamics found in living systems. The proposed framework tracks competition between conversation history and response-class basins to forecast behavioral transitions in a model-agnostic manner. Validated across diverse chatbot architectures and large-scale datasets, the method offers a real-time safety mechanism independent of existing post-training alignment strategies.

## Key Contributions

- Introduces a model-agnostic mathematical framework that predicts undesirable shifts in AI behavior by analyzing group-level basin dynamics.
- Demonstrates 90% accuracy in forecasting behavioral shifts across seven distinct AI models ranging from 124M to 12B parameters.
- Provides a real-time warning signal that operates architecturally below existing alignment stacks, enabling proactive detection of undesirable outputs.

## Open Questions & Future Work

- [[architectural-mitigation-of-tipping]]

## Key Concepts

- [[fusion-fission-behavioral-forecasting]]: A predictive framework for AI behavioral shifts based on a vector generalization of fusion-fission group dynamics derived from living and active-matter systems.

## Archivist Review

The paper proposes a novel framework for forecasting AI behavioral shifts by treating conversation dynamics as a fusion-fission process, which is highly distinct from standard model-specific alignment. I approved the core forecasting mechanism as a reusable concept and the question of architectural mitigation as a critical open problem that challenges current safety-by-alignment paradigms. Other minor candidates were rejected for being redundant or too closely tied to specific paper applications.

### Approved Concepts
- Fusion-Fission Behavioral Forecasting: It provides the core mathematical framework for predicting shifts to undesirable AI behavior based on group-level dynamics rather than model-specific features.

### Approved Open Questions
- Architectural Mitigation of Tipping: The existence of this mechanism suggests that current safety practices, such as RLHF, may be fundamentally limited if they only treat the symptoms rather than the root geometric drivers of behavioral instability. Understanding whether this can be architecturally mitigated is critical for future safety-by-design research.

## Links

- [Abstract](https://arxiv.org/abs/2605.14218)
- [PDF](https://arxiv.org/pdf/2605.14218)

