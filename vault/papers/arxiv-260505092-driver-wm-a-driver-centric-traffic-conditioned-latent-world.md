---
# CSL-compatible fields
title: "Driver-WM: A Driver-Centric Traffic-Conditioned Latent World Model for In-Cabin Dynamics Rollout"
author:
  - literal: "Haozhuang Chi"
  - literal: "Daosheng Qiu"
  - literal: "Hao Su"
  - literal: "Haochen Liu"
  - literal: "Zirui Li"
  - literal: "Haoruo Zhang"
  - literal: "Chen Lv"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.05092"

# Custom fields
paper_id: "2605.05092"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "driver-wm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:13:33Z"
created_at: "2026-05-07T05:13:33Z"
---

# Driver-WM: A Driver-Centric Traffic-Conditioned Latent World Model for In-Cabin Dynamics Rollout

**Authors**: Haozhuang Chi, Daosheng Qiu, Hao Su, Haochen Liu, Zirui Li, Haoruo Zhang, Chen Lv
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.05092](https://arxiv.org/abs/2605.05092)

## Summary

Driver-WM is a novel latent world model designed to predict human driver dynamics within shared-control driving systems by conditioning on external traffic stimuli. The model uses a dual-stream architecture in a compact latent space, applying a gated causal injection mechanism to relate traffic context to in-cabin behavior. This approach enables robust long-horizon geometric forecasting and allows for controlled test-time interventions to evaluate human-machine interaction safety.

## Key Contributions

- Proposes Driver-WM, a latent world model for driver dynamics that bridges the gap between external traffic context and internal driver behavior.
- Implements a gated causal injection mechanism that enforces temporal consistency while modulating external perturbations on driver state predictions.
- Achieves improved multi-step geometric forecasting for high-motion maneuvers and semantic alignment in assistive driving benchmarks.

## Open Questions & Future Work

- [[modeling-driver-as-dynamical-system]]

## Key Concepts

- [[driver-wm]]: A driver-centric latent world model that rolls out in-cabin dynamics by conditioning on external traffic context using a dual-stream architecture with gated causal injection.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 1 concept(s), 1 open question(s), and 0 dataset(s), with 1 rejected candidate note(s).

### Approved Concepts
- Driver-WM: Provides a unified, causal framework for predicting human-in-the-loop driver dynamics conditioned on external environmental stimuli via a gated causal injection mechanism.

### Approved Open Questions
- Modeling Driver as Dynamical System: Transitioning from static recognition to dynamic world modeling for human drivers is critical for anticipating safety-critical reactions in shared-control systems.

### Rejected Candidates
- [concept] Driver-WM (`driver-wm`) - other: The paper proposes a specific implementation of a latent world model, which I am approving as a concept under the specific slug 'driver-wm'; however, if the gated causal injection mechanism is considered the primary novelty, the model architecture itself is the overarching mechanism. (Self-Correction: I have approved the model as the primary mechanism).

## Links

- [Abstract](https://arxiv.org/abs/2605.05092)
- [PDF](https://arxiv.org/pdf/2605.05092)

