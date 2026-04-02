---
# CSL-compatible fields
title: "LAtent Phase Inference from Short time sequences using SHallow REcurrent Decoders (LAPIS-SHRED)"
author:
  - literal: "Yuxuan Bao"
  - literal: "Xingyue Zhang"
  - literal: "J. Nathan Kutz"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.01216"

# Custom fields
paper_id: "2604.01216"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting-horizon"
  - "irregular-time-step-forecasting"
  - "physics-spatiotemporal-masked-autoencoder"
architectures:
  []
datasets:
  []
concept_slugs:
  - "lapis-shred"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-02T05:36:42Z"
created_at: "2026-04-02T05:36:42Z"
---

# LAtent Phase Inference from Short time sequences using SHallow REcurrent Decoders (LAPIS-SHRED)

**Authors**: Yuxuan Bao, Xingyue Zhang, J. Nathan Kutz
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.01216](https://arxiv.org/abs/2604.01216)

## Summary

LAPIS-SHRED is a modular framework designed to reconstruct full spatio-temporal dynamics from hyper-sparse, short-window sensor observations. The method employs a three-stage pipeline involving pre-trained latent space mapping and temporal state propagation to overcome limitations in observational data. By leveraging simulation-trained models and modular decoders, the framework enables robust inference in scenarios ranging from turbulent flows to satellite-derived environmental fields. LAPIS-SHRED supports bidirectional trajectory reconstruction and is specifically tailored for operational settings with extreme physical or logistical observational constraints.

## Key Contributions

- Introduces LAPIS-SHRED, a three-stage modular framework for reconstructing and forecasting high-dimensional spatio-temporal dynamics from sparse, short-window sensor inputs.
- Demonstrates bidirectional inference capabilities allowing for both past and future state reconstruction from limited observations.
- Validates the model across six diverse complex systems including turbulent flows, combustion, and satellite environmental fields, showing effectiveness in extreme observational scenarios.

## Open Questions & Future Work

- [[backward-inference-chaotic-stability]]
- [[temporal-inference-data-assimilation-integration]]

## Key Concepts

- [[lapis-shred]]: A three-stage modular framework that reconstructs complete spatio-temporal dynamics from hyper-sparse, short-window sensor observations by coupling latent space mapping with temporal state propagation.

## Archivist Review

Approved LAPIS-SHRED as a notable example of a modular, simulation-to-reality pipeline for spatio-temporal forecasting. Open questions focus on the stability of backward inference in chaotic regimes and the integration of data assimilation with latent temporal models to address the simulation-to-reality gap. Rejected no candidates as none were provided in the input besides the ones approved.

### Approved Concepts
- LAPIS-SHRED: Introduces a three-stage modular pipeline (latent mapping + temporal propagation) for spatio-temporal reconstruction that effectively handles extreme observational scarcity.

### Approved Open Questions
- Backward Inference in Chaotic Systems: Formalizing error bounds in chaotic regimes is essential for the reliability of inverse spatio-temporal modeling in physical sciences.
- Temporal Inference-Data Assimilation Integration: This addresses the fundamental simulation-to-reality gap in physics-informed machine learning, enabling model adaptation to real-world sensor feedback.

## Links

- [Abstract](https://arxiv.org/abs/2604.01216)
- [PDF](https://arxiv.org/pdf/2604.01216)

