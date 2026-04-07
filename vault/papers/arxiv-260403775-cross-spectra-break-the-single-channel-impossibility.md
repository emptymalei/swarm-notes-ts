---
# CSL-compatible fields
title: "Cross Spectra Break the Single-Channel Impossibility"
author:
  - literal: "Yuda Bi"
  - literal: "Vince D Calhoun"
issued:
  date-parts:
    - [2026, 4, 4]
url: "https://arxiv.org/abs/2604.03775"

# Custom fields
paper_id: "2604.03775"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "cross-spectral-detectability-coefficient"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-07T04:55:16Z"
created_at: "2026-04-07T04:55:16Z"
---

# Cross Spectra Break the Single-Channel Impossibility

**Authors**: Yuda Bi, Vince D Calhoun
**Date**: 2026-04-04
**Paper ID**: [arxiv:2604.03775](https://arxiv.org/abs/2604.03775)

## Summary

This paper addresses the theoretical impossibility of detecting time-irreversibility in single-channel linear Gaussian time series by leveraging dual-channel cross-spectral information. The authors demonstrate that the off-diagonal subspace of the spectral matrix contains hidden dynamical signatures that single-channel measures, such as traditional entropy production metrics, cannot access. By introducing the cross-spectral detectability coefficient (Scross), the study provides a robust, scale-invariant metric that certifies non-equilibrium behavior in systems where all single-channel measures vanish. The findings are validated through analytical links to entropy production rates in coupled Ornstein–Uhlenbeck models and are proposed for use in multi-probe physical and climate monitoring systems.

## Key Contributions

- Identified that cross-spectral information in the off-diagonal subspace of the spectral matrix enables detection of time-irreversibility in linear Gaussian systems where single-channel measures fail.
- Derived the cross-spectral detectability coefficient (Scross), which remains strictly positive at timescale coalescence and is independent of observed timescales.
- Established a formal relationship between cross-spectral structure and the entropy production rate (EPR) in coupled Ornstein–Uhlenbeck systems, proving Scross serves as a certificate for system dissipation.

## Open Questions & Future Work

- [[generalizing-cross-spectral-epr-witnesses]]

## Key Concepts

- [[cross-spectral-detectability-coefficient]]: A quartic-order cross-contribution metric derived from the spectral matrix that enables detection of non-equilibrium behavior in linear systems where single-channel measures fail.

## Archivist Review

The paper provides a significant theoretical contribution by demonstrating that off-diagonal spectral information can recover system-level signatures that are otherwise hidden from single-channel analysis. I have approved the 'Cross-spectral detectability coefficient' as a key methodological concept and the associated open question regarding the extension of this framework to more complex, bidirectional systems. No datasets were approved as none were central to the theoretical claims of this work.

### Approved Concepts
- Cross-spectral detectability coefficient: It overcomes the 'single-channel impossibility' for detecting time-irreversibility in linear Gaussian systems by leveraging off-diagonal spectral information.

### Approved Open Questions
- Generalizing Cross-Spectral EPR Witnesses: This is critical for validating the cross-spectral witness as a reliable indicator of system dissipation in realistic, complex physical systems where one-way coupling is an oversimplification.

## Links

- [Abstract](https://arxiv.org/abs/2604.03775)
- [PDF](https://arxiv.org/pdf/2604.03775)

