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
processed_at: "2026-04-10T15:26:31Z"
created_at: "2026-04-10T15:26:31Z"
---

# LITE: Lightweight Channel Gain Estimation with Reduced X-Haul CSI Signaling in O-RAN

**Authors**: David Goez, Marco Piazzola, Giulia Costa, Achiel Colpaert, Rodney Martinez Alonso, Esra Aycan Beyazit, Nina Slamnik-Krijestorac, Johann M. Marquez-Barja, Miguel Camelo Botero
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08458](https://arxiv.org/abs/2604.08458)

## Summary

LITE is a lightweight pipeline designed to address X-haul bandwidth constraints in Cell-Free Massive MIMO O-RAN systems by reducing frequent CSI signaling. It employs a 1-D convolutional autoencoder at the Distributed Unit for 50% data compression and an SE-enhanced BiLSTM at the Near-RT-RIC for channel gain forecasting. The implementation achieves significant improvements in throughput and complexity reduction while maintaining competitive accuracy, making it suitable for real-time deployment in O-RAN environments.

## Key Contributions

- Proposes LITE, a pipeline for X-haul-efficient CSI signaling in O-RAN using 50% CSI compression.
- Achieves 83.39% model complexity reduction and 5% accuracy improvement over a standard BiLSTM baseline.
- Demonstrates 147k QPS throughput via TensorRT optimization, facilitating deployment-ready channel-gain prediction.

## Open Questions & Future Work

- [[optimizing-oran-channel-prediction-scalability]]

## Archivist Review

I approved a refined open question regarding the challenges of deploying channel prediction in O-RAN systems, as this is a distinct and unresolved research bottleneck. I rejected the proposed concept LITE because it represents a specific system-level pipeline instantiation rather than a reusable algorithmic mechanism. The existing vault already contains sophisticated methods for time-series forecasting and uncertainty estimation that cover the underlying components of this architecture.

### Approved Open Questions
- Optimizing O-RAN Channel Prediction: This addresses the gap between proof-of-concept research and practical O-RAN deployments, ensuring that theoretical gains in transport efficiency translate into tangible system-level performance improvements.

### Rejected Candidates
- [concept] Lightweight Intelligent Trajectory Estimator (LITE) (`lite-lightweight-intelligent-trajectory-estimator`) - paper_local: This is a paper-specific architectural proposal rather than a generalizable algorithmic concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.08458)
- [PDF](https://arxiv.org/pdf/2604.08458)

