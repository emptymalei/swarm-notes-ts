---
# CSL-compatible fields
title: "Spatiotemporal System Forecasting with Irregular Time Steps via Masked Autoencoder"
author:
  - literal: "Kewei Zhu"
  - literal: "Yanze Xin"
  - literal: "Jinwei Hu"
  - literal: "Xiaoyuan Cheng"
  - literal: "Yiming Yang"
  - literal: "Sibo Cheng"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25597"

# Custom fields
paper_id: "2603.25597"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series forecasting"
  - "self-supervised learning"
  - "deep generative models"
  - "scientific computing"
architectures:
  - "Masked Autoencoder"
  - "Autoencoder"
datasets:
  []
concept_slugs:
  - "physics-spatiotemporal-masked-autoencoder"
  - "irregular-time-step-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:15:47Z"
created_at: "2026-03-29T20:15:47Z"
---

# Spatiotemporal System Forecasting with Irregular Time Steps via Masked Autoencoder

**Authors**: Kewei Zhu, Yanze Xin, Jinwei Hu, Xiaoyuan Cheng, Yiming Yang, Sibo Cheng
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25597](https://arxiv.org/abs/2603.25597)

## Summary

This paper introduces the Physics-Spatiotemporal Masked Autoencoder (PS-MAE) to tackle the challenge of forecasting high-dimensional dynamical systems sampled at irregular time intervals, a common issue arising from sparse or missing observations. The architecture combines convolutional autoencoders for spatial feature extraction with masked autoencoder principles optimized for non-uniform sequences, using attention mechanisms to reconstruct the complete system state in one pass. By avoiding explicit data imputation, the model preserves the system's physical integrity while capturing complex spatiotemporal patterns effectively. Evaluation against traditional recurrent and convolutional methods across simulated and real-world ocean temperature data showed superior prediction accuracy and robustness.

## Key Contributions

- Proposed the Physics-Spatiotemporal Masked Autoencoder (PS-MAE) which integrates convolutional autoencoders for spatial features and MAE for irregular time series reconstruction.
- Achieved significant improvements in prediction accuracy and robustness to nonlinearities over traditional convolutional and recurrent methods on simulated and real-world datasets.
- Model successfully reconstructs the entire physical sequence in a single prediction pass without requiring explicit data imputation.
- Demonstrated applicability to high-dimensional dynamical systems, showing potential for climate modelling and fluid dynamics applications.

## Limitations

The abstract does not detail explicit limitations, but mentions the focus on 'physics' as high-dimensional fields rather than explicit PDE enforcement.

## Open Questions & Future Work

- [[transformer-quadratic-complexity-scalability]]
- [[multi-objective-optimization-structural-fidelity]]
- [[advanced-positional-embeddings-irregular-time]]

## Key Concepts

- [[physics-spatiotemporal-masked-autoencoder]]: A Masked Autoencoder framework adapted for spatiotemporal forecasting with irregular time steps, leveraging convolutions for spatial features and attention for sequence reconstruction.
- [[irregular-time-step-forecasting]]: Forecasting or modeling of time series data where the intervals between observations are non-uniform, variable, or sparse.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 2 concept(s), 3 open question(s), and 0 dataset(s), with 2 rejected candidate note(s).

### Approved Concepts
- Physics-Spatiotemporal Masked Autoencoder (PS-MAE): This is the central novel architecture proposed to handle irregular time series forecasting by combining MAE principles with spatiotemporal feature extraction.
- Irregular Time Step Forecasting: The core problem addressed by the paper, which is a significant challenge in scientific machine learning that requires specialized architectural solutions.

### Approved Open Questions
- Scalable Attention for Long Sequences: Scaling self-attention is a critical bottleneck for applying transformer-based sequence models, like P-STMAE, to very long time series data common in long-term climate forecasting.
- Multi-Objective Optimization for Structure: Balancing point-wise accuracy (MSE) with global structural preservation (SSIM/PSNR) is a fundamental and persistent challenge in scientific machine learning forecasting.
- Advanced Positional Embeddings for Irregularity: Positional encodings are crucial for transformers on sequences, and adapting them for irregular time series—where standard methods can fail—is key to improving temporal modeling fidelity.

### Rejected Candidates
- [open_question] Advanced Spatial Encoding Fidelity (`advanced-spatial-encoding-for-latent-space`) - paper_local: This is a specific extension of the current architecture (replacing the CAE with VAE/ViT) rather than a fundamental, reusable problem in the domain.
- [open_question] Broader Real-World Validation (`broad-validation-real-world-datasets`) - low_impact: This is boilerplate future work—requesting more experiments/data validation—and does not describe a specific, unresolved technical mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2603.25597)
- [PDF](https://arxiv.org/pdf/2603.25597)

