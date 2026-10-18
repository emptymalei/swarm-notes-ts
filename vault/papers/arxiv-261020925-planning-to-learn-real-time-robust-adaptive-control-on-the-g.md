---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Planning to Learn: Real-Time Robust Adaptive Control on the GPU with Guaranteed Future Learning"
description: "This paper presents A-SLS, a learning-aware robust adaptive model predictive control (RAMPC) framework based on system-level synthesis (SLS). Unlike traditional robust controllers that treat future uncertainty as static, A-SLS forecasts future parameter updates and preserves correlations between disturbances and estimates to create tighter, guaranteed reachable sets. To enable real-time application on complex robots, the authors provide a GPU-accelerated solver, which they demonstrate on a 61-state quadruped and a physical drone. The approach significantly reduces conservativeness in safety-critical planning by anticipating information gain from future interactions."
resource: "https://arxiv.org/abs/2610.20925"
tags:
  - "robotics"
  - "control-systems"
  - "real-time-modeling"
  - "robust-optimization"
  - "uncertainty-quantification"
  - "gpu-acceleration"
  - "safety-critical systems"
  - "quadruped-robotics"
timestamp: "2026-10-18T00:28:09Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Anutam Srinivasan"
  - literal: "Siddhant Panse"
  - literal: "Glen Chou"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20925"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "a-sls"
    description: "A robust adaptive model predictive control framework based on system-level synthesis that forecasts future parameter uncertainty and information gain to construct tighter reachable sets."
datasets:
  []
open_questions:
  - name: "non-convex-sls-constraints"
    description: "How can learning-aware control frameworks be extended to handle highly non-convex state and control constraints while maintaining real-time guarantees provided by hardware acceleration?"
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:28:09Z"
created_at: "2026-10-18T00:28:09Z"
---

# Planning to Learn: Real-Time Robust Adaptive Control on the GPU with Guaranteed Future Learning

**Authors**: Anutam Srinivasan, Siddhant Panse, Glen Chou
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20925](https://arxiv.org/abs/2610.20925)

## Summary

This paper presents A-SLS, a learning-aware robust adaptive model predictive control (RAMPC) framework based on system-level synthesis (SLS). Unlike traditional robust controllers that treat future uncertainty as static, A-SLS forecasts future parameter updates and preserves correlations between disturbances and estimates to create tighter, guaranteed reachable sets. To enable real-time application on complex robots, the authors provide a GPU-accelerated solver, which they demonstrate on a 61-state quadruped and a physical drone. The approach significantly reduces conservativeness in safety-critical planning by anticipating information gain from future interactions.

## Key Contributions

- Introduces A-SLS, a learning-aware Robust Adaptive Model Predictive Control (RAMPC) framework that forecasts future parameter information gain to reduce conservativeness.
- Developed a GPU-accelerated A-SLS solver that enables real-time optimization for high-dimensional robotic systems.
- Demonstrated scaling of RAMPC to a whole-body quadruped model with 61 states and 8 uncertain parameters, a significant increase over prior state-of-the-art.
- Validated the framework on physical hardware using a Crazyflie drone to stabilize under online parameter adaptation.

## Limitations

The framework's performance depends on the accuracy of the uncertainty model and the computational overhead of the SLS optimization, which may still be challenging for even higher-dimensional or more complex non-linear dynamics.

## Open Questions & Future Work

- [[non-convex-sls-constraints]]

## Key Concepts

- [[a-sls]]: A robust adaptive model predictive control framework based on system-level synthesis that forecasts future parameter uncertainty and information gain to construct tighter reachable sets.

## Archivist Review

The paper presents a significant advancement in robust adaptive control by integrating learning-awareness into the System-Level Synthesis (SLS) framework. A-SLS is approved as a core concept because it addresses the conservative nature of traditional robust controllers by anticipating future information gain. The open question regarding scaling these methods to non-convex constraints is also approved as it represents a fundamental challenge for applying these safety-critical controllers to complex real-world environments. No datasets were proposed.

### Approved Concepts
- A-SLS: A-SLS addresses a fundamental limitation in robust control by explicitly accounting for future parameter learning during the planning phase, reducing the inherent conservativeness of traditional reachability analysis.

### Approved Open Questions
- Scaling SLS to Non-Convex Constraints: Real-world environments often contain non-convex obstacles and complex safety boundaries that require more flexible constraint handling than current linear-system-centric formulations allow.

## Links

- [Abstract](https://arxiv.org/abs/2610.20925)
- [PDF](https://arxiv.org/pdf/2610.20925)

