---
# CSL-compatible fields
title: "Dispersion-Domain Detection for Mobile Molecular Communication Under Multiplicative Geometry Uncertainty"
author:
  - literal: "Shaojie Zhang"
  - literal: "Ozgur B. Akan"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.15896"

# Custom fields
paper_id: "2604.15896"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dispersion-domain-detection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:09:44Z"
created_at: "2026-04-20T05:09:44Z"
---

# Dispersion-Domain Detection for Mobile Molecular Communication Under Multiplicative Geometry Uncertainty

**Authors**: Shaojie Zhang, Ozgur B. Akan
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.15896](https://arxiv.org/abs/2604.15896)

## Summary

This paper addresses the sensitivity of mobile molecular communication systems to geometry-induced multiplicative noise and inter-symbol interference. The authors introduce a novel dispersion-domain detection statistic, which isolates signal dispersion from the deterministic mean to ensure threshold stability under unknown, time-varying geometry gains. By employing a time-series central limit theorem to approximate the receiver's performance, the framework provides analytical ROC/BER metrics that account for both node mobility and signal memory. Simulations confirm that this approach maintains reliable detection performance in scenarios where conventional mean-domain analysis fails due to suppressed signal differences.

## Key Contributions

- Proposes a dispersion-domain detection statistic T_k^(Δ) that enables threshold stability in mobile molecular communication under multiplicative geometry gain uncertainty.
- Derives a Gaussian working approximation for the detection statistic using a time-series central limit theorem, incorporating long-run variance corrections for ISI and mobility.
- Demonstrates superior empirical threshold stability compared to mean-domain detection methods, particularly when mean signal differences are unreliable or suppressed.

## Open Questions & Future Work

- [[robust-mobile-mc-detection-bottlenecks]]

## Key Concepts

- [[dispersion-domain-detection]]: A detection framework that isolates signal dispersion by subtracting deterministic mean components and normalizing, enabling threshold stability under multiplicative geometry gains.

## Archivist Review

The paper proposes a novel detection statistic that addresses threshold instability in molecular communication. The concept of 'Dispersion-Domain Detection' is approved as it offers a reusable strategy for handling multiplicative gain uncertainty. The open question was reframed to focus on the specific performance bottlenecks inherent to the proposed approach, ensuring it remains a targetable, high-level research question.

### Approved Concepts
- Dispersion-Domain Detection: It introduces a robust detection statistic designed to maintain threshold stability under multiplicative uncertainty, a common challenge in stochastic sensing and molecular communication.

### Approved Open Questions
- Robust Mobile MC Detection Bottlenecks: This is a foundational performance bottleneck in the transition from theoretical model-based detection to robust, adaptive nanonetwork transceivers.

### Rejected Candidates
- [open_question] Robust Mobile MC Detection Directions (`future-directions-mobile-mc-detection`) - other: The candidate was too broad and overlapped with the conceptual focus; it was reframed into a more precise research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.15896)
- [PDF](https://arxiv.org/pdf/2604.15896)

