---
# CSL-compatible fields
title: "A Novel Two-Step Approach for Reactive Power Demand Calculation Using Integrated Voltage Stability Analysis"
author:
  - literal: "Hassan Abouelgheit"
  - literal: "Hendrik Lens"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.25016"

# Custom fields
paper_id: "2604.25016"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "iterative-quasi-dynamic-simulation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:12:26Z"
created_at: "2026-04-29T05:12:26Z"
---

# A Novel Two-Step Approach for Reactive Power Demand Calculation Using Integrated Voltage Stability Analysis

**Authors**: Hassan Abouelgheit, Hendrik Lens
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.25016](https://arxiv.org/abs/2604.25016)

## Summary

This paper proposes a two-step methodology for calculating reactive power demand by integrating steady-state and dynamic stability assessments. The approach utilizes an iterative Quasi-Dynamic Simulation framework to perform a comprehensive annual analysis (8760 hours) of power systems, moving beyond existing single-simulation models. By applying multi-criteria violation assessments, the method successfully identifies voltage stability issues and calculates required reactive power across network buses.

## Key Contributions

- Introduces a two-step approach for calculating reactive power demand that integrates steady-state and dynamic stability assessments.
- Combines Quasi-Dynamic Simulation, Q-V analysis, and dynamic simulations to evaluate system stability over a full annual cycle (8760 hours).
- Implements a multi-criteria violation assessment framework (frequency, severity, and duration) to identify and address voltage stability issues across network buses.

## Open Questions & Future Work

- [[optimizing-reactive-power-placement-sizing]]

## Key Concepts

- [[iterative-quasi-dynamic-simulation]]: A sequential integration of steady-state and dynamic simulation methods to assess power system stability over extended time horizons.

## Archivist Review

The approved concept, 'Iterative Quasi-Dynamic Simulation', represents the core methodological contribution of the paper, offering a generalized framework for multi-regime time-series assessment in power systems. The approved open question addresses the practical gap between theoretical stability violations and engineering feasibility in power grid management, providing a clear future research direction. Other candidates were rejected because they were either paper-local implementation details or generic engineering challenges.

### Approved Concepts
- Iterative Quasi-Dynamic Simulation: The paper's primary contribution is this integration of steady-state and dynamic stability analysis for power system stability assessment.

### Approved Open Questions
- Optimizing Reactive Power Placement: Transitioning from reactive power calculation to optimized engineering deployment is necessary for practical power system management.

## Links

- [Abstract](https://arxiv.org/abs/2604.25016)
- [PDF](https://arxiv.org/pdf/2604.25016)

