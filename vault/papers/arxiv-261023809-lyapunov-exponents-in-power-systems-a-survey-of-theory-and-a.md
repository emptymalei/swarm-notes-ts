---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Lyapunov Exponents in Power Systems: A Survey of Theory and Applications in Stability, Control, Forecasting, and Protection"
description: "This paper provides a comprehensive survey of Lyapunov Exponents (LEs) as tools for power system stability, control, forecasting, and protection. Reviewing over 165 publications from 1990 to 2026, it traces the evolution of LE applications from simple machine models to contemporary inverter-based resource (IBR) dominated grids. The review highlights the transition from model-based analysis to data-driven and machine-learning-augmented approaches for quantifying grid predictability and stability."
resource: "https://arxiv.org/abs/2610.23809"
tags:
  - "energy-systems"
  - "nonlinear-dynamics"
  - "stability-analysis"
  - "forecasting"
  - "time-series-analysis"
  - "chaotic-systems"
  - "data-driven-control"
  - "machine-learning"
  - "power-estimation"
timestamp: "2026-10-19T04:24:24Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Mohammad Almomani"
  - literal: "Venkataramana Ajjarapu"
issued:
  date-parts:
    - [2026, 10, 16]

# Domain-specific custom fields
paper_id: "2610.23809"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "lyapunov-stability-analysis-in-power-systems"
    description: "A methodology for assessing grid stability and predictability by calculating the average exponential rates of divergence or convergence of state trajectories in phase space."
  - name: "ibr-dominated-grid-stability"
    description: "The study of stability and control in power systems where dynamics are driven by fast-switching power electronics rather than mechanical inertia."
datasets:
  []
open_questions:
  - name: "le-ibr-stability-framework"
    description: "There is a lack of a unified mathematical framework for computing Lyapunov exponents in systems dominated by inverter-based resources (IBRs) that accounts for piecewise-smooth dynamics and fast microsecond-scale control loops."
  - name: "predictability-horizon-integration"
    description: "Research is needed to systematically integrate theoretical predictability horizons (Tmax) as a standard planning and validation tool for load and renewable energy forecasting models, rather than treating them as purely theoretical limits."
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:24:24Z"
created_at: "2026-10-19T04:24:24Z"
---

# Lyapunov Exponents in Power Systems: A Survey of Theory and Applications in Stability, Control, Forecasting, and Protection

**Authors**: Mohammad Almomani, Venkataramana Ajjarapu
**Date**: 2026-10-16
**Paper ID**: [arxiv:2610.23809](https://arxiv.org/abs/2610.23809)

## Summary

This paper provides a comprehensive survey of Lyapunov Exponents (LEs) as tools for power system stability, control, forecasting, and protection. Reviewing over 165 publications from 1990 to 2026, it traces the evolution of LE applications from simple machine models to contemporary inverter-based resource (IBR) dominated grids. The review highlights the transition from model-based analysis to data-driven and machine-learning-augmented approaches for quantifying grid predictability and stability.

## Key Contributions

- Comprehensive taxonomy of Lyapunov Exponent (LE) applications across stability analysis, chaos control, forecasting, and fault diagnosis in power systems.
- Systematic comparison between traditional model-based LE calculation and modern data-driven estimation using machine learning.
- Analysis of LE-based predictability horizons for short-term load and renewable energy forecasting.
- Evaluation of stability assessment techniques for Inverter-Based Resource (IBR)-dominated grids using nonlinear metrics.

## Limitations

The paper notes gaps in real-time LE estimation from sparse or noisy synchrophasor data and the lack of standardized benchmarks for IBR stability.

## Open Questions & Future Work

- [[le-ibr-stability-framework]]
- [[predictability-horizon-integration]]

## Key Concepts

- [[lyapunov-stability-analysis-in-power-systems]]: A methodology for assessing grid stability and predictability by calculating the average exponential rates of divergence or convergence of state trajectories in phase space.
- [[ibr-dominated-grid-stability]]: The study of stability and control in power systems where dynamics are driven by fast-switching power electronics rather than mechanical inertia.

## Archivist Review

The approved items focus on the core theoretical shift discussed in the paper: applying Lyapunov exponents to the emerging problem of IBR-dominated grids. 'IBR-Dominated Grid Stability' is included as it represents the specific physical context requiring these new metrics. The open questions target the lack of formal frameworks for non-smooth switching in LE calculations and the under-utilized concept of physical predictability horizons in forecasting. Generic terms like 'load forecasting' and 'chaos detection' were rejected as they are broad domains rather than reusable methodological concepts.

### Approved Concepts
- Lyapunov Stability Analysis in Power Systems: LE-based methods provide a model-independent way to quantify the stability of power system dynamics, which is crucial as grids become more non-linear and complex.
- IBR-Dominated Grid Stability: The transition from synchronous machines to power-electronic-interfaced generation fundamentally changes power grid dynamics, requiring new stability paradigms.

### Approved Open Questions
- LE Framework for IBR Grids: Without a consistent framework, operators cannot reliably use LEs to predict instabilities caused by complex interactions between power electronics and the network.
- Predictability Horizon Integration Limits: Defining these limits helps distinguish between model errors and inherent physical unpredictability, allowing for more realistic reliability assessments in energy scheduling.

### Rejected Candidates
- [concept] Short-term Load Forecasting (`short-term-load-forecasting`) - generic: Generic application area and a standard task in power systems.
- [concept] Chaos Detection (`chaos-detection`) - not_novel: General mathematical technique not specific to this paper's novelty or a new architectural mechanism.
- [open_question] Quantitative Probabilistic Stability Margins (`le-probabilistic-stability-margins`) - other: Exceeded the limit of 2 open questions; other candidates were more central to the paper's focus on IBRs and predictability limits.
- [open_question] Device-Level Stability Responsibility Attribution (`le-device-stability-attribution`) - other: Exceeded the limit of 2 open questions; although important, it is more of a downstream task compared to the fundamental framework gaps.

## Links

- [Abstract](https://arxiv.org/abs/2610.23809)
- [PDF](https://arxiv.org/pdf/2610.23809)

