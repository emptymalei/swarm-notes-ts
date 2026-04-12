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
domain: "time-series"
tags:
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-12T05:02:07Z"
created_at: "2026-04-12T05:02:07Z"
---

# LITE: Lightweight Channel Gain Estimation with Reduced X-Haul CSI Signaling in O-RAN

**Authors**: David Goez, Marco Piazzola, Giulia Costa, Achiel Colpaert, Rodney Martinez Alonso, Esra Aycan Beyazit, Nina Slamnik-Krijestorac, Johann M. Marquez-Barja, Miguel Camelo Botero
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08458](https://arxiv.org/abs/2604.08458)

## Summary

LITE addresses the bandwidth constraints in Cell-Free Massive MIMO by enabling lightweight channel state information (CSI) forecasting within the Open Radio Access Network (O-RAN). By combining a 1-D convolutional Autoencoder for CSI compression with an SE-enhanced BiLSTM predictor, the system significantly reduces X-haul signaling requirements. Experimental results show that LITE optimizes both model complexity and throughput, offering a deployable, high-efficiency solution for real-time channel gain estimation.

## Key Contributions

- Proposes LITE, a pipeline combining a 1-D CNN Autoencoder and an SE-enhanced BiLSTM, which achieves 50% CSI compression for X-haul signaling reduction.
- Demonstrates 83.39% reduction in model complexity compared to standard BiLSTM models while improving prediction accuracy by 5%.
- Provides a TensorRT-optimized implementation achieving 147k Queries per Second (QPS), representing a 4.6x throughput gain for O-RAN deployments.

## Open Questions & Future Work

- [[adaptive-csi-compression-prediction-o-ran]]

## Archivist Review

The paper presents a system-level optimization for O-RAN channel prediction. I have rejected the specific LITE pipeline as it functions as a collection of established architectural modules (CNN-AE, BiLSTM) rather than a reusable core mechanism. I have approved a refined version of the open question regarding adaptive CSI compression, as it highlights a significant architectural bottleneck in wireless communication systems.

### Approved Open Questions
- Adaptive CSI Compression Prediction: Evaluating performance on real traces and enabling adaptive compression-prediction trade-offs are critical for transitioning from laboratory models to deployment-ready O-RAN systems.

### Rejected Candidates
- [concept] Lightweight Intelligent Trajectory Estimator (LITE) (`lightweight-intelligent-trajectory-estimator-lite`) - paper_local: This is a paper-specific system pipeline that combines standard components; the underlying design pattern is too granular for a standalone concept note.

## Links

- [Abstract](https://arxiv.org/abs/2604.08458)
- [PDF](https://arxiv.org/pdf/2604.08458)

