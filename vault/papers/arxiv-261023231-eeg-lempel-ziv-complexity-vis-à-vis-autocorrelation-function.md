---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "EEG Lempel-Ziv Complexity vis-à-vis Autocorrelation Function"
description: "This paper investigates the relationship between normalized Lempel-Ziv complexity (LZC) and the Autocorrelation Function (ACF) in electroencephalography (EEG). By analyzing both synthetic stochastic processes and resting-state EEG data, the authors demonstrate a strong inverse correlation between LZC and the first autocorrelation coefficient. The results suggest that the information captured by LZC largely reflects temporal redundancy and oscillatory persistence already quantifiable by simpler, more mechanistically transparent autocorrelation measures."
resource: "https://arxiv.org/abs/2610.23231"
tags:
  - "time-series"
  - "eeg"
  - "signal-processing"
  - "stochastic-modeling"
  - "statistics"
  - "information-theory"
  - "mechanistic-interpretability"
  - "biomedical-signal-processing"
timestamp: "2026-10-19T04:31:20Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Pedro Montoya"
  - literal: "Ignacio Cifre"
  - literal: "José Luis Rosselló Sanz"
  - literal: "Dante R. Chialvo"
issued:
  date-parts:
    - [2026, 10, 16]

# Domain-specific custom fields
paper_id: "2610.23231"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "eeg-complexity-constituent-decomposition"
    description: "It remains an unresolved challenge to determine the relative contributions of specific statistical properties—including oscillatory amplitude, spectral composition, and temporal predictability—to observed changes in complexity measures. Establishing a framework to disentangle these factors is necessary for providing a transparent mechanistic interpretation of EEG complexity across different physiological and pathological brain states."
  - name: "non-linear-info-in-complexity-metrics"
    description: "While linear temporal dependence is a primary driver of signal compressibility, the specific signal regimes or neurophysiological conditions under which Lempel-Ziv complexity captures higher-order, non-linear temporal structures that are invisible to conventional linear autocorrelation remain to be rigorously identified. Identifying these specific scenarios is essential for justifying the added value of algorithmic complexity metrics over simpler statistical measures."
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:31:20Z"
created_at: "2026-10-19T04:31:20Z"
---

# EEG Lempel-Ziv Complexity vis-à-vis Autocorrelation Function

**Authors**: Pedro Montoya, Ignacio Cifre, José Luis Rosselló Sanz, Dante R. Chialvo
**Date**: 2026-10-16
**Paper ID**: [arxiv:2610.23231](https://arxiv.org/abs/2610.23231)

## Summary

This paper investigates the relationship between normalized Lempel-Ziv complexity (LZC) and the Autocorrelation Function (ACF) in electroencephalography (EEG). By analyzing both synthetic stochastic processes and resting-state EEG data, the authors demonstrate a strong inverse correlation between LZC and the first autocorrelation coefficient. The results suggest that the information captured by LZC largely reflects temporal redundancy and oscillatory persistence already quantifiable by simpler, more mechanistically transparent autocorrelation measures.

## Key Contributions

- Demonstrated a robust inverse relationship between normalized Lempel-Ziv complexity (LZC) and the first autocorrelation coefficient (r1) across synthetic and physiological EEG signals.
- Validated that dynamic changes in EEG complexity during eyes-open/eyes-closed maneuvers are strongly correlated with shifts in the signal's temporal autocorrelation structure.
- Argued that LZC primarily reflects temporal redundancy already captured by conventional autocorrelation measures, which are more mechanistically interpretable for neurophysiology.

## Limitations

The analysis primarily focuses on linear autocorrelation (r1), potentially overlooking higher-order non-linear dependencies that LZC might capture in more complex or pathological brain states.

## Open Questions & Future Work

- [[eeg-complexity-constituent-decomposition]]
- [[non-linear-info-in-complexity-metrics]]

## Archivist Review

I have approved two open questions focusing on the mechanistic interpretability and utility of signal complexity metrics like Lempel-Ziv Complexity (LZC) in relation to standard autocorrelation. The paper provides strong evidence that LZC is often redundant with linear temporal statistics in EEG, raising critical questions about when such algorithmic complexity measures provide unique value and how their constituent drivers can be disentangled. No new concepts or datasets were approved, as the paper relies on established metrics and standard/synthetic datasets to make its analytical point.

### Approved Open Questions
- Decomposing EEG Complexity Constituents: Without a method to decompose these influences, changes in LZC remain physiologically ambiguous, making it difficult to distinguish between shifts in simple oscillatory power and fundamental changes in neural information processing.
- Unique Non-Linear Information in LZC: If the information captured by LZC is largely redundant with linear autocorrelation, the use of more complex algorithmic measures may not be justified without identifying the specific non-linear phenomena they are meant to detect.

## Links

- [Abstract](https://arxiv.org/abs/2610.23231)
- [PDF](https://arxiv.org/pdf/2610.23231)

