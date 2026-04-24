---
# CSL-compatible fields
title: "Short-time, Wavelet-inspired Mouse Submovement Detection"
author:
  - literal: "Auejin Ham"
  - literal: "Ben Boudaoud"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20673"

# Custom fields
paper_id: "2604.20673"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "segmentation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "self-weighted-loss-refinement"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:09:49Z"
created_at: "2026-04-24T05:09:49Z"
---

# Short-time, Wavelet-inspired Mouse Submovement Detection

**Authors**: Auejin Ham, Ben Boudaoud
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20673](https://arxiv.org/abs/2604.20673)

## Summary

This paper addresses the challenge of segmenting overlapping motor submovements in 1D speed time series, typically associated with motor planning and execution. The authors present a wavelet-inspired detection framework that utilizes a self-weighted loss refinement step to mitigate fitting errors common in standard wavelet transforms. Results from synthetic egocentric aiming trials show that the proposed method outperforms traditional dual-threshold and persistence-based segmentation techniques in accurately identifying ballistic submovement components.

## Key Contributions

- Introduces a wavelet-inspired approach for segmenting and parameterizing ballistic mouse submovements from 1D speed signals.
- Develops a self-weighted loss refinement technique to address performance degradation in noisy or overlapping motor submovements.
- Evaluates the method against dual-threshold and persistence-based 1D segmentation on 6,400 synthetic egocentric aiming trials, demonstrating improved detection accuracy.

## Open Questions & Future Work

- [[confidence-metrics-submovement-decomposition]]

## Key Concepts

- [[self-weighted-loss-refinement]]: An optimization technique that iteratively identifies and refines motion segments with poor fit quality to improve submovement extraction.

## Archivist Review

I approved the self-weighted loss refinement concept as it provides a reusable iterative optimization approach for improving signal fit, and the proposed open question regarding confidence metrics for submovement decomposition, as it addresses a fundamental challenge in time-series segmentation and decomposition. No datasets were approved as none were presented as distinct, reusable contributions.

### Approved Concepts
- self-weighted-loss-refinement: Central mechanism for improving the performance of the wavelet-based detection by iteratively refining low-confidence regions.

### Approved Open Questions
- Confidence Metrics for Submovement Decomposition: This would address a known limitation in current decomposition algorithms where poor parameter estimation in early iterations propagates errors, allowing for more reliable interpretation of submovement patterns in human motor tasks.

## Links

- [Abstract](https://arxiv.org/abs/2604.20673)
- [PDF](https://arxiv.org/pdf/2604.20673)

