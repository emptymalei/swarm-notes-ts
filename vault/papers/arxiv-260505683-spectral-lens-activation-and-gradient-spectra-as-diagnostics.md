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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "spectral-lens-diagnostic-protocol"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-10T05:21:05Z"
created_at: "2026-05-10T05:21:05Z"
---

# Spectral Lens: Activation and Gradient Spectra as Diagnostics of LLM Optimization

**Authors**: Andy Zeyi Liu, Elliot Paquette, John Sous
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05683](https://arxiv.org/abs/2605.05683)

## Summary

This paper introduces the Spectral Lens, a diagnostic protocol that utilizes activation covariance and gradient SVD spectra to analyze LLM training mechanics. By applying this protocol to a controlled family of decoder-only models, the authors reveal that batch size shapes representation geometry even when training loss is identical. The framework further enables the prediction of downstream token efficiency using early-training spectral signals and distinguishes between architecture-driven and execution-driven learning improvements.

## Key Contributions

- Introduces the Spectral Lens protocol, which uses activation covariance and per-sample gradient SVD spectra to diagnose internal LLM training dynamics.
- Demonstrates that batch size acts as a latent determinant of representation geometry, causing models with identical loss to have distinct internal spectra.
- Establishes that the activation covariance tail measured early in training predicts downstream token efficiency across varying model scales.

## Open Questions & Future Work

- [[spectral-diagnostics-downstream-predictivity]]
- [[automatic-spectral-boundary-detection]]

## Key Concepts

- [[spectral-lens-diagnostic-protocol]]: A diagnostic protocol using activation covariance and gradient SVD spectra to measure LLM optimization dynamics and representational geometry.

## Archivist Review

I have approved the core diagnostic protocol as a reusable analytical framework for LLM training. I have also approved the two open questions because they identify clear bottlenecks in the scalability and practical downstream utility of using spectral diagnostics for model monitoring. No datasets were approved as none were presented as critical, novel, or unique to this specific study.

### Approved Concepts
- Spectral Lens Diagnostic Protocol: It provides a novel, dual-view diagnostic framework for analyzing LLM optimization dynamics beyond simple loss curves.

### Approved Open Questions
- Spectral Predictivity for Downstream Performance: This is critical for practitioners who are ultimately interested in the downstream utility of a model rather than the proxy metric of pretraining loss.
- Automated Spectral Boundary Detection: Developing automated boundary detection would turn a manual diagnostic protocol into a scalable, plug-and-play tool for training monitoring.

## Links

- [Abstract](https://arxiv.org/abs/2605.05683)
- [PDF](https://arxiv.org/pdf/2605.05683)

