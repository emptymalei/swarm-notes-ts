---
# CSL-compatible fields
title: "SLALOM: Simulation Lifecycle Analysis via Longitudinal Observation Metrics for Social Simulation"
author:
  - literal: "Juhoon Lee"
  - literal: "Joseph Seering"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11466"

# Custom fields
paper_id: "2604.11466"
paper_source: "arxiv"
domain: "social-science-simulation"
tags:
  - "social-science-simulation"
  - "llm-agent-evaluation"
  - "longitudinal-analysis"
  - "simulation-validity"
architectures:
  []
datasets:
  []
concept_slugs:
  - "slalom-simulation-lifecycle-analysis"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:03:08Z"
created_at: "2026-04-14T05:03:08Z"
---

# SLALOM: Simulation Lifecycle Analysis via Longitudinal Observation Metrics for Social Simulation

**Authors**: Juhoon Lee, Joseph Seering
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11466](https://arxiv.org/abs/2604.11466)

## Summary

SLALOM addresses the validity crisis in LLM-based social simulations by moving beyond final outcome verification to assess the trajectory of social dynamics. The framework utilizes Pattern-Oriented Modeling to define critical intermediate waypoints, which simulated agents must traverse to ensure sociological plausibility. By applying Dynamic Time Warping to compare these simulated paths against empirical data, SLALOM provides a quantitative mechanism to distinguish meaningful social evolution from stochastic noise.

## Key Contributions

- Introduces SLALOM, a framework for evaluating LLM agent social simulations by assessing process fidelity rather than final outcomes.
- Implements waypoint-constrained evaluation by utilizing intermediate 'SLALOM gates' mapped to empirical sociological phases.
- Employs Dynamic Time Warping (DTW) to provide a quantitative metric for structural realism in longitudinal social simulations.

## Open Questions & Future Work

- [[non-linear-simulation-trajectory-validation]]

## Key Concepts

- [[slalom-simulation-lifecycle-analysis]]: A framework for validating LLM-agent social simulations by using Pattern-Oriented Modeling and Dynamic Time Warping to evaluate longitudinal process fidelity against intermediate waypoint constraints.

## Archivist Review

I approved SLALOM as a concept because it formalizes the shift from outcome-based to process-based evaluation in simulations, which is a significant and reusable methodological contribution. The approved open question focuses on the specific bottleneck of non-linear temporal dynamics in simulation evaluation, which provides a clear path for future research in trajectory alignment. Other candidates were rejected to prioritize clarity and minimize overlap.

### Approved Concepts
- SLALOM (Simulation Lifecycle Analysis via Longitudinal Observation Metrics): It introduces a systematic, trajectory-based validation paradigm for social simulations that prioritizes process fidelity over final-state outcomes.

### Approved Open Questions
- Non-linear simulation trajectory validation: High-fidelity social simulations frequently exhibit non-linear behaviors that current alignment metrics fail to capture, limiting the generalizability of existing process-validation frameworks.

### Rejected Candidates
- [open_question] Validating Non-linear Social Simulations (`evaluating-nonlinear-social-simulations`) - duplicate_existing: This candidate is largely redundant with the approved question but is phrased as a broader validation task rather than a specific research gap.

## Links

- [Abstract](https://arxiv.org/abs/2604.11466)
- [PDF](https://arxiv.org/pdf/2604.11466)

