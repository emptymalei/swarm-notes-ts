---
# CSL-compatible fields
title: "Beyond Patient Invariance: Learning Cardiac Dynamics via Action-Conditioned JEPAs"
author:
  - literal: "Jose Geraldo Fernandes"
  - literal: "Luiz Facury"
  - literal: "Pedro Robles Dutenhefner"
  - literal: "Wagner Meira"
issued:
  date-parts:
    - [2026, 4, 24]
url: "https://arxiv.org/abs/2604.22618"

# Custom fields
paper_id: "2604.22618"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "time-series-forecasting"
  - "self-supervised-learning"
  - "healthcare-ai"
  - "representation-learning"
  - "world-models"
architectures:
  []
datasets:
  - "mimic-iv-ecg"
concept_slugs:
  - "action-conditioned-world-model"
dataset_slugs:
  - "mimic-iv-ecg"
skill: "TimeSeriesSkill"
processed_at: "2026-04-27T05:10:52Z"
created_at: "2026-04-27T05:10:52Z"
---

# Beyond Patient Invariance: Learning Cardiac Dynamics via Action-Conditioned JEPAs

**Authors**: Jose Geraldo Fernandes, Luiz Facury, Pedro Robles Dutenhefner, Wagner Meira
**Date**: 2026-04-24
**Paper ID**: [arxiv:2604.22618](https://arxiv.org/abs/2604.22618)

## Summary

This paper addresses the limitation of current invariance-based self-supervised learning in healthcare, which suppresses transient pathological signals. The authors propose an action-conditioned world model that simulates disease progression by treating pathology as a transition vector in latent space. By explicitly modeling future electrophysiological states given a disease onset, the framework improves clinical triage and sample efficiency in low-resource settings. Experiments on the MIMIC-IV-ECG dataset demonstrate that capturing biological dynamics offers a more robust supervision signal than static classification.

## Key Contributions

- Proposes an Action-Conditioned Joint-Embedding Predictive Architecture (JEPAs) for learning physiological disease dynamics.
- Introduces a representation of pathology as a transition vector in the latent state space, explicitly disentangling anatomy from disease progression.
- Achieves superior performance over fully supervised baselines on clinical triage tasks using the MIMIC-IV-ECG dataset, especially in low-data regimes.

## Open Questions & Future Work

- [[modeling-disease-irreversibility-temporal-asymmetry]]

## Key Concepts

- [[action-conditioned-world-model]]: A framework for simulating physiological transitions by conditioning latent state evolution on specific medical events or interventions.

## Archivist Review

The paper provides a significant advancement by framing pathology as a transition vector rather than a static label, moving beyond traditional invariance-based SSL. I approved the core conceptual framework of the action-conditioned world model as it is a highly reusable paradigm for physiological time-series modeling. I also approved the open question regarding disease irreversibility, as it highlights a specific, non-boilerplate research bottleneck in latent dynamic modeling. The MIMIC-IV-ECG dataset is included as a primary site of the study's empirical evidence.

### Approved Concepts
- Action-Conditioned World Model: Central to shifting the paradigm from static patient invariance to dynamic disease modeling in physiological time-series.

### Approved Open Questions
- Modeling Disease Progression Irreversibility: Addressing temporal irreversibility is essential for building clinically accurate simulators that can perform valid counterfactual reasoning, which is limited by the current reliance on models that struggle with the distinction between reversible and irreversible pathologies.

## Datasets

- [[mimic-iv-ecg]]

## Links

- [Abstract](https://arxiv.org/abs/2604.22618)
- [PDF](https://arxiv.org/pdf/2604.22618)

