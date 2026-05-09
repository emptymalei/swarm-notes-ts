---
# CSL-compatible fields
title: "Spectral Lens: Activation and Gradient Spectra as Diagnostics of LLM Optimization"
author:
  - literal: "Andy Zeyi Liu"
  - literal: "Elliot Paquette"
  - literal: "John Sous"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05683"

# Custom fields
paper_id: "2605.05683"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "llm-optimization"
  - "training-dynamics"
  - "representation-analysis"
  - "interpretability"
  - "spectral-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "spectral-lens-diagnostic-protocol"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-09T05:13:00Z"
created_at: "2026-05-09T05:13:00Z"
---

# Spectral Lens: Activation and Gradient Spectra as Diagnostics of LLM Optimization

**Authors**: Andy Zeyi Liu, Elliot Paquette, John Sous
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05683](https://arxiv.org/abs/2605.05683)

## Summary

This paper introduces Spectral Lens, a diagnostic framework using activation covariance and gradient SVD spectra to reveal the hidden mechanics of LLM training dynamics. By analyzing these spectral measurements, the authors demonstrate that training runs with identical losses often exhibit distinct representation geometries influenced by batch size. Furthermore, they establish that early-stage spectral signatures successfully predict downstream token efficiency and distinguish between architectural and execution-side performance gains. The work also provides a theoretical model that links these spectral dynamics to the process of task-aligned feature learning.

## Key Contributions

- Introduces Spectral Lens, a diagnostic protocol for LLM training based on activation covariance and per-sample gradient SVD spectra.
- Demonstrates that batch size significantly alters representation geometry, even in models that achieve identical final training loss.
- Establishes that the tail of the activation covariance spectrum early in training acts as a reliable predictor for long-term downstream token efficiency.
- Provides a mechanistic model explaining the observed correlation between activation covariance spectra and the acquisition of task-aligned features.

## Open Questions & Future Work

- [[spectral-downstream-predictivity]]
- [[spectral-moe-generalization]]

## Key Concepts

- [[spectral-lens-diagnostic-protocol]]: An empirical diagnostic framework utilizing activation covariance and per-sample gradient SVD spectra to analyze LLM representation geometry and training progress.

## Archivist Review

I approved the Spectral Lens Diagnostic Protocol as a distinct and reusable method for training-time analysis of LLMs. The open questions regarding downstream capability prediction and MoE adaptation represent legitimate, high-level bottlenecks for applying these diagnostics beyond standard transformer pretraining.

### Approved Concepts
- Spectral Lens Diagnostic Protocol: Provides a novel, structured method for diagnosing LLM training dynamics that goes beyond loss and throughput.

### Approved Open Questions
- Downstream Capability Prediction: Validating the link between pretraining spectral signatures and downstream capabilities is essential for determining if these diagnostics are truly useful for practitioners interested in final model quality rather than just training speed.
- MoE Architecture Adaptation: MoE models have different structural characteristics and training dynamics, making it necessary to understand whether existing spectral diagnostic signatures generalize or if they require new calibration for these widespread model architectures.

## Links

- [Abstract](https://arxiv.org/abs/2605.05683)
- [PDF](https://arxiv.org/pdf/2605.05683)

