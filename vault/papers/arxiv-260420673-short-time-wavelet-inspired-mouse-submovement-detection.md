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
  - "signal-processing"
  - "motion-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "self-weighted-loss-refinement"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:06:03Z"
created_at: "2026-04-23T05:06:03Z"
---

# Short-time, Wavelet-inspired Mouse Submovement Detection

**Authors**: Auejin Ham, Ben Boudaoud
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20673](https://arxiv.org/abs/2604.20673)

## Summary

This paper addresses the difficulty of decomposing ballistic submovements from overlapping motion data by leveraging a wavelet-inspired framework. To overcome the limitations of standard wavelet transforms in capturing non-stationary, overlapping events, the authors introduce a self-weighted loss refinement step that enhances segmentation accuracy in areas with poor fit. The method is validated against synthetic egocentric aiming datasets modeled from human user behavior, outperforming traditional dual-threshold and persistence-based segmentation approaches.

## Key Contributions

- Introduced a wavelet-inspired method for detecting and parameterizing overlapping ballistic submovements in 1D speed time series.
- Developed a self-weighted loss refinement procedure to overcome poor fit quality issues inherent in basic wavelet transforms.
- Validated the approach on ~6,400 synthetic egocentric aiming trials, demonstrating superior performance compared to dual-threshold and persistence-based segmentation baselines.

## Open Questions & Future Work

- [[adaptive-submovement-termination-criteria]]

## Key Concepts

- [[self-weighted-loss-refinement]]: An iterative refinement technique that improves signal decomposition by selectively weighting areas with poor model fit.

## Archivist Review

I approved the self-weighted loss refinement concept as a reusable, generalizable signal processing technique. The open question regarding termination criteria was approved as it reflects a broader, recurring challenge in iterative decomposition methods. The orthogonality question was rejected as overly localized to specific submovement modeling assumptions.

### Approved Concepts
- Self-weighted loss refinement: This mechanism addresses the core limitation of standard wavelet-based signal segmentation by iteratively refining fit quality in overlapping motion scenarios.

### Approved Open Questions
- Adaptive submovement termination criteria: Automated and reliable termination of submovement extraction is a primary bottleneck in applying these methods to real-world datasets where ground truth labels are absent and motion profiles vary significantly across populations or tasks.

### Rejected Candidates
- [open_question] Orthogonality in submovement decomposition (`wavelet-decomposition-orthogonality`) - paper_local: The question is highly specific to a niche limitation of current submovement models rather than a general bottleneck in time-series analysis.

## Links

- [Abstract](https://arxiv.org/abs/2604.20673)
- [PDF](https://arxiv.org/pdf/2604.20673)

