---
created_at: '2026-05-10T05:19:37Z'
source_papers:
- '[[arxiv-260505975-physical-fidelity-reconstruction-via-improved-consistency-di]]'
title: Scalability of One-Step Reconstruction
---

**Background:** Physical fidelity reconstruction involves generating high-resolution fields from low-resolution observations by sampling from a conditional posterior distribution, a process typically performed using multi-step iterative generative models. Efficient one-step generative approaches, such as consistency distillation, have been successfully applied to natural image tasks but their performance and training stability in the context of scientific data with multi-scale physical structures remain to be fully characterized.

**Question / Future Work:** While this framework demonstrates that consistency distillation can achieve effective one-step physical fidelity reconstruction, it is currently limited to two-dimensional, statistically stationary fields. The conditioning mechanism relies on the assumption that upsampled low-resolution inputs are well-approximated by on-trajectory optimal transport states, and there is significant potential to investigate the extension of this distillation approach to three-dimensional turbulence, non-stationary boundary conditions, and sparse or unstructured observational data.

**Why It Matters:** This direction is critical for determining the scalability of one-step generative models to the complex, high-dimensional, and non-stationary conditions frequently encountered in practical scientific simulation and ensemble forecasting workflows.