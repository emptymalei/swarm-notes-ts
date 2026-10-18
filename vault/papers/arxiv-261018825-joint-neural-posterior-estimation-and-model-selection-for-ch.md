---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Joint Neural Posterior Estimation and Model Selection for Chemical Reaction Networks"
description: "The paper presents a neural simulation-based inference (SBI) framework designed for Chemical Reaction Networks (CRNs) to solve the dual challenges of pathway discrimination and kinetic parameter estimation. The architecture employs a shared 1D-CNN and Set Attention mechanism to extract summary statistics from multi-experiment time-series data, which are then used to condition both a model-selection classifier and model-specific conditional Invertible Neural Networks (cINNs). This approach allows for rapid, amortized Bayesian inference, resolving structural ambiguities in competing catalyst deactivation pathways that are typically intractable for classical Sequential Monte Carlo methods."
resource: "https://arxiv.org/abs/2610.18825"
tags:
  - "simulation-based-inference"
  - "bayesian-inference"
  - "time-series-analysis"
  - "scientific-machine-learning"
  - "parameter-estimation"
  - "attention-mechanism"
  - "uncertainty-quantification"
  - "model-selection"
timestamp: "2026-10-18T00:53:45Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "J. Arturo Esquivel"
  - literal: "Jorge A. Campos-Gonzalez-Angulo"
  - literal: "Sergio Pablo-García"
  - literal: "Alán Aspuru-Guzik"
  - literal: "Vianey Leos-Barajas"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18825"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "joint-npe-model-selection"
    description: "An amortized inference framework that uses shared neural representations to simultaneously perform Bayesian model selection and parameter posterior estimation for complex dynamical systems."
datasets:
  []
open_questions:
  - name: "structural-unidentifiability-neural-inference"
    description: "How can amortized neural inference architectures be designed to explicitly detect, quantify, or resolve structural unidentifiability in high-dimensional systems, rather than just returning broad or multimodal posteriors?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:53:45Z"
created_at: "2026-10-18T00:53:45Z"
---

# Joint Neural Posterior Estimation and Model Selection for Chemical Reaction Networks

**Authors**: J. Arturo Esquivel, Jorge A. Campos-Gonzalez-Angulo, Sergio Pablo-García, Alán Aspuru-Guzik, Vianey Leos-Barajas
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18825](https://arxiv.org/abs/2610.18825)

## Summary

The paper presents a neural simulation-based inference (SBI) framework designed for Chemical Reaction Networks (CRNs) to solve the dual challenges of pathway discrimination and kinetic parameter estimation. The architecture employs a shared 1D-CNN and Set Attention mechanism to extract summary statistics from multi-experiment time-series data, which are then used to condition both a model-selection classifier and model-specific conditional Invertible Neural Networks (cINNs). This approach allows for rapid, amortized Bayesian inference, resolving structural ambiguities in competing catalyst deactivation pathways that are typically intractable for classical Sequential Monte Carlo methods.

## Key Contributions

- Introduced a joint neural simulation-based inference (SBI) pipeline that simultaneously computes posterior model probabilities and model-specific parameter distributions for Chemical Reaction Networks.
- Developed a multi-experiment encoder utilizing shared 1D-CNNs and a Set Attention mechanism to process variable-length time-series data into permutation-invariant summary statistics.
- Applied conditional Invertible Neural Networks (cINNs) to the problem of kinetic parameter estimation, bypassing the need for manually engineered summary statistics in chemical kinetics.
- Demonstrated the resolution of structural ambiguity in catalyst deactivation pathways for protodeboronation, a task that typically scales poorly with traditional ABC methods.

## Limitations

The scaling of the model selection component as the number of possible reaction pathways (models) grows very large was not extensively detailed.

## Open Questions & Future Work

- [[structural-unidentifiability-neural-inference]]

## Key Concepts

- [[joint-npe-model-selection]]: An amortized inference framework that uses shared neural representations to simultaneously perform Bayesian model selection and parameter posterior estimation for complex dynamical systems.

## Archivist Review

The approved concept highlights the integration of model selection and posterior estimation in SBI, a critical pattern for scientific modeling. The open question addresses the core issue of structural unidentifiability in neural architectures, which is a major bottleneck for trust in automated scientific discovery. Standard components and local chemical examples were excluded to ensure the vault contains high-level, reusable ML concepts.

### Approved Concepts
- Joint Neural Posterior Estimation and Model Selection: Scientific discovery often requires choosing between multiple competing physical mechanisms while simultaneously estimating their parameters; this framework provides an amortized solution for both.

### Approved Open Questions
- Quantifying Unidentifiability in Neural Inference: Reliable scientific inference requires knowing if a model is uniquely identified by the data; failure to detect unidentifiability leads to physically incorrect conclusions even if numerical fit is high.

### Rejected Candidates
- [concept] Neural Posterior Estimation (`neural-posterior-estimation`) - not_novel: NPE is a well-established technique in the Simulation-Based Inference (SBI) community and does not originate with this paper.
- [dataset] Protodeboronation Example (`protodeboronation-dataset`) - paper_local: This is a specific chemical application case study used for demonstration rather than a reusable benchmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2610.18825)
- [PDF](https://arxiv.org/pdf/2610.18825)

