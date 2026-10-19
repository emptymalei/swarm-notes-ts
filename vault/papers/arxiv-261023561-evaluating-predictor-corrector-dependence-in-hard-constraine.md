---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Evaluating Predictor-Corrector Dependence in Hard-Constrained Climate Emulators"
description: "This paper addresses a critical flaw in the evaluation of physics-constrained climate emulators, where the accuracy of the neural network predictor is often conflated with the efficacy of the hard-constraint corrector. The authors propose a decoupling framework to evaluate the predictor and corrector separately, revealing that hard constraints fundamentally reshape the predictor's behavior during training, often creating a dependency that degrades uncorrected forecast quality. Experiments on ACE2 and heat-equation systems show that while corrections improve physical consistency, they can hide underlying predictor deficits that are only mitigable through specific training strategies like direct uncorrected supervision."
resource: "https://arxiv.org/abs/2610.23561"
tags:
  - "earth-system-modeling"
  - "physics-informed-machine-learning"
  - "climate-modeling"
  - "weather-forecasting"
  - "model-evaluation"
  - "evaluation-framework"
  - "deep-learning"
  - "dynamical-systems"
  - "spatiotemporal-modeling"
timestamp: "2026-10-19T04:25:29Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Tianyu Zhang"
  - literal: "Xinyu Wang"
  - literal: "Zhenghan Tai"
  - literal: "Xiao-Wen Chang"
  - literal: "Yoshua Bengio"
issued:
  date-parts:
    - [2026, 10, 16]

# Domain-specific custom fields
paper_id: "2610.23561"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "predictor-corrector-evaluation-framework"
    description: "An evaluation methodology that decouples the contributions of a neural network predictor from the physical correction step in hard-constrained machine learning emulators."
  - name: "predictor-corrector-dependence"
    description: "A phenomenon where a neural network's internal representations and predictive accuracy are fundamentally altered by the presence of a hard-constraint corrector during training."
datasets:
  []
open_questions:
  - name: "predictor-corrector-interaction-generalization"
    description: "The extent to which the interactions between neural predictors and hard-constraint correctors—such as the tendency of predictors to develop dependencies on correction during training—generalize across different architectures and physical domains remains undetermined. It is not yet known if the patterns observed in atmospheric and heat-equation systems, including the \"concealment\" of predictor errors by correctors, persist in other complex dynamical regimes or under different types of constraint-enforcing operations."
  - name: "horizon-dependent-error-reversal-mechanisms"
    description: "The underlying mechanisms that cause predictive error patterns to reverse across different forecast horizons are not yet understood. It remains unresolved whether these reversals are primarily driven by the magnitude of the applied correction at specific lead times, the accumulation of physical residuals such as water-budget imbalances, or fundamental shifts in the input distributions encountered during long-range recursive rollouts."
skill: "GeneralMLSkill"
processed_at: "2026-10-19T04:25:29Z"
created_at: "2026-10-19T04:25:29Z"
---

# Evaluating Predictor-Corrector Dependence in Hard-Constrained Climate Emulators

**Authors**: Tianyu Zhang, Xinyu Wang, Zhenghan Tai, Xiao-Wen Chang, Yoshua Bengio
**Date**: 2026-10-16
**Paper ID**: [arxiv:2610.23561](https://arxiv.org/abs/2610.23561)

## Summary

This paper addresses a critical flaw in the evaluation of physics-constrained climate emulators, where the accuracy of the neural network predictor is often conflated with the efficacy of the hard-constraint corrector. The authors propose a decoupling framework to evaluate the predictor and corrector separately, revealing that hard constraints fundamentally reshape the predictor's behavior during training, often creating a dependency that degrades uncorrected forecast quality. Experiments on ACE2 and heat-equation systems show that while corrections improve physical consistency, they can hide underlying predictor deficits that are only mitigable through specific training strategies like direct uncorrected supervision.

## Key Contributions

- Proposed an evaluation framework that decouples predictor accuracy from corrector effects using autonomous rollouts and cross-correction testing.
- Discovered 'predictor-corrector dependence,' demonstrating that training with hard constraints can degrade the raw accuracy of the underlying neural network predictor.
- Demonstrated that direct supervision of uncorrected outputs can mitigate the accuracy deficit in short-horizon precipitation forecasts without harming corrected performance.
- Quantified the specific benefit of physical corrections over matched non-physical controls in maintaining model accuracy in heat-equation systems.

## Limitations

The study focuses on short to medium-range horizons (up to 30 days); effects on long-term climate stability or multi-decadal rollouts were not fully explored.

## Open Questions & Future Work

- [[predictor-corrector-interaction-generalization]]
- [[horizon-dependent-error-reversal-mechanisms]]

## Key Concepts

- [[predictor-corrector-evaluation-framework]]: An evaluation methodology that decouples the contributions of a neural network predictor from the physical correction step in hard-constrained machine learning emulators.
- [[predictor-corrector-dependence]]: A phenomenon where a neural network's internal representations and predictive accuracy are fundamentally altered by the presence of a hard-constraint corrector during training.

## Archivist Review

Approved the evaluation framework and the identified 'predictor-corrector dependence' phenomenon as they provide a formal methodology for auditing hybrid ML-physics systems. These concepts address a significant gap in current climate emulation evaluation practices. Approved two open questions concerning the universality of these dependencies and the mechanical explanation for lead-time dependent error reversals, both of which are critical for future robust emulator development.

### Approved Concepts
- Predictor-Corrector Evaluation Framework: Standard evaluation of constrained emulators conflates neural network skill with the correction step, masking potential model degradation or reliance on the post-processor.
- Predictor-Corrector Dependence: Identifies a critical failure mode in physics-informed training where models learn to rely on post-processing corrections, potentially leading to poor generalization or unphysical internal states.

### Approved Open Questions
- Generalization of Predictor-Corrector Interactions: Establishing the universality of these dependencies is essential for building trustworthy hybrid models that maintain physical consistency without concealing underlying predictor degradation.
- Mechanisms of Horizon-Dependent Error Reversal: Decoupling the factors that drive long-horizon stability from short-horizon accuracy deficits is critical for optimizing training objectives in autoregressive physical emulators.

### Rejected Candidates
- [dataset] ACE2 Emulator (`ace2-emulator`) - duplicate_existing: ACE2 (AI2 Climate Emulator) is an existing model/architecture framework used for experiments, not a novel dataset introduced by this paper.
- [concept] Hard-Constrained Emulators (`hard-constrained-emulators`) - not_novel: This refers to a broad, established category of physics-informed models rather than a specific method or discovery unique to this paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.23561)
- [PDF](https://arxiv.org/pdf/2610.23561)

