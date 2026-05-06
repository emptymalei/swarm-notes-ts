---
# CSL-compatible fields
title: "DynoSLAM: Dynamic SLAM with Generative Graph Neural Networks for Real-World Social Navigation"
author:
  - literal: "Danil Tokhchukov"
  - literal: "Veronika Morozova"
  - literal: "Gonzalo Ferrer"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02759"

# Custom fields
paper_id: "2605.02759"
paper_source: "arxiv"
domain: "robotics"
tags:
  - "robotics"
  - "slam"
  - "graph-neural-networks"
  - "motion-planning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "action-conditioned-world-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:13:50Z"
created_at: "2026-05-06T05:13:50Z"
---

# DynoSLAM: Dynamic SLAM with Generative Graph Neural Networks for Real-World Social Navigation

**Authors**: Danil Tokhchukov, Veronika Morozova, Gonzalo Ferrer
**Date**: 2026-05-04
**Paper ID**: [arxiv:2605.02759](https://arxiv.org/abs/2605.02759)

## Summary

DynoSLAM addresses the limitations of traditional static-environment SLAM algorithms by integrating socially-aware GNNs into factor graph optimization. By modeling pedestrian motion as a stochastic world model, the framework captures multimodal epistemic uncertainty through Monte Carlo rollouts and embeds these priors into the SLAM graph via dynamic Mahalanobis distance factors. This approach mitigates optimization failures associated with deterministic movement assumptions and provides a rigorous probabilistic safety envelope for robot navigation in crowded scenarios.

## Key Contributions

- Introduces DynoSLAM, a tightly-coupled Dynamic GraphSLAM architecture integrating socially-aware GNNs for robust performance in dynamic environments.
- Formulates pedestrian motion forecasting as a stochastic world model, capturing multimodal epistemic uncertainty through GNN-based Monte Carlo rollouts.
- Introduces a dynamic Mahalanobis distance factor to optimize SLAM trajectories while preventing deterministic 'argmax problem' failures.
- Enables probabilistic safety envelope estimation for downstream navigation planners, improving collision-free motion in crowded spaces.

## Open Questions & Future Work

- [[flow-matching-trajectory-prediction]]

## Key Concepts

- [[action-conditioned-world-model]]: A stochastic world model that integrates pedestrian motion forecasting into SLAM via Monte Carlo rollouts from a GNN.

## Archivist Review

The paper is approved for its novel integration of a stochastic world model into a dynamic SLAM framework, replacing rigid heuristics with a GNN-based probabilistic approach. I have approved the 'action-conditioned-world-model' concept for its reusable mechanism and the 'flow-matching-trajectory-prediction' open question for its potential to replace computationally expensive sampling with more rigorous generative approaches in robotics.

### Approved Concepts
- Action-conditioned world model: Central to the paper's integration of motion forecasting into SLAM as a stochastic process rather than a static heuristic.

### Approved Open Questions
- Flow Matching for Trajectory Forecasting: Transitioning from perturbation-based sampling to learned flow fields could provide more reliable and computationally efficient uncertainty quantification in dynamic SLAM environments.

## Links

- [Abstract](https://arxiv.org/abs/2605.02759)
- [PDF](https://arxiv.org/pdf/2605.02759)

