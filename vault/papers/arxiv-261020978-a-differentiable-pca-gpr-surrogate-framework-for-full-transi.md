---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A differentiable PCA-GPR surrogate framework for full-transient Bayesian inverse uncertainty quantification of black-box nuclear thermal-hydraulic systems"
description: "The paper introduces a differentiable surrogate-assisted framework for Bayesian Inverse Uncertainty Quantification (IUQ) of transient energy systems, specifically targeting nuclear thermal-hydraulics. By combining Principal Component Analysis (PCA) for dimensionality reduction of time-series outputs with Gaussian Process Regression (GPR), the authors create an emulator that preserves temporal correlations while enabling automatic differentiation of the log-posterior. This differentiability allows for the application of efficient gradient-informed samplers like NUTS, resulting in a 3000-fold speedup in likelihood evaluations compared to the high-fidelity Flownex SE simulator while maintaining high predictive accuracy (<2% NRMSE)."
resource: "https://arxiv.org/abs/2610.20978"
tags:
  - "uncertainty-quantification"
  - "bayesian-inference"
  - "surrogate-modeling"
  - "gaussian-processes"
  - "principal-component-analysis"
  - "differentiable-programming"
  - "energy-systems"
  - "time-series"
  - "physics-informed-machine-learning"
  - "mcmc"
timestamp: "2026-10-18T00:26:53Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Zikang Yaoa"
  - literal: "Eugene Yeea"
  - literal: "Fue-Sang Lien"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20978"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "pca-gpr-surrogate-framework"
    description: "A differentiable surrogate modeling approach that couples Principal Component Analysis for dimensionality reduction of time-series outputs with Gaussian Process Regression to enable gradient-based Bayesian inference."
datasets:
  []
open_questions:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:26:53Z"
created_at: "2026-10-18T00:26:53Z"
---

# A differentiable PCA-GPR surrogate framework for full-transient Bayesian inverse uncertainty quantification of black-box nuclear thermal-hydraulic systems

**Authors**: Zikang Yaoa, Eugene Yeea, Fue-Sang Lien
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20978](https://arxiv.org/abs/2610.20978)

## Summary

The paper introduces a differentiable surrogate-assisted framework for Bayesian Inverse Uncertainty Quantification (IUQ) of transient energy systems, specifically targeting nuclear thermal-hydraulics. By combining Principal Component Analysis (PCA) for dimensionality reduction of time-series outputs with Gaussian Process Regression (GPR), the authors create an emulator that preserves temporal correlations while enabling automatic differentiation of the log-posterior. This differentiability allows for the application of efficient gradient-informed samplers like NUTS, resulting in a 3000-fold speedup in likelihood evaluations compared to the high-fidelity Flownex SE simulator while maintaining high predictive accuracy (<2% NRMSE).

## Key Contributions

- Developed a differentiable PCA-GPR surrogate framework that transforms high-fidelity black-box transient simulators into probabilistic emulators capable of providing gradients for Bayesian inference.
- Achieved a 3000-fold reduction in likelihood evaluation cost compared to direct simulator execution while maintaining posterior accuracy and reducing prediction bias.
- Demonstrated that five principal components are sufficient to capture 99% of output variance in complex multi-channel temperature and flow histories, enabling compact latent representation of transient data.
- Integrated the surrogate with gradient-informed samplers including NUTS and Microcanonical Langevin Monte Carlo to perform full-time-series calibration of nuclear thermal-hydraulic systems.

## Limitations

The framework's performance depends on the ability of PCA to capture dominant dynamics in a low-dimensional space; highly non-linear or discontinuous transients might require more complex latent representations.

## Key Concepts

- [[pca-gpr-surrogate-framework]]: A differentiable surrogate modeling approach that couples Principal Component Analysis for dimensionality reduction of time-series outputs with Gaussian Process Regression to enable gradient-based Bayesian inference.

## Archivist Review

Approved the PCA-GPR surrogate framework as it represents a core, reusable methodological pattern for making complex simulators differentiable for Bayesian inference. Rejected the dataset and open questions as they were either specific to a single experimental setup or addressed generic ML scaling challenges rather than paper-specific theoretical bottlenecks.

### Approved Concepts
- PCA-GPR Surrogate Framework: Enables the use of gradient-informed Bayesian samplers (like NUTS) on black-box, high-fidelity transient simulators by providing a differentiable mapping from parameters to latent output space.

### Rejected Candidates
- [dataset] NACIE loop data (`nacie-loop-data`) - paper_local: The NACIE data is specific to a particular physical experimental facility and is not presented as a reusable, general-purpose machine learning benchmark.
- [open_question] Scaling Limits of Differentiable Surrogates (`high-dimensional-surrogate-scaling-limits`) - generic: Scaling to higher-dimensional input spaces is a generic challenge for all surrogate models and Gaussian processes, not a specific unresolved mechanism introduced by this framework.
- [concept] Inverse Uncertainty Quantification (IUQ) (`inverse-uncertainty-quantification`) - not_novel: IUQ is a standard statistical practice and not a novel architecture or technique introduced by this paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.20978)
- [PDF](https://arxiv.org/pdf/2610.20978)

