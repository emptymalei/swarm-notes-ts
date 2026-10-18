---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Variable Masking for Climate Emulation in ACE"
description: "The paper addresses a critical deficiency in current AI climate emulators: the systematic underestimation of near-surface warming trends. The authors introduce M-ACE2S (Masked-ACE2S), a stochastic emulator that utilizes 'variable masking' during training to prevent the model from over-relying on individual input channels. Coupled with a new 'global mean removal' normalization strategy, M-ACE2S demonstrates superior training stability and better generalization to unseen climate forcing compared to the ACE2S baseline. Results on the ERA5 reanalysis dataset show significant improvements in long-term near-surface temperature prediction, making it a more robust tool for climate emulation."
resource: "https://arxiv.org/abs/2610.21012"
tags:
  - "earth-system-modeling"
  - "climate-modeling"
  - "weather-forecasting"
  - "stochastic-modeling"
  - "normalization"
  - "robustness"
  - "generalization"
  - "era5"
  - "machine-learning-applications"
timestamp: "2026-10-18T00:26:04Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Alexey Yermakov"
  - literal: "Troy Arcomano"
  - literal: "Jeremy McGibbon"
  - literal: "Brian Henn"
  - literal: "Oliver Watt-Meyer"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.21012"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "variable-masking"
    description: "A regularization technique that masks entire input variables or channels during training to force the model to learn robust physical dependencies across all predictors."
  - name: "global-mean-removal"
    description: "A normalization strategy that subtracts the instantaneous spatial global average from climate fields to facilitate generalization to non-stationary forcing."
datasets:
  []
open_questions:
  - name: "masking-physical-consistency"
    description: "How does the stochastic nature of variable masking interact with explicit physical constraints (e.g., energy conservation)? Does reducing channel dependency improve or degrade the emulator's ability to maintain physical consistency in extreme warming scenarios?"
  - name: "regional-precision-tradeoff"
    description: "Does the use of global mean removal negatively impact the precision of regional-scale anomalies or the detection of localized extreme weather events by potentially smoothing out critical variance?"
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:26:04Z"
created_at: "2026-10-18T00:26:04Z"
---

# Variable Masking for Climate Emulation in ACE

**Authors**: Alexey Yermakov, Troy Arcomano, Jeremy McGibbon, Brian Henn, Oliver Watt-Meyer
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.21012](https://arxiv.org/abs/2610.21012)

## Summary

The paper addresses a critical deficiency in current AI climate emulators: the systematic underestimation of near-surface warming trends. The authors introduce M-ACE2S (Masked-ACE2S), a stochastic emulator that utilizes 'variable masking' during training to prevent the model from over-relying on individual input channels. Coupled with a new 'global mean removal' normalization strategy, M-ACE2S demonstrates superior training stability and better generalization to unseen climate forcing compared to the ACE2S baseline. Results on the ERA5 reanalysis dataset show significant improvements in long-term near-surface temperature prediction, making it a more robust tool for climate emulation.

## Key Contributions

- Introduced M-ACE2S (Masked-ACE2S), which incorporates variable masking to reduce channel dependency and improve the capture of long-term warming trends.
- Proposed 'global mean removal' as a novel normalization technique that enhances training stability and improves extrapolation to unseen climate forcing.
- Demonstrated that combining masking with global mean removal corrects the systematic underestimation of near-surface warming trends observed in previous ACE2.1-ERA5 emulators.
- Achieved improved in-sample performance and generalizability on the AIMIP benchmark for climate emulation.

## Limitations

The study focuses primarily on near-surface air temperature; the impact of these techniques on other climate variables or extreme event distributions is not fully detailed.

## Open Questions & Future Work

- [[masking-physical-consistency]]
- [[regional-precision-tradeoff]]

## Key Concepts

- [[variable-masking]]: A regularization technique that masks entire input variables or channels during training to force the model to learn robust physical dependencies across all predictors.
- [[global-mean-removal]]: A normalization strategy that subtracts the instantaneous spatial global average from climate fields to facilitate generalization to non-stationary forcing.

## Archivist Review

I approved the two methodological contributions (Variable Masking and Global Mean Removal) as they represent reusable strategies for improving robustness in scientific emulation. I also approved two open questions that explore the trade-offs between these stability-focused methods and regional/physical accuracy. The ERA5 dataset was rejected as it is the standard 'routine' benchmark for this domain.

### Approved Concepts
- Variable Masking: Prevents emulators from learning 'shortcuts' or over-relying on a subset of climate variables, which is a known cause of trend underestimation in long-term climate projections.
- Global Mean Removal: Significantly improves extrapolation to out-of-sample forcing (e.g., higher CO2 levels) by removing global spatial biases that cause training instability in standard normalization schemes.

### Approved Open Questions
- Masking and Physical Consistency Trade-offs: Establishing whether robust feature learning through masking supports or conflicts with physical law preservation is key to building trustworthy climate models.
- Regional Impact of Global Normalization: Climate adaptation requires accurate local-scale information, and it is vital to know if global stability comes at the cost of regional accuracy.

### Rejected Candidates
- [dataset] ERA5 (`era5`) - not_novel: ERA5 is the standard, ubiquitous reanalysis dataset in atmospheric science and functions as a routine benchmark rather than a novel contribution or specialized resource introduced by this work.

## Links

- [Abstract](https://arxiv.org/abs/2610.21012)
- [PDF](https://arxiv.org/pdf/2610.21012)

