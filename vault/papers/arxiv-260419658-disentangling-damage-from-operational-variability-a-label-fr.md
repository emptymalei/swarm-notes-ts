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
  - "structural-health-monitoring"
  - "representation-learning"
  - "self-supervised-learning"
  - "vibration-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "label-free-structural-damage-identification"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:09:05Z"
created_at: "2026-04-23T05:09:05Z"
---

# Disentangling Damage from Operational Variability: A Label-Free Self-Supervised Representation Learning Framework for Output-Only Structural Damage Identification

**Authors**: Xudong Jian, Charikleia Stoura, Simon Scandella, Eleni Chatzi
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19658](https://arxiv.org/abs/2604.19658)

## Summary

This paper introduces a self-supervised, label-free framework for structural health monitoring that disentangles damage-related characteristics from operational and environmental variability. By utilizing an autoencoder with dual latent representations—regularized by Variance-Invariance-Covariance (VICReg) and a frequency-domain spectral constraint—the model learns robust features directly from raw vibration signals. The proposed approach eliminates the need for prior knowledge of damage, excitation, or environmental states, showing high performance and generalization capability on real-world bridge and gearbox datasets.

## Key Contributions

- Proposes a self-supervised disentangled representation learning framework that decouples damage-related features from operational/environmental noise.
- Introduces a frequency-domain constraint alongside VICReg regularization to align latent reconstructions with spectral characteristics of vibration data.
- Demonstrates effective damage detection and quantification on bridge and gearbox benchmarks without needing labeled data or environmental metadata.

## Open Questions & Future Work

- [[detecting-subtle-structural-damage]]
- [[reliable-structural-damage-quantification]]

## Key Concepts

- [[label-free-structural-damage-identification]]: A framework that learns robust structural damage representations from raw vibration signals without requiring damage-labeled data or environmental context.

## Archivist Review

I approved the framework as a concept because it formalizes a reusable strategy for nuisance-invariant representation learning in physical systems. The open questions were approved because they specifically address the technical hurdles of detectability and physical quantification in data-driven structural health monitoring, moving beyond general 'performance improvement' boilerplate. The datasets were rejected as generic, non-standardized descriptions of common vibration test rigs.

### Approved Concepts
- Label-free Structural Damage Identification: It addresses the critical challenge of disentangling damage signatures from confounding environmental and operational factors in structural health monitoring.

### Approved Open Questions
- Detecting subtle structural damage: Early detection of subtle structural changes is a critical bottleneck for predictive maintenance and long-term structural reliability.
- Reliable structural damage quantification: Damage quantification is necessary for transitioning from qualitative detection to actionable, decision-oriented maintenance planning.

### Rejected Candidates
- [dataset] Bridge vibration dataset (`bridge-vibration-dataset`) - low_impact: This is a generic dataset reference, not a specific named benchmark worthy of a vault entry.
- [dataset] Gearbox vibration dataset (`gearbox-vibration-dataset`) - low_impact: This is a generic dataset reference, not a specific named benchmark worthy of a vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.19658)
- [PDF](https://arxiv.org/pdf/2604.19658)

