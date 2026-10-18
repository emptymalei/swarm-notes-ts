---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Predicting Unseen Scientific Interactions: Conditional Flow Models Hallucinate Non-Additive Effects"
description: "This paper investigates the ability of conditional flow-matching models to predict and extrapolate non-additive scientific interactions, such as drug-drug effects or cellular perturbations. The authors demonstrate that models often prioritize learning individual effects over interactions, leading to 'interaction hallucinations' where non-existent effects are predicted in unseen conditions. The research highlights that generalization success is heavily dependent on condition structure and that standard performance metrics can be deceptive, failing to indicate whether a model has truly captured the underlying scientific mechanism."
resource: "https://arxiv.org/abs/2610.20288"
tags:
  - "scientific-machine-learning"
  - "flow-matching"
  - "time-series"
  - "generative-modeling"
  - "generalization"
  - "distribution-shift"
  - "uncertainty-quantification"
  - "biophysics"
  - "medical-ai"
timestamp: "2026-10-18T00:33:59Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Sam Gijsen"
  - literal: "Moritz Seiler"
  - literal: "Kerstin Ritter"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20288"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "interaction-hallucination"
    description: "The tendency of conditional generative models to predict spurious non-additive effects between variables when generalizing to unseen combinations of conditions."
datasets:
  []
open_questions:
  - name: "interaction-identifiability-biases"
    description: "How can we develop inductive biases or training objectives that prioritize the learning of identifiable interaction effects over the simple interpolation of main effects in high-dimensional scientific spaces?"
  - name: "metrics-for-scientific-interaction-recovery"
    description: "What specific evaluation metrics can reliably distinguish between true learned scientific interactions and hallucinated non-additive effects, especially in out-of-distribution scenarios where ground truth is scarce?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:33:59Z"
created_at: "2026-10-18T00:33:59Z"
---

# Predicting Unseen Scientific Interactions: Conditional Flow Models Hallucinate Non-Additive Effects

**Authors**: Sam Gijsen, Moritz Seiler, Kerstin Ritter
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20288](https://arxiv.org/abs/2610.20288)

## Summary

This paper investigates the ability of conditional flow-matching models to predict and extrapolate non-additive scientific interactions, such as drug-drug effects or cellular perturbations. The authors demonstrate that models often prioritize learning individual effects over interactions, leading to 'interaction hallucinations' where non-existent effects are predicted in unseen conditions. The research highlights that generalization success is heavily dependent on condition structure and that standard performance metrics can be deceptive, failing to indicate whether a model has truly captured the underlying scientific mechanism.

## Key Contributions

- Discovered that individual effects are learned significantly earlier than interaction effects in flow-matching models, leading to a phase where models predict plausible but incorrect interactions.
- Demonstrated that successful extrapolation to unseen scientific interactions depends on whether the underlying condition structure is preserved between training and test sets.
- Identified that interaction recovery is sensitive to nonlinear readouts, where a model may capture the interaction in its output space but lose it under typical scientific measurement transformations.
- Revealed that standard fidelity metrics like FID or MSE are insufficient for evaluating whether a model has actually learned the causal interaction structure of a system.

## Limitations

The study primarily focuses on flow-matching models and the specific failure modes identified may vary across other generative architectures like VAEs or Diffusion Transformers.

## Open Questions & Future Work

- [[interaction-identifiability-biases]]
- [[metrics-for-scientific-interaction-recovery]]

## Key Concepts

- [[interaction-hallucination]]: The tendency of conditional generative models to predict spurious non-additive effects between variables when generalizing to unseen combinations of conditions.

## Archivist Review

I approved 'Interaction Hallucination' as it describes a specific, novel failure mode in scientific generative modeling identified by the paper. I rejected 'Interaction Recovery' as it is a standard statistical goal. I approved two open questions that address the critical gaps in identifiability and evaluation metrics for non-additive effects, which are central to the paper's findings.

### Approved Concepts
- Interaction Hallucination: Identifies a critical failure mode in generative models used for scientific discovery, where models predict complex non-additive effects that are actually artifacts of the learning process rather than physical reality.

### Approved Open Questions
- Interaction Identifiability in High-Dimensions: Current generative models struggle with identifiability, often prioritizing simple main effects or hallucinating complex ones, which leads to false scientific conclusions.
- Metrics for Scientific Interaction Recovery: Without targeted metrics for interaction fidelity, researchers may over-rely on models that appear accurate on average but fail on the most scientifically critical non-additive predictions.

### Rejected Candidates
- [concept] Interaction Recovery (`interaction-recovery`) - generic: The term is used generically in statistics and the paper treats it as a goal/task rather than a novel conceptual mechanism or phenomenon.
- [concept] Flow Matching Models (`flow-matching-models`) - not_novel: Flow matching is an established architecture family and not a novel concept introduced by this paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.20288)
- [PDF](https://arxiv.org/pdf/2610.20288)

