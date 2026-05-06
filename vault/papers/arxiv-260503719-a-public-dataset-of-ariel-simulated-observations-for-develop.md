---
# CSL-compatible fields
title: "A public dataset of Ariel simulated observations for developing exoplanetary atmosphere data reduction pipelines"
author:
  - literal: "Lorenzo V. Mugnai"
  - literal: "Kai Hou Yip"
  - literal: "Andrea Bocchieri"
  - literal: "Andreas Papageorgiou"
  - literal: "Virginie Batista"
  - literal: "Orphée Faucoz"
  - literal: "Angèle Syty"
  - literal: "Tara Tahseen"
  - literal: "Enzo Pascale"
  - literal: "Ingo Waldmann"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03719"

# Custom fields
paper_id: "2605.03719"
paper_source: "arxiv"
domain: "astronomy-and-astrophysics"
tags:
  []
architectures:
  []
datasets:
  - "ExoSim2"
  - "TauREx"
concept_slugs:
  - "ariel-simulated-dataset"
dataset_slugs:
  - "exosim2"
  - "taurex"
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:12:03Z"
created_at: "2026-05-06T05:12:03Z"
---

# A public dataset of Ariel simulated observations for developing exoplanetary atmosphere data reduction pipelines

**Authors**: Lorenzo V. Mugnai, Kai Hou Yip, Andrea Bocchieri, Andreas Papageorgiou, Virginie Batista, Orphée Faucoz, Angèle Syty, Tara Tahseen, Enzo Pascale, Ingo Waldmann
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03719](https://arxiv.org/abs/2605.03719)

## Summary

This paper presents a large-scale, high-fidelity public dataset of simulated observations tailored to the ESA Ariel mission's payload design, aimed at advancing exoplanetary atmosphere data reduction and detrending pipelines. By providing ground-truth labeled data alongside a deep learning baseline, the researchers enable robust benchmarking of both classical and data-driven methods. The study also identifies critical performance limitations, specifically the susceptibility of machine learning models to dataset shift when transitioning from simulated training data to realistic observational conditions.

## Key Contributions

- Released a comprehensive public dataset of simulated Ariel exoplanetary atmosphere observations for benchmarking detrending algorithms.
- Provided a deep neural network baseline for time-series spectroscopy reduction to facilitate comparative algorithm development.
- Demonstrated the vulnerability of ML-based detrending methods to dataset shift between simulated training distributions and potentially divergent real-world observational conditions.

## Open Questions & Future Work

- [[uncalibrated-uncertainty-ood-exoplanet-ml]]

## Key Concepts

- [[ariel-simulated-dataset]]: A comprehensive public dataset of simulated Ariel exoplanetary atmosphere observations designed for benchmarking data reduction and detrending pipelines.

## Archivist Review

I approved the Ariel Simulated Dataset as a foundational benchmark for exoplanetary spectroscopy and two critical simulation software packages (ExoSim2 and TauREx). The open question regarding out-of-distribution uncertainty was refined to focus on the specific bottleneck of epistemic uncertainty quantification in astrophysical survey science. This selection adheres to the policy of keeping vault entries rare and focused on high-utility research infrastructure.

### Approved Concepts
- Ariel Simulated Dataset: It provides a standardized, high-fidelity benchmark for validating ML-based data reduction pipelines, which is a critical step for future exoplanetary atmospheric science.

### Approved Open Questions
- Calibrated Uncertainty for OOD Spectroscopy: In survey-scale missions like Ariel, overconfident predictions on OOD data can lead to erroneous scientific conclusions, making epistemic uncertainty quantification a critical bottleneck.

### Rejected Candidates
- [open_question] Calibrated Uncertainty for Exoplanet OOD (`uncalibrated-uncertainty-ood-exoplanet-ml`) - duplicate_existing: This was renamed to a more concise, descriptive title for the vault.

## Datasets

- [[exosim2]]
- [[taurex]]

## Links

- [Abstract](https://arxiv.org/abs/2605.03719)
- [PDF](https://arxiv.org/pdf/2605.03719)

