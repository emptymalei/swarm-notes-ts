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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "self-weighted-loss-refinement"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:56:08Z"
created_at: "2026-04-25T04:56:08Z"
---

# Short-time, Wavelet-inspired Mouse Submovement Detection

**Authors**: Auejin Ham, Ben Boudaoud
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20673](https://arxiv.org/abs/2604.20673)

## Summary

This paper presents a wavelet-inspired approach to detect and parameterize ballistic submovements from 1D speed time series, addressing the challenge of overlapping motion components. The method incorporates a self-weighted loss refinement step to improve the quality of fit in regions where standard wavelet transforms typically struggle. Empirical validation on 6,400 synthetic trials of egocentric camera movement shows that the proposed approach offers improved accuracy over traditional dual-threshold and persistence-based segmentation methods.

## Key Contributions

- Introduced a wavelet-inspired methodology for the precise extraction and parameterization of overlapping ballistic submovements in 1D velocity time series.
- Proposed a self-weighted loss refinement step that enhances signal fitting in regions traditionally difficult for standard wavelet transforms.
- Demonstrated efficacy on ~6,400 synthetic first-person shooter aim trials, outperforming existing dual-threshold and persistence-based 1D segmentation techniques.

## Open Questions & Future Work

- [[confidence-metrics-submovement-decomposition]]

## Key Concepts

- [[self-weighted-loss-refinement]]: A post-processing refinement step that improves fit quality by adaptively weighting loss based on the local performance of the signal decomposition.

## Archivist Review

The paper introduces a wavelet-inspired method for submovement decomposition and a specific refinement strategy. I approved 'self-weighted loss refinement' as it is a reusable signal-processing improvement, and 'confidence-metrics-submovement-decomposition' as it addresses a fundamental limitation in the robustness and evaluation of motor control time-series modeling. No datasets were approved as the described synthetic trials were based on a private dataset of 13 users, failing the criterion for critical, reusable community resources.

### Approved Concepts
- Self-weighted loss refinement: Provides a mechanism to iteratively improve submovement detection accuracy by addressing poor fitting regions within a wavelet-inspired framework.

### Approved Open Questions
- Confidence metrics submovement decomposition: The lack of standardized, robust confidence metrics for submovement decomposition hinders the objective comparison of motor control strategies across populations, especially when motions exhibit high degrees of temporal overlap.

## Links

- [Abstract](https://arxiv.org/abs/2604.20673)
- [PDF](https://arxiv.org/pdf/2604.20673)

