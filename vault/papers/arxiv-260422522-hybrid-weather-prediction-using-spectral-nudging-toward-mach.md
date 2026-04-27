---
# CSL-compatible fields
title: "Hybrid weather prediction using spectral nudging toward machine-learning forecasts"
author:
  - literal: "I. Polichtchouk"
  - literal: "M. C. A. Clare"
  - literal: "M. Chantry"
  - literal: "E. Gascón"
  - literal: "M. Maier-Gerber"
  - literal: "B. Vanniere"
  - literal: "S. Lang"
issued:
  date-parts:
    - [2026, 4, 24]
url: "https://arxiv.org/abs/2604.22522"

# Custom fields
paper_id: "2604.22522"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "spectral-nudging-for-hybrid-weather-prediction"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-27T05:11:20Z"
created_at: "2026-04-27T05:11:20Z"
---

# Hybrid weather prediction using spectral nudging toward machine-learning forecasts

**Authors**: I. Polichtchouk, M. C. A. Clare, M. Chantry, E. Gascón, M. Maier-Gerber, B. Vanniere, S. Lang
**Date**: 2026-04-24
**Paper ID**: [arxiv:2604.22522](https://arxiv.org/abs/2604.22522)

## Summary

This paper introduces a hybrid numerical weather prediction framework that spectrally nudges a physics-based Integrated Forecasting System (IFS) toward machine-learned model forecasts. By applying nudging exclusively to large-scale virtual temperature and vorticity, the approach improves large-scale prediction skill while preserving fine-scale physical dynamical behavior. The proposed method reduces the frequency of forecast busts and enhances tropical cyclone track accuracy without compromising storm intensity or near-surface weather representation. This study highlights a scalable pathway for integrating data-driven models with established physics-based weather forecasting systems.

## Key Contributions

- Introduced a hybrid forecasting framework using scale-selective spectral nudging to guide physics-based models (IFS) with machine-learned forecasts.
- Demonstrated substantial gains in large-scale forecast skill, equivalent to 1.5 days in the tropics and 12-18 hours in the extra-tropics.
- Showed that the hybrid system reduces forecast busts and maintains physically consistent storm intensities compared to pure machine-learning alternatives.

## Open Questions & Future Work

- [[hybrid-mitigation-of-forecast-busts-mechanisms]]

## Key Concepts

- [[spectral-nudging-for-hybrid-weather-prediction]]: A scale-selective technique that nudges physics-based NWP models toward ML forecasts at large scales while maintaining high-fidelity dynamics at small scales.

## Archivist Review

The paper presents a clear, scalable methodological framework for hybrid weather forecasting. I have approved the spectral nudging concept as it provides a robust mechanism for integrating ML and physics-based models that is likely to be highly reusable in climate and atmospheric sciences. The open question regarding forecast busts was selected as it addresses a fundamental limitation in the reliability of hybrid systems. Other candidates were rejected for being overly local to this specific study or too specific to cyclone track prediction.

### Approved Concepts
- Spectral Nudging for Hybrid Weather Prediction: Provides a robust framework for blending physical consistency with ML-driven performance gains in numerical weather prediction via scale-selective integration.

### Approved Open Questions
- Hybrid Mitigation of Forecast Busts Mechanisms: Understanding the selective mitigation of forecast failures is crucial for diagnosing the sources of model errors and refining hybrid system design to optimize predictive reliability.

## Links

- [Abstract](https://arxiv.org/abs/2604.22522)
- [PDF](https://arxiv.org/pdf/2604.22522)

