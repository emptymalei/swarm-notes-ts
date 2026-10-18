---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Forecasting a Cosmological 21 cm Stacking Detection with Early HIRAX Data"
description: "The paper presents a simulation-based forecasting pipeline for detecting the cosmological 21 cm signal using early data from the HIRAX radio interferometer. The authors simulate the cosmological signal, instrumental noise, and astrophysical foregrounds for a 36-dish array, applying delay-domain filtering to create 'ringmaps'. By stacking these maps at the positions of known external galaxies, the study finds that while spectroscopic redshift precision allows for a robust detection (SNR > 11), the signal is significantly degraded when using photometric redshifts due to the interaction between redshift uncertainty and foreground filtering."
resource: "https://arxiv.org/abs/2610.18981"
tags:
  - "21cm-cosmology"
  - "astrophysics"
  - "cosmology"
  - "forecasting"
  - "simulation"
  - "signal-processing"
timestamp: "2026-10-18T00:51:42Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Pascal Hitz"
  - literal: "Devin Crichton"
  - literal: "Alexandre Refregier"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18981"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "21cm-stacking-detection"
    description: "A statistical method that averages radio intensity maps at the locations of external catalogue sources to enhance the signal-to-noise ratio of the cosmological 21 cm signal."
  - name: "delay-domain-foreground-filtering"
    description: "A signal processing technique that transforms frequency-dependent visibility data into the delay domain to isolate and remove smooth-spectrum foreground contamination."
datasets:
  []
open_questions:
  - name: "redshift-precision-in-21cm-cross-correlation"
    description: "To what extent can 21 cm signals be recovered when cross-correlated with photometric surveys, given that the necessary frequency-domain foreground filtering may interact destructively with the inherent redshift uncertainties of the external sources?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:51:42Z"
created_at: "2026-10-18T00:51:42Z"
---

# Forecasting a Cosmological 21 cm Stacking Detection with Early HIRAX Data

**Authors**: Pascal Hitz, Devin Crichton, Alexandre Refregier
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18981](https://arxiv.org/abs/2610.18981)

## Summary

The paper presents a simulation-based forecasting pipeline for detecting the cosmological 21 cm signal using early data from the HIRAX radio interferometer. The authors simulate the cosmological signal, instrumental noise, and astrophysical foregrounds for a 36-dish array, applying delay-domain filtering to create 'ringmaps'. By stacking these maps at the positions of known external galaxies, the study finds that while spectroscopic redshift precision allows for a robust detection (SNR > 11), the signal is significantly degraded when using photometric redshifts due to the interaction between redshift uncertainty and foreground filtering.

## Key Contributions

- Developed an end-to-end forward modeling pipeline for forecasting 21 cm detections with the early-stage 36-dish HIRAX array.
- Quantified the impact of redshift precision on 21 cm signal recovery, demonstrating that spectroscopic accuracy (sigma_z/(1+z) ~ 0.001) is essential for detection after foreground filtering.
- Demonstrated that a minimum signal-to-noise ratio (SNR) of 11 is achievable using 120 days of single-pointing HIRAX data cross-correlated with a Euclid-like spectroscopic sample.

## Limitations

The study is restricted to a single zenith pointing and assumes a simplified 36-dish configuration, which may not capture all systematic effects of the full HIRAX array.

## Open Questions & Future Work

- [[redshift-precision-in-21cm-cross-correlation]]

## Key Concepts

- [[21cm-stacking-detection]]: A statistical method that averages radio intensity maps at the locations of external catalogue sources to enhance the signal-to-noise ratio of the cosmological 21 cm signal.
- [[delay-domain-foreground-filtering]]: A signal processing technique that transforms frequency-dependent visibility data into the delay domain to isolate and remove smooth-spectrum foreground contamination.

## Archivist Review

The approved concepts (21 cm Stacking and Delay-Domain Filtering) are fundamental to the field of radio cosmology and represent the core methodologies analyzed. The open question was refined to focus on the interaction between redshift precision and signal recovery, which the paper identified as the most critical bottleneck for future cross-correlation detections. The 'Euclid-like' dataset was rejected as it is a simulated benchmark for forecasting rather than a persistent dataset.

### Approved Concepts
- 21 cm Stacking Detection: Stacking is a critical statistical technique in intensity mapping for extracting faint cosmological signals from maps dominated by noise and foregrounds.
- Delay-Domain Foreground Filtering: This technique addresses the primary bottleneck in 21 cm cosmology: the removal of astrophysical foregrounds that are orders of magnitude brighter than the target signal.

### Approved Open Questions
- Redshift Precision in 21 cm Cross-Correlation: Large-scale photometric surveys offer much larger source densities than spectroscopic ones, but their utility for 21 cm cross-correlation depends on overcoming the signal suppression caused by redshift errors.

### Rejected Candidates
- [dataset] Euclid-like spectroscopic galaxy sample (`euclid-like-spectroscopic-galaxy-sample`) - paper_local: This is a simulated proxy used for forecasting rather than a standalone, persistent, or widely reusable dataset.
- [open_question] Scaling Delay-Domain Filtering for Large Interferometers (`optimizing-delay-domain-filtering-for-large-arrays`) - other: The candidate was rewritten and approved under a more specific slug that better reflects the paper's evidence regarding redshift precision.

## Links

- [Abstract](https://arxiv.org/abs/2610.18981)
- [PDF](https://arxiv.org/pdf/2610.18981)

