---
# CSL-compatible fields
title: "Forecasting Motion in the Wild"
author:
  - literal: "Neerja Thakkar"
  - literal: "Shiry Ginosar"
  - literal: "Jacob Walker"
  - literal: "Jitendra Malik"
  - literal: "Joao Carreira"
  - literal: "Carl Doersch"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.01015"

# Custom fields
paper_id: "2604.01015"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "computer-vision"
  - "forecasting"
  - "diffusion-transformers"
  - "motion-prediction"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dense-point-trajectories-as-visual-tokens"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-02T05:37:22Z"
created_at: "2026-04-02T05:37:22Z"
---

# Forecasting Motion in the Wild

**Authors**: Neerja Thakkar, Shiry Ginosar, Jacob Walker, Jitendra Malik, Joao Carreira, Carl Doersch
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.01015](https://arxiv.org/abs/2604.01015)

## Summary

This paper addresses the challenge of predictive visual intelligence by proposing dense point trajectories as a generalized, category-agnostic representation of behavior. The authors implement a diffusion transformer that processes these trajectories as unordered sets, allowing for coherent motion forecasting that accounts for complex occlusions. To evaluate the model's performance in unconstrained settings, they introduce a large-scale dataset of animal motion, demonstrating superior generalization to rare species and morphologies compared to existing baselines.

## Key Contributions

- Introduces dense point trajectories as a category-agnostic visual representation that disentangles motion from appearance.
- Develops a diffusion transformer architecture capable of modeling sets of trajectories while explicitly handling occlusion.
- Curates a large-scale, 300-hour dataset of unconstrained animal videos featuring camera-motion compensation for robust forecasting evaluation.

## Open Questions & Future Work

- [[improving-perception-robustness-for-behavior-forecasting]]

## Key Concepts

- [[dense-point-trajectories-as-visual-tokens]]: A mid-level representation using dense point trajectories to disentangle motion from appearance across diverse, non-rigid agents.

## Archivist Review

I approved the concept of dense point trajectories as visual tokens because it represents a clear, reusable architectural abstraction for disentangling motion and appearance. I also approved the open question on perception robustness, as it highlights a persistent, domain-agnostic bottleneck in agent-centric behavior forecasting. I rejected no candidates because only one of each was proposed, and both were sufficiently high-level and theoretically valuable.

### Approved Concepts
- Dense Point Trajectories as Visual Tokens: This representation shifts the focus of behavior modeling from pixel-level or box-level predictions to a trajectory-based abstraction that disentangles motion from appearance, enhancing generalization.

### Approved Open Questions
- Improving Perception for Motion Forecasting: This is critical because the quality of the learned motion representation depends heavily on the accuracy of the underlying perception pipeline; if the data processing is noisy or incomplete, the trajectory forecasting model's performance on rare species or complex scenarios will be severely hindered.

## Links

- [Abstract](https://arxiv.org/abs/2604.01015)
- [PDF](https://arxiv.org/pdf/2604.01015)

