---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "FutureLift: Lifting Trajectory Proposals into Bidirectional Future Graphs for Motion Forecasting"
description: "FutureLift is a modular refinement framework designed to improve the accuracy of multimodal trajectory proposals in autonomous driving. It 'lifts' trajectory proposals into a heterogeneous future graph, where temporal nodes are connected to agent history, map data, and other agents' futures. By utilizing bidirectional temporal edges, the model enables future evidence to inform the correction of earlier trajectory segments, bypassing the limitations of sequential segment updates. The framework is backbone-agnostic and achieves top-tier results on the Waymo Open Motion Dataset and Argoverse 2 benchmarks, particularly in displacement error metrics."
resource: "https://arxiv.org/abs/2610.22215"
tags:
  - "motion-prediction"
  - "autonomous-driving"
  - "trajectory-prediction"
  - "graph-neural-networks"
  - "spatio-temporal-modeling"
  - "multimodal-learning"
  - "refinement"
  - "trajectory-forecasting"
timestamp: "2026-10-18T00:15:42Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Daniel Grimm"
  - literal: "J. Marius Zöllner"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22215"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "future-lift"
    description: "A backbone-agnostic refinement framework that treats trajectory proposals as heterogeneous graphs to allow non-sequential correction of motion forecasts."
  - name: "bidirectional-future-graph"
    description: "A graph-based representation of proposed trajectories where bidirectional temporal edges enable future proposed states to inform the refinement of earlier segments."
datasets:
  - name: "Waymo Open Motion Dataset (WOMD)"
    description: "A large-scale motion forecasting dataset for autonomous driving, featuring high-quality trajectories and HD maps, used as the primary benchmark for SOTA displacement error (minADE/minFDE) claims."
  - name: "Argoverse 2"
    description: "A benchmark for long-term motion forecasting in diverse urban environments, focusing on complex scenarios and multimodal prediction."
open_questions:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:15:42Z"
created_at: "2026-10-18T00:15:42Z"
---

# FutureLift: Lifting Trajectory Proposals into Bidirectional Future Graphs for Motion Forecasting

**Authors**: Daniel Grimm, J. Marius Zöllner
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22215](https://arxiv.org/abs/2610.22215)

## Summary

FutureLift is a modular refinement framework designed to improve the accuracy of multimodal trajectory proposals in autonomous driving. It 'lifts' trajectory proposals into a heterogeneous future graph, where temporal nodes are connected to agent history, map data, and other agents' futures. By utilizing bidirectional temporal edges, the model enables future evidence to inform the correction of earlier trajectory segments, bypassing the limitations of sequential segment updates. The framework is backbone-agnostic and achieves top-tier results on the Waymo Open Motion Dataset and Argoverse 2 benchmarks, particularly in displacement error metrics.

## Key Contributions

- Proposed FutureLift, a backbone-agnostic refinement framework that improves trajectory proposals by representing them as heterogeneous future graphs.
- Introduced bidirectional temporal edges within the future graph to allow later proposed trajectory segments to serve as context for revising earlier coordinates.
- Achieved state-of-the-art performance on the WOMD motion-prediction leaderboard for standard-input methods, ranking first in minADE (0.5049m) and minFDE (0.9942m).

## Limitations

The paper focuses on standard-input methods (excluding LiDAR or ensembling), so performance relative to heavily ensembled multi-modal sensor fusion models remains to be fully explored.

## Key Concepts

- [[future-lift]]: A backbone-agnostic refinement framework that treats trajectory proposals as heterogeneous graphs to allow non-sequential correction of motion forecasts.
- [[bidirectional-future-graph]]: A graph-based representation of proposed trajectories where bidirectional temporal edges enable future proposed states to inform the refinement of earlier segments.

## Archivist Review

The paper's primary contribution (FutureLift) and its core architectural mechanism (Bidirectional Future Graph) were approved as they represent a significant shift toward modular, non-sequential trajectory refinement. The Waymo Open Motion Dataset and Argoverse 2 were approved as they are the foundational benchmarks for motion forecasting and central to the paper's performance claims. The open question regarding end-to-end training was rejected as a routine optimization step rather than a unique research challenge.

### Approved Concepts
- FutureLift: It establishes a modular, backbone-agnostic interface for motion forecast refinement, allowing the decoupling of proposal generation from trajectory correction.
- Bidirectional Future Graph: Unlike sequential refiners that update segments chronologically, this representation allows the 'end' of a proposed trajectory to provide context for correcting its 'beginning', improving global temporal consistency.

### Rejected Candidates
- [open_question] End-to-end Refinement Training (`end-to-end-futurelift-integration`) - generic: The question of end-to-end integration for modular refiners is a standard architectural trade-off and does not represent a novel research bottleneck specific to this paper's findings.

## Datasets

- [[Waymo Open Motion Dataset (WOMD)]]
- [[Argoverse 2]]

## Links

- [Abstract](https://arxiv.org/abs/2610.22215)
- [PDF](https://arxiv.org/pdf/2610.22215)

