---
# CSL-compatible fields
title: "Starspot activity and surface differential rotation on UX Arietis"
author:
  - literal: "Yue Xiang"
  - literal: "Shenghong Gu"
  - literal: "A. Collier Cameron"
  - literal: "J. R. Barnes"
  - literal: "Dongtao Cao"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11702"

# Custom fields
paper_id: "2605.11702"
paper_source: "arxiv"
domain: "astronomy"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:24:46Z"
created_at: "2026-05-13T05:24:46Z"
---

# Starspot activity and surface differential rotation on UX Arietis

**Authors**: Yue Xiang, Shenghong Gu, A. Collier Cameron, J. R. Barnes, Dongtao Cao
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11702](https://arxiv.org/abs/2605.11702)

## Summary

This paper presents Doppler images of the K0 subgiant component of the binary system UX Arietis, based on high-resolution spectral observations from 2017 and 2024. The authors address spectral line variability by using the Ca I 6439 Å line as a reliable reference for Least-Squares Deconvolution (LSD), ensuring consistent spot reconstructions. The resulting surface maps indicate persistent mid-to-high latitude starspot structures and reveal a weak anti-solar differential rotation profile. Additionally, the study notes a spatial association between a starspot group observed in 2017 and a subsequent large flare event.

## Key Contributions

- Reconstructed high-resolution Doppler images of the K0 subgiant primary of UX Arietis using 2017 and 2024 time-series spectra.
- Demonstrated that using the Ca I 6439 Å line as a reference for Least-Squares Deconvolution (LSD) profile generation improves Doppler imaging consistency and reliability.
- Identified a weak anti-solar differential rotation for the K0 subgiant, contrasted with an equator belt that remains well tidally locked.

## Open Questions & Future Work

- [[anti-solar-rotation-mechanism]]

## Archivist Review

The paper provides standard astronomical analysis of stellar rotation and activity. The proposed open question regarding the mechanism of anti-solar differential rotation is significant for stellar physics and satisfies the threshold for tracking, while the concept related to calibration was rejected as a standard domain-specific implementation detail.

### Approved Open Questions
- Mechanism of anti-solar rotation: Understanding this rotational pattern is critical for refining stellar dynamo theories and the influence of rotational shear on magnetic field generation in evolved, magnetically active stars.

### Rejected Candidates
- [concept] LSD Reference Profile Consistency (`lsd-reference-profile-consistency`) - not_novel: The method of using a reference line for LSD calibration is a standard astronomical signal processing practice and does not qualify as a novel, reusable ML-vault-worthy concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.11702)
- [PDF](https://arxiv.org/pdf/2605.11702)

