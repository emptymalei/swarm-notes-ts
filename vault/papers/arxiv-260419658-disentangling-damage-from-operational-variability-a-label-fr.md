---
# CSL-compatible fields
title: "Disentangling Damage from Operational Variability: A Label-Free Self-Supervised Representation Learning Framework for Output-Only Structural Damage Identification"
author:
  - literal: "Xudong Jian"
  - literal: "Charikleia Stoura"
  - literal: "Simon Scandella"
  - literal: "Eleni Chatzi"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19658"

# Custom fields
paper_id: "2604.19658"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "self-supervised-learning"
  - "structural-health-monitoring"
  - "anomaly-detection"
  - "disentangled-representation-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "label-free-structural-damage-identification"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:03:04Z"
created_at: "2026-04-22T05:03:04Z"
---

# Disentangling Damage from Operational Variability: A Label-Free Self-Supervised Representation Learning Framework for Output-Only Structural Damage Identification

**Authors**: Xudong Jian, Charikleia Stoura, Simon Scandella, Eleni Chatzi
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19658](https://arxiv.org/abs/2604.19658)

## Summary

This paper introduces a label-free, self-supervised framework for structural health monitoring that disentangles damage-related signals from operational and environmental variability. By utilizing an autoencoder with Variance-Invariance-Covariance Regularization (VICReg) and a frequency-domain reconstruction constraint, the model learns latent representations invariant to nuisance conditions. The approach effectively isolates damage characteristics from vibration acceleration signals without requiring labeled training data. Validation on real-world bridge and gearbox vibration datasets demonstrates the framework's strong performance in both damage detection and quantification.

## Key Contributions

- Proposes a self-supervised autoencoder framework that uses VICReg to enforce invariance to nuisance operational/environmental variability in vibration signals.
- Introduces a frequency-domain constraint to ensure latent representations maintain spectral information, facilitating effective disentanglement of damage-sensitive features.
- Achieves robust damage detection and quantification on real-world bridge and gearbox datasets without requiring prior labels for damage or environmental conditions.

## Open Questions & Future Work

- [[improving-weak-damage-detection-quantification]]

## Key Concepts

- [[label-free-structural-damage-identification]]: A self-supervised representation learning framework using VICReg and frequency-domain constraints to isolate damage features from environmental noise in structural vibrations.

## Archivist Review

I have approved the core methodological framework as a reusable concept for disentangling nuisance variability from signal representations. The open question regarding weak damage detection identifies a non-trivial, domain-agnostic limitation in unsupervised diagnostic tasks. No datasets were approved as the candidates were generic or not sufficiently specific.

### Approved Concepts
- Label-Free Structural Damage Identification: Addresses the critical problem of disentangling structural damage from non-damage-related operational/environmental variability without labels.

### Approved Open Questions
- Improving weak damage detection: These areas address the fundamental limitations of the current framework in handling subtle, early-stage damage and the inherent noise/uncertainty in real-world structural data, which are critical for the practical deployment of autonomous SHM systems.

## Links

- [Abstract](https://arxiv.org/abs/2604.19658)
- [PDF](https://arxiv.org/pdf/2604.19658)

