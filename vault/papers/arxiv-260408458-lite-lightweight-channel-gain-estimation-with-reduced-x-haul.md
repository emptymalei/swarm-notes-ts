---
# CSL-compatible fields
title: "LITE: Lightweight Channel Gain Estimation with Reduced X-Haul CSI Signaling in O-RAN"
author:
  - literal: "David Goez"
  - literal: "Marco Piazzola"
  - literal: "Giulia Costa"
  - literal: "Achiel Colpaert"
  - literal: "Rodney Martinez Alonso"
  - literal: "Esra Aycan Beyazit"
  - literal: "Nina Slamnik-Krijestorac"
  - literal: "Johann M. Marquez-Barja"
  - literal: "Miguel Camelo Botero"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08458"

# Custom fields
paper_id: "2604.08458"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:43:30Z"
created_at: "2026-04-11T04:43:30Z"
---

# LITE: Lightweight Channel Gain Estimation with Reduced X-Haul CSI Signaling in O-RAN

**Authors**: David Goez, Marco Piazzola, Giulia Costa, Achiel Colpaert, Rodney Martinez Alonso, Esra Aycan Beyazit, Nina Slamnik-Krijestorac, Johann M. Marquez-Barja, Miguel Camelo Botero
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08458](https://arxiv.org/abs/2604.08458)

## Summary

LITE is a lightweight CSI forecasting pipeline designed for Cell-Free Massive MIMO in O-RAN environments to mitigate X-haul bandwidth congestion. The framework integrates a 1D-convolutional autoencoder for 50% data compression with an asymmetric Squeeze-and-Excitation (SE)-enhanced BiLSTM for channel gain prediction. By optimizing for both transport efficiency and inference latency, LITE provides a deployment-ready solution that significantly outperforms baseline approaches in model complexity and throughput while maintaining high predictive accuracy.

## Key Contributions

- Introduces LITE, a lightweight pipeline for channel state information (CSI) forecasting in O-RAN that enables 50% CSI compression for reduced X-haul signaling.
- Achieves an 83.39% reduction in model complexity compared to standard BiLSTM baselines through an asymmetric SE-BiLSTM architecture.
- Demonstrates a 4.6x throughput gain and 147k Queries per Second (QPS) performance using a TensorRT-optimized deployment.

## Open Questions & Future Work

- [[adaptive-csi-compression-prediction-o-ran]]
- [[model-efficiency-for-ran-controllers]]

## Archivist Review

I have approved the two open questions as they address the critical and non-trivial challenge of balancing transport-layer constraints (signaling/X-haul) with predictive performance in real-time RAN environments. The proposed concept of 'LITE' was rejected as it represents a specific pipeline configuration rather than a fundamentally new, reusable architectural primitive suitable for the vault.

### Approved Open Questions
- Adaptive CSI Compression Optimization: Optimizing the balance between compression and prediction is critical for scaling Cell-Free Massive MIMO in O-RAN, as fixed-ratio compression may be suboptimal under fluctuating network conditions.
- Efficient Model Deployment Methods: This is essential for the practical, large-scale deployment of AI-based channel prediction in resource-constrained edge computing environments.

### Rejected Candidates
- [concept] LITE (Lightweight Intelligent Trajectory Estimator) (`lite-architecture`) - paper_local: The LITE architecture is a paper-local integration of existing modules (autoencoder and SE-BiLSTM) rather than a novel, reusable algorithmic paradigm.

## Links

- [Abstract](https://arxiv.org/abs/2604.08458)
- [PDF](https://arxiv.org/pdf/2604.08458)

