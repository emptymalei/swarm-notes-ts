---
# CSL-compatible fields
title: "Forecasting the occupancy of satellite megaconstellations in SKA observations"
author:
  - literal: "Nicolas Cerardi"
  - literal: "Emma Tolley"
  - literal: "Federico di Vruno"
issued:
  date-parts:
    - [2026, 4, 24]
url: "https://arxiv.org/abs/2604.22694"

# Custom fields
paper_id: "2604.22694"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "ska-radio-frequency-interference-modeling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-27T05:10:39Z"
created_at: "2026-04-27T05:10:39Z"
---

# Forecasting the occupancy of satellite megaconstellations in SKA observations

**Authors**: Nicolas Cerardi, Emma Tolley, Federico di Vruno
**Date**: 2026-04-24
**Paper ID**: [arxiv:2604.22694](https://arxiv.org/abs/2604.22694)

## Summary

This paper provides a critical forecast of radio frequency interference (RFI) from emerging satellite megaconstellations on upcoming Square Kilometre Array (SKA) observations. Using an analytical model, the authors evaluate satellite exposure scenarios considering both the main beam and the first sidelobe. The results indicate significant interference, particularly for SKA-Low, which faces near-total RFI exposure at lower frequencies. The findings highlight an urgent need for advanced mitigation strategies beyond conventional data flagging to maintain scientific viability.

## Key Contributions

- Introduces an analytical model to forecast satellite megaconstellation RFI exposure for SKA-Low and SKA-Mid telescopes.
- Demonstrates that SKA-Low faces high interference risk, with up to 100% of observation time exposed to satellite RFI below 100 MHz.
- Quantifies that SKA-Mid observations below 1 GHz are predicted to be compromised for at least 30% of observation time.

## Open Questions & Future Work

- [[characterizing-satellite-uemr-impact]]

## Key Concepts

- [[ska-radio-frequency-interference-modeling]]: An analytical framework for estimating satellite-induced RFI exposure in future Square Kilometre Array observations.

## Archivist Review

I approved the RFI modeling concept as it provides a reproducible methodology for evaluating satellite-induced interference in radio astronomy. The open question on UEMR impact characterization was approved because it addresses a fundamental scientific bottleneck identified by the authors that prevents moving from occupancy forecasting to robust, physics-aware mitigation. All other candidates were rejected as they were either too specific to the SKA or represent routine forecasting extensions.

### Approved Concepts
- SKA Radio Frequency Interference Modeling: The paper establishes a critical forecast for future radio astronomy operations under increasing satellite megaconstellation density. The analytical framework serves as a methodology for quantifying RFI exposure risks.

### Approved Open Questions
- Characterizing satellite UEMR impact: This is a foundational bottleneck; without a granular understanding of the RFI power and coherence, it is impossible to distinguish between background noise and data-corrupting signals, which prevents the development of effective, non-destructive mitigation strategies.

## Links

- [Abstract](https://arxiv.org/abs/2604.22694)
- [PDF](https://arxiv.org/pdf/2604.22694)

