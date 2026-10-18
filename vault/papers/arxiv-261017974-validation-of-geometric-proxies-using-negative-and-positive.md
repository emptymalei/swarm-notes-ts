---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Validation of geometric proxies using negative and positive triangularity plasmas with varying elongation on TCV and multi-machine gyrokinetic simulations"
description: "This paper validates a set of computationally efficient geometric proxies for predicting turbulent transport in Negative Triangularity (NT) tokamak plasmas. By analyzing poloidally averaged magnetic drift and Finite Larmor Radius (FLR) effects, the authors identify a critical elongation threshold ($κ \\sim 0.75-0.8$) for NT confinement benefits, a finding corroborated by both GENE gyrokinetic simulations and experimental scans on the TCV tokamak. The study further demonstrates the robustness of these proxies across multiple experimental facilities (DIII-D, AUG, JET), showing that NT consistently reduces nonlinear heat flux by 1.6-2.1 times due to geometric stabilization of Ion Temperature Gradient (ITG) and Trapped Electron Mode (TEM) turbulence."
resource: "https://arxiv.org/abs/2610.17974"
tags:
  - "physics"
  - "scientific-modeling"
  - "simulation"
  - "fluid-dynamics"
  - "tokamak"
  - "plasma-physics"
  - "negative-triangularity"
  - "gyrokinetic-simulations"
timestamp: "2026-10-18T01:00:23Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Alessandro Balestri"
  - literal: "Justin Ball"
  - literal: "Stefano Coda"
  - literal: "Olivier Sauter"
  - literal: "Paola Mantica"
  - literal: "Alberto Mariani"
  - literal: "Benoit Labit"
  - literal: "Branka Vanovac"
  - literal: "Joerg Hobirk"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.17974"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "negative-triangularity"
    description: "A tokamak magnetic configuration where the plasma cross-section is shaped with the triangle's tip pointing towards the central column, resulting in naturally suppressed turbulent transport."
  - name: "geometric-transport-proxies"
    description: "Reduced-order physical parameters derived from magnetic geometry used to estimate turbulent heat transport without requiring full-scale gyrokinetic simulations."
datasets:
  []
open_questions:
  - name: "asymmetric-plasma-transport-modeling"
    description: "How can predictive models for turbulent transport be generalized to accurately capture the physics of up-down asymmetric equilibria, where simple scalar metrics for triangularity fail to represent the magnetic configuration?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T01:00:23Z"
created_at: "2026-10-18T01:00:23Z"
---

# Validation of geometric proxies using negative and positive triangularity plasmas with varying elongation on TCV and multi-machine gyrokinetic simulations

**Authors**: Alessandro Balestri, Justin Ball, Stefano Coda, Olivier Sauter, Paola Mantica, Alberto Mariani, Benoit Labit, Branka Vanovac, Joerg Hobirk
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.17974](https://arxiv.org/abs/2610.17974)

## Summary

This paper validates a set of computationally efficient geometric proxies for predicting turbulent transport in Negative Triangularity (NT) tokamak plasmas. By analyzing poloidally averaged magnetic drift and Finite Larmor Radius (FLR) effects, the authors identify a critical elongation threshold ($κ \sim 0.75-0.8$) for NT confinement benefits, a finding corroborated by both GENE gyrokinetic simulations and experimental scans on the TCV tokamak. The study further demonstrates the robustness of these proxies across multiple experimental facilities (DIII-D, AUG, JET), showing that NT consistently reduces nonlinear heat flux by 1.6-2.1 times due to geometric stabilization of Ion Temperature Gradient (ITG) and Trapped Electron Mode (TEM) turbulence.

## Key Contributions

- Validated geometric proxies based on magnetic drift and FLR effects as computationally inexpensive predictors of turbulent transport in Negative Triangularity (NT) plasmas.
- Identified and experimentally confirmed a critical elongation threshold (κ ≈ 0.8) below which the confinement advantages of NT over Positive Triangularity (PT) are lost.
- Demonstrated through GENE simulations that NT reduces nonlinear heat fluxes by factors of 1.6 to 2.1 across JET, DIII-D, and ASDEX Upgrade (AUG) scenarios.
- Established that magnetic drifts and Finite Larmor Radius (FLR) effects are the dominant stabilizing mechanisms in NT plasmas, outweighing parallel dynamics.

## Limitations

The analysis of up-down asymmetric equilibria suggests that conventional triangularity-based descriptions may be insufficient, necessitating more robust geometric definitions.

## Open Questions & Future Work

- [[asymmetric-plasma-transport-modeling]]

## Key Concepts

- [[negative-triangularity]]: A tokamak magnetic configuration where the plasma cross-section is shaped with the triangle's tip pointing towards the central column, resulting in naturally suppressed turbulent transport.
- [[geometric-transport-proxies]]: Reduced-order physical parameters derived from magnetic geometry used to estimate turbulent heat transport without requiring full-scale gyrokinetic simulations.

## Archivist Review

The approved concepts focus on the core physical configuration (Negative Triangularity) and the primary methodological contribution (Geometric Transport Proxies), both of which are central to the paper's predictive claims and relevant to scientific modeling. The open question regarding asymmetric equilibria addresses a specific technical bottleneck identified in the study. The dataset was rejected as it is a routine experimental record from a specific facility rather than a general-purpose benchmark.

### Approved Concepts
- Negative Triangularity: NT is a transformative magnetic configuration that decouples high core performance from edge instabilities, representing a major shift in tokamak reactor design strategy.
- Geometric Transport Proxies: Full gyrokinetic simulations are computationally prohibitive for real-time control; these proxies provide a physically grounded, low-cost alternative for predicting turbulence.

### Approved Open Questions
- Transport Prediction in Asymmetric Equilibria: Modern reactor designs often incorporate asymmetric features (e.g., single-null diverters) that are not well-served by current simplified geometric models.

### Rejected Candidates
- [dataset] TCV Tokamak Experimental Data (`tcv-tokamak-experimental-data`) - paper_local: The TCV data is specific to a single experimental facility and session; it is not presented as a reusable, standardized benchmark for the broader ML community.
- [concept] GENE Simulations (`gene-simulations`) - not_novel: GENE is an established software tool for gyrokinetic simulations, not a novel concept or mechanism introduced in this paper.
- [concept] Elongation Scan (`elongation-scan`) - not_novel: Elongation scans are a routine experimental procedure in plasma physics and do not constitute a standalone novel mechanism or concept.
- [concept] H-mode (`h-mode`) - not_novel: H-mode (High-confinement mode) is a well-established and long-standing plasma regime in fusion research.

## Links

- [Abstract](https://arxiv.org/abs/2610.17974)
- [PDF](https://arxiv.org/pdf/2610.17974)

