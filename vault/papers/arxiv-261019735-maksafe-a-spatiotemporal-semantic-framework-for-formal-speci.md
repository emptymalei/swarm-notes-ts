---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "MakSafe: A Spatiotemporal Semantic Framework for Formal Specification and Compliance Checking of Road Vehicle Safety Rules"
description: "MakSafe is a formal spatiotemporal framework designed for the specification and compliance checking of road vehicle safety rules. By utilizing semantic zones and action-based forecasting, the framework evaluates safety through trace-tree reasoning, which avoids the limitations of uniform time discretization. The system formalizes road networks and vehicle states to execute complex rules such as Time-to-Collision (TTC) verification in sub-millisecond time. Experimental results demonstrate that the framework can efficiently derive safe and unsafe outcomes from branching future scenarios, supporting real-time safety monitoring and control update re-evaluation."
resource: "https://arxiv.org/abs/2610.19735"
tags:
  - "autonomous-driving"
  - "safety-critical systems"
  - "spatiotemporal-modeling"
  - "forecasting"
  - "real-time-modeling"
  - "decision-making"
  - "traffic-prediction"
timestamp: "2026-10-18T00:43:23Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Maksym Labzhaniia"
  - literal: "Julien Deantoni"
  - literal: "Marie-Agnès Peraldi-Frati"
  - literal: "Frédéric Mallet"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19735"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "trace-tree-reasoning"
    description: "A safety evaluation methodology that analyzes outcomes across branching future action sequences rather than single linear trajectories, often utilizing non-uniform time discretization."
datasets:
  []
open_questions:
  - name: "formal-verification-under-perception-uncertainty"
    description: "How can formal spatiotemporal frameworks integrate with the uncertainty and noise inherent in real-world sensor data and deep-learning-based perception outputs?"
  - name: "formal-rule-integration-in-learning-loops"
    description: "Can executable spatiotemporal rules be integrated directly into the training loops of neural driving policies to serve as differentiable safety constraints or shields?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:43:23Z"
created_at: "2026-10-18T00:43:23Z"
---

# MakSafe: A Spatiotemporal Semantic Framework for Formal Specification and Compliance Checking of Road Vehicle Safety Rules

**Authors**: Maksym Labzhaniia, Julien Deantoni, Marie-Agnès Peraldi-Frati, Frédéric Mallet
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19735](https://arxiv.org/abs/2610.19735)

## Summary

MakSafe is a formal spatiotemporal framework designed for the specification and compliance checking of road vehicle safety rules. By utilizing semantic zones and action-based forecasting, the framework evaluates safety through trace-tree reasoning, which avoids the limitations of uniform time discretization. The system formalizes road networks and vehicle states to execute complex rules such as Time-to-Collision (TTC) verification in sub-millisecond time. Experimental results demonstrate that the framework can efficiently derive safe and unsafe outcomes from branching future scenarios, supporting real-time safety monitoring and control update re-evaluation.

## Key Contributions

- Introduction of MakSafe, a formal spatiotemporal framework that enables the specification and checking of safety rules for automated vehicles without requiring uniform time discretization.
- Implementation of a trace-tree reasoning mechanism that derives branch-specific safety verdicts (safe vs. unsafe) from the same initial traffic scene.
- Development of action-based forecasting for occupancy zones, allowing for flexible prediction horizons and real-time re-evaluation after control updates.
- Demonstration of sub-millisecond rule-checking performance for front-vehicle identification and Time-to-Collision (TTC) verification across varying traffic densities.

## Limitations

The paper primarily focuses on front-vehicle identification and TTC, and the scalability of the trace-tree reasoning might be challenged by extremely high branching factors or dense, complex urban intersections.

## Open Questions & Future Work

- [[formal-verification-under-perception-uncertainty]]
- [[formal-rule-integration-in-learning-loops]]

## Key Concepts

- [[trace-tree-reasoning]]: A safety evaluation methodology that analyzes outcomes across branching future action sequences rather than single linear trajectories, often utilizing non-uniform time discretization.

## Archivist Review

I approved Trace-Tree Reasoning as it represents the core methodological contribution of evaluating safety across branching, non-uniform temporal traces. I rejected MakSafe as a standalone concept note because it refers specifically to the paper's implementation rather than a generalizable concept. The approved open questions address the industry-wide challenges of reconciling formal logic with probabilistic perception and integrating safety rules into learning-based controllers.

### Approved Concepts
- Trace-Tree Reasoning: It provides a mechanism for safety validation that explores multiple future trajectories (branching futures) simultaneously, which is more robust than linear trace analysis for autonomous decision-making.

### Approved Open Questions
- Formal Verification Under Perception Uncertainty: Bridging the gap between formal logic and probabilistic perception is a critical bottleneck for achieving certifiable safety in autonomous systems.
- Formal Rule Integration in Learning Loops: Integrating formal safety bounds into learning algorithms could prevent the exploration of catastrophically unsafe states during training and deployment.

### Rejected Candidates
- [concept] MakSafe (`maksafe`) - paper_local: This is the name of the specific framework/software tool presented in the paper; the underlying methodological innovation is better captured by the 'Trace-Tree Reasoning' concept.
- [concept] Semantic Zones (`semantic-zones`) - generic: Semantic zones is a generic descriptive term in spatial reasoning and GIS rather than a novel standalone mechanism.
- [concept] Action-Based Forecasting (`action-based-forecasting`) - subcomponent_of_broader_mechanism: This is a sub-component of the framework's operational logic rather than a distinct reusable architecture or technique.

## Links

- [Abstract](https://arxiv.org/abs/2610.19735)
- [PDF](https://arxiv.org/pdf/2610.19735)

