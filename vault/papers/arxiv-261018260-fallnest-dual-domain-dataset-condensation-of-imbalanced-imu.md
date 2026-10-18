---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "FALLNEST: Dual-Domain Dataset Condensation of Imbalanced IMU Data for Wearable Fall Detection"
description: "FALLNEST is a data-centric framework designed to address the challenges of imbalanced IMU data in wearable fall detection by distilling large datasets into tiny, class-balanced synthetic training sets. Using dual-domain condensation (time and frequency), it combines normalized gradient matching with MMD-based embedding alignment and Fourier-domain augmentation to ensure the synthetic data preserves critical features of rare fall events. Evaluation on benchmarks like SisFall and KFall shows that models trained on as little as 1% of the original data achieve performance comparable to full-dataset training, making it highly efficient for resource-constrained wearable applications."
resource: "https://arxiv.org/abs/2610.18260"
tags:
  - "time-series"
  - "wearable-sensing"
  - "healthcare-ai"
  - "sensor-based-har"
  - "distillation"
  - "data imbalance"
  - "computational-efficiency"
  - "spatio-temporal-modeling"
timestamp: "2026-10-18T00:59:01Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Rashi Niyas P"
  - literal: "Ritika Jain"
  - literal: "Hitika Tiwari"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18260"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "dataset-condensation"
    description: "A data-centric technique that distills a large training dataset into a significantly smaller synthetic set that preserves the original dataset's performance."
datasets:
  - name: "SisFall"
    description: "A wearable sensor dataset containing IMU data from 38 subjects performing 19 Activities of Daily Living (ADL) and 15 fall types, widely used for benchmarking fall detection algorithms."
  - name: "KFall"
    description: "A large-scale dataset for fall detection and activity recognition containing inertial data from subjects performing a diverse range of activities and fall scenarios."
open_questions:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:59:01Z"
created_at: "2026-10-18T00:59:01Z"
---

# FALLNEST: Dual-Domain Dataset Condensation of Imbalanced IMU Data for Wearable Fall Detection

**Authors**: Rashi Niyas P, Ritika Jain, Hitika Tiwari
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18260](https://arxiv.org/abs/2610.18260)

## Summary

FALLNEST is a data-centric framework designed to address the challenges of imbalanced IMU data in wearable fall detection by distilling large datasets into tiny, class-balanced synthetic training sets. Using dual-domain condensation (time and frequency), it combines normalized gradient matching with MMD-based embedding alignment and Fourier-domain augmentation to ensure the synthetic data preserves critical features of rare fall events. Evaluation on benchmarks like SisFall and KFall shows that models trained on as little as 1% of the original data achieve performance comparable to full-dataset training, making it highly efficient for resource-constrained wearable applications.

## Key Contributions

- Developed FALLNEST, a dual-domain dataset condensation framework that handles extreme class imbalance in IMU data by generating class-balanced synthetic training sets.
- Introduced a fall-specific 7-channel input representation and multi-view Fourier-domain augmentation to enhance signal learning during the condensation process.
- Achieved high classification performance (93.5-95.8% accuracy) using a TinyCNN trained on only 1% of the original data windows, significantly reducing training overhead.

## Limitations

The study relies on subject-wise splits and synthetic data; real-world performance on diverse, unobserved populations or varied sensor placements remains to be fully explored.

## Key Concepts

- [[dataset-condensation]]: A data-centric technique that distills a large training dataset into a significantly smaller synthetic set that preserves the original dataset's performance.

## Archivist Review

I have approved 'Dataset Condensation' as a core concept because it represents the fundamental methodology of the paper and is a growing field in data-centric AI. I rejected 'FALLNEST' as it is a paper-specific system name and the underlying innovations are better captured by the broader condensation concept. The datasets SisFall and KFall are approved as they are standard benchmarks in the fall detection domain.

### Approved Concepts
- Dataset Condensation: Dataset condensation (or distillation) is a critical data-centric approach for reducing computational costs and enabling training on edge devices with limited memory.

### Rejected Candidates
- [concept] FALLNEST (`fallnest`) - paper_local: This is the name of the specific framework proposed in the paper, which is a composite of several existing techniques (gradient matching, MMD, etc.) tailored for fall detection rather than a fundamental standalone concept.

## Datasets

- [[SisFall]]
- [[KFall]]

## Links

- [Abstract](https://arxiv.org/abs/2610.18260)
- [PDF](https://arxiv.org/pdf/2610.18260)

