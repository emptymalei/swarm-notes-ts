---
# CSL-compatible fields
title: "Period-conscious Time-series Reconstruction under Local Differential Privacy"
author:
  - literal: "Yaxuan Wang"
  - literal: "Tianxin Li"
  - literal: "Enji Liang"
  - literal: "Yue Fu"
  - literal: "Yanran Wang"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02724"

# Custom fields
paper_id: "2605.02724"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "privacy-preserving-ml"
  - "time-series-reconstruction"
  - "periodicity-estimation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "cycle-and-phase-recovery-cpr"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:14:03Z"
created_at: "2026-05-06T05:14:03Z"
---

# Period-conscious Time-series Reconstruction under Local Differential Privacy

**Authors**: Yaxuan Wang, Tianxin Li, Enji Liang, Yue Fu, Yanran Wang
**Date**: 2026-05-04
**Paper ID**: [arxiv:2605.02724](https://arxiv.org/abs/2605.02724)

## Summary

This paper introduces Cycle and Phase Recovery (CPR), a framework designed to reconstruct periodic time series signals subjected to local differential privacy (LDP) noise. LDP typically corrupts spectral peaks and causes phase drift, which the authors mitigate by utilizing multi-scale period probing and multi-consensus selection to align samples within cycles. By integrating EM-based denoising with kernel density estimation, the method improves reconstruction robustness even under strict privacy constraints, outperforming existing LDP-based baselines.

## Key Contributions

- Proposed CPR (Cycle and Phase Recovery), a framework that leverages multi-scale period probing and multi-consensus selection to maintain spectral integrity under local differential privacy.
- Introduced a phase-matched aggregation mechanism combined with EM-based denoising to stabilize phase alignment and improve per-phase reconstruction.
- Demonstrated that CPR consistently outperforms representative LDP baselines in reconstruction error and structural preservation, particularly in high-privacy (low-epsilon) regimes.

## Open Questions & Future Work

- [[multi-period-reconstruction-under-ldp]]

## Key Concepts

- [[cycle-and-phase-recovery-cpr]]: A period-aware reconstruction framework that uses multi-scale period probing, phase-matched aggregation, and EM-based denoising to recover periodic signals under local differential privacy.

## Archivist Review

I approved the Cycle and Phase Recovery framework as it offers a specific architectural approach to a distinct intersection of signal processing and privacy-preserving ML. The open question regarding multi-periodic reconstruction highlights a significant, non-trivial limitation in current state-of-the-art privacy-preserving signal recovery methods, moving beyond standard 'more data/better results' boilerplate. No datasets were approved because the paper relied on general, unnamed periodic signal domains rather than proposing a reusable benchmark collection.

### Approved Concepts
- Cycle and Phase Recovery (CPR): It provides a dedicated mechanism for periodic signal reconstruction under restrictive local differential privacy budgets, a distinct problem from standard time series forecasting.

### Approved Open Questions
- Multi-periodic LDP Reconstruction Limits: Most complex multimedia and physiological signals contain multiple overlapping periodic rhythms; limiting reconstruction to a single period severely restricts the fidelity and utility of privacy-preserving systems.

## Links

- [Abstract](https://arxiv.org/abs/2605.02724)
- [PDF](https://arxiv.org/pdf/2605.02724)

