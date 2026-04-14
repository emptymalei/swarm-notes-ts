---
# CSL-compatible fields
title: "Towards Situation-aware State Modeling for Air Traffic Flow Prediction"
author:
  - literal: "Anqi Liu"
  - literal: "Bin Wang"
  - literal: "Jiangtao Zhao"
  - literal: "Dechuan Ma"
  - literal: "Guiyuan Jiang"
  - literal: "Feng Hong"
  - literal: "Yanwei Yu"
  - literal: "Tianrui Li"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11198"

# Custom fields
paper_id: "2604.11198"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "attention-mechanism"
  - "robustness"
  - "interpretability"
architectures:
  []
datasets:
  []
concept_slugs:
  - "direct-state-to-flow-modeling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:03:52Z"
created_at: "2026-04-14T05:03:52Z"
---

# Towards Situation-aware State Modeling for Air Traffic Flow Prediction

**Authors**: Anqi Liu, Bin Wang, Jiangtao Zhao, Dechuan Ma, Guiyuan Jiang, Feng Hong, Yanwei Yu, Tianrui Li
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11198](https://arxiv.org/abs/2604.11198)

## Summary

AeroSense addresses the limitations of time-series-based air traffic flow prediction by modeling the airspace as a dynamic set of microscopic aircraft states rather than aggregated flow sequences. By employing a situation-aware representation and masked self-attention, the model effectively captures real-time kinematics, aircraft interactions, and heterogeneous flow dynamics. Experiments confirm that this direct state-to-flow approach significantly outperforms traditional time-series forecasting, especially during peak traffic periods.

## Key Contributions

- Proposes AeroSense, a direct state-to-flow modeling framework that replaces traditional macroscopic time-series aggregation with processing of microscopic aircraft states.
- Incorporates a situation-aware state representation to capture instantaneous airspace dynamics and masked self-attention to model inter-aircraft interactions.
- Demonstrates superior predictive fidelity and robustness compared to time-series forecasting baselines on a large-scale terminal airspace dataset.

## Open Questions & Future Work

- [[scaling-state-to-flow-air-traffic-modeling]]

## Key Concepts

- [[direct-state-to-flow-modeling]]: A modeling paradigm that replaces macroscopic time-series aggregation with direct processing of microscopic agent states as dynamic sets to predict system-level flow.

## Archivist Review

I approved the core modeling paradigm 'Direct State-to-Flow Modeling' as a reusable concept for agent-based system forecasting, while rejecting the paper-specific model name 'AeroSense'. The open question regarding the scaling of this paradigm to network topologies and external environmental factors represents a substantial research gap in time-series-adjacent forecasting. No datasets were approved as none were explicitly named or uniquely identified beyond general large-scale airport data.

### Approved Concepts
- Direct State-to-Flow Modeling: This shifts the modeling paradigm from aggregated time-series prediction to entity-aware set processing, which is a powerful alternative for complex multi-agent system dynamics.

### Approved Open Questions
- Scaling State-to-Flow Air Traffic Modeling: This identifies the primary bottleneck in moving from specialized local airspace controllers to global, multi-scale traffic management systems.

### Rejected Candidates
- [concept] AeroSense (`aerosense`) - subcomponent_of_broader_mechanism: This is the specific model name rather than the underlying reusable mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.11198)
- [PDF](https://arxiv.org/pdf/2604.11198)

