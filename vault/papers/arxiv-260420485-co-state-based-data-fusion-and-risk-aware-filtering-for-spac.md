---
# CSL-compatible fields
title: "Co-State Based Data Fusion and Risk Aware Filtering for Spacecraft Navigation and Hazard Prediction"
author:
  - literal: "Surya Ratna Prakash D"
  - literal: "Soumyendu Raha"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20485"

# Custom fields
paper_id: "2604.20485"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "anomaly-detection"
  - "probabilistic-forecasting"
  - "time-series"
  - "navigation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "differential-algebraic-co-state-fusion"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:06:21Z"
created_at: "2026-04-23T05:06:21Z"
---

# Co-State Based Data Fusion and Risk Aware Filtering for Spacecraft Navigation and Hazard Prediction

**Authors**: Surya Ratna Prakash D, Soumyendu Raha
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20485](https://arxiv.org/abs/2604.20485)

## Summary

This paper introduces a co-state-based fusion framework for spacecraft navigation and hazard prediction that treats co-states as instantaneous Lagrange multipliers to enforce measurement compatibility. By analyzing the trajectory of these co-states alongside innovation signals, the authors construct a continuous-time Markov generator to model regime transitions and perform probabilistic risk assessment. This approach provides an online, anomaly-detection pipeline that identifies navigation inconsistencies prior to catastrophic divergence, as demonstrated on real-world lunar descent telemetry. The method notably outperforms standard Extended Kalman Filters by identifying subtle geometric inconsistencies without requiring external fault labels or heuristic tuning.

## Key Contributions

- Introduces a co-state-based data fusion framework that utilizes instantaneous Lagrange multipliers to detect geometric inconsistencies in navigation systems.
- Develops a continuous-time Markov generator from co-state and innovation trajectories to facilitate probabilistic risk forecasting and mean first-passage time (MFPT) estimation.
- Demonstrates that the co-state framework enables earlier fault detection in lunar powered-descent telemetry compared to traditional Extended Kalman Filter (EKF) baselines without needing pre-labeled failure data.

## Open Questions & Future Work

- [[automated-parameter-tuning-for-co-state-fusion]]
- [[closed-loop-risk-aware-guidance-control]]

## Key Concepts

- [[differential-algebraic-co-state-fusion]]: A fusion framework that uses instantaneous Lagrange multipliers as differential algebraic co-states to enforce measurement consistency and identify system-level anomalies.

## Archivist Review

I approved the core co-state fusion mechanism as a reusable concept for physical state-space consistency, along with two open questions targeting the critical transition from diagnostic assessment to autonomous, parameter-agnostic control. I rejected the generic version of the fusion concept to avoid redundancy. Standard rigor was applied by focusing on methodology over local implementation details.

### Approved Concepts
- Differential Algebraic Co-state Fusion: This approach provides a physically grounded way to enforce dynamical consistency in navigation without heuristic fault models or labels, which is a reusable pattern for complex state-space modeling.

### Approved Open Questions
- Automated Parameter Tuning: Reducing manual calibration is critical for deploying adaptive anomaly detection in complex, long-duration autonomous systems.
- Closed-Loop Risk-Aware Control: Proactive risk mitigation is a necessary step to transition from diagnostic monitoring to fully autonomous operation in uncertain environments.

### Rejected Candidates
- [concept] Co-State Based Data Fusion (`co-state-based-data-fusion`) - duplicate_existing: This is synonymous with the more specific 'differential-algebraic-co-state-fusion' concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.20485)
- [PDF](https://arxiv.org/pdf/2604.20485)

