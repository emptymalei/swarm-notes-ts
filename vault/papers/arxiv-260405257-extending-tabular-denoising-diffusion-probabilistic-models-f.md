---
# CSL-compatible fields
title: "Extending Tabular Denoising Diffusion Probabilistic Models for Time-Series Data Generation"
author:
  - literal: "Umang Dobhal"
  - literal: "Christina Garcia"
  - literal: "Sozo Inoue"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.05257"

# Custom fields
paper_id: "2604.05257"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "temporal-tabddpm-adapters"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:56:51Z"
created_at: "2026-04-08T04:56:51Z"
---

# Extending Tabular Denoising Diffusion Probabilistic Models for Time-Series Data Generation

**Authors**: Umang Dobhal, Christina Garcia, Sozo Inoue
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.05257](https://arxiv.org/abs/2604.05257)

## Summary

This paper introduces a temporal extension of Tabular Denoising Diffusion Probabilistic Models (TabDDPM) to facilitate the generation of synthetic time-series data. By incorporating lightweight temporal adapters and context-aware embedding modules, the proposed method successfully models dependencies in windowed sensor sequences that standard tabular diffusion models typically ignore. Evaluation on the WISDM accelerometer dataset indicates that the approach produces high-fidelity, coherent sequences that preserve the statistical properties of the original data while enabling effective downstream classification.

## Key Contributions

- Introduces temporal adapters and context-aware embedding modules to extend TabDDPM for sequential sensor data synthesis.
- Demonstrates enhanced temporal realism and statistical alignment over traditional baseline interpolation techniques via autocorrelation analysis.
- Achieves a 0.64 macro F1-score and 0.71 accuracy on the WISDM dataset using synthetic samples, showing viability for privacy-preserving data augmentation.

## Open Questions & Future Work

- [[scaling-diffusion-long-sequences]]

## Key Concepts

- [[temporal-tabddpm-adapters]]: Lightweight architectural modules designed to inject temporal dependency awareness into standard TabDDPM architectures for sequential data synthesis.

## Archivist Review

I approved the core architectural concept of temporal adapters for tabular diffusion models, as this is a specific, reusable approach to a known research problem. I also approved the open question regarding scaling diffusion to long sequences, as it addresses a fundamental technical limitation in time-series generative modeling. The candidate regarding HAR model generalization was rejected as generic, as it applies to virtually any empirical research paper rather than identifying a specific unresolved challenge.

### Approved Concepts
- Temporal TabDDPM Adapters: Core mechanism enabling the adaptation of independent-sample tabular diffusion models to coherent time-series generation.

### Approved Open Questions
- Scaling Diffusion for Sequences: Scalability is a critical bottleneck for deploying diffusion models in real-world time-series applications where long-range dependencies are essential.

### Rejected Candidates
- [open_question] Generalizing Generative HAR Models (`generalizing-generative-har-models`) - generic: The need for broader validation is a generic requirement for almost all empirical ML papers and does not represent a specific, unresolved mechanistic or theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.05257)
- [PDF](https://arxiv.org/pdf/2604.05257)

