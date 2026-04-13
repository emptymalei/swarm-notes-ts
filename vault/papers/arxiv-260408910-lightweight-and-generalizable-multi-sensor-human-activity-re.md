---
# CSL-compatible fields
title: "Lightweight and Generalizable Multi-Sensor Human Activity Recognition via Cascaded Fusion and Style-Augmented Decomposition"
author:
  - literal: "Wang Chenglong"
  - literal: "Zhuo Yan"
  - literal: "Ding Wenbo"
  - literal: "Chen Xinlei"
issued:
  date-parts:
    - [2026, 4, 10]
url: "https://arxiv.org/abs/2604.08910"

# Custom fields
paper_id: "2604.08910"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "cascaded-fusion-block"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-13T05:10:54Z"
created_at: "2026-04-13T05:10:54Z"
---

# Lightweight and Generalizable Multi-Sensor Human Activity Recognition via Cascaded Fusion and Style-Augmented Decomposition

**Authors**: Wang Chenglong, Zhuo Yan, Ding Wenbo, Chen Xinlei
**Date**: 2026-04-10
**Paper ID**: [arxiv:2604.08910](https://arxiv.org/abs/2604.08910)

## Summary

The paper introduces a lightweight framework for Wearable Human Activity Recognition (WHAR) that improves upon existing high-complexity attention-based models. It replaces standard cross-variable fusion with a novel Cascaded Fusion Block (CFB) that efficiently models multi-sensor relationships through recursive compression and concatenation. Additionally, the authors integrate a MixStyle-based augmentation module to enhance generalizability by diversifying batch-level feature statistics, providing a robust and efficient solution for resource-constrained wearable devices.

## Key Contributions

- Introduces the Cascaded Fusion Block (CFB) for efficient multi-sensor feature interaction without explicit attention, reducing computational overhead by >30%.
- Proposes a MixStyle-based data augmentation strategy to improve model generalization by perturbing batch-level statistics without corrupting core signal information.
- Demonstrates superior accuracy and macro-F1 performance on Realdisp and Skoda datasets compared to state-of-the-art attention-based WHAR baselines.

## Open Questions & Future Work

- [[ssl-for-whar-label-efficiency]]
- [[adaptive-moment-mixing-strategies]]

## Key Concepts

- [[cascaded-fusion-block]]: A lightweight feature fusion module that replaces attention-based mechanisms with a recursive compression and concatenation process.

## Archivist Review

I approved the Cascaded Fusion Block as a reusable architectural pattern for efficient feature fusion and two open questions concerning label efficiency and adaptive augmentation in sensor-based time series. Standard benchmark datasets (Realdisp, Skoda) were rejected as they are routine evaluation tools rather than novel research assets.

### Approved Concepts
- Cascaded Fusion Block: Central to the paper's efficiency claim, replacing heavy attention mechanisms with an operational process of compression-recursion-concatenation-fusion.

### Approved Open Questions
- Self-supervised learning for WHAR: Reducing reliance on labeled data is critical for scaling WHAR to diverse populations where annotated data is scarce.
- Adaptive moment mixing strategies: Adaptive strategies could better address hierarchical style variations in sensor data from low-level noise to high-level temporal dynamics.

### Rejected Candidates
- [dataset] Realdisp (`realdisp`) - not_novel: Standard benchmark dataset; doesn't meet the requirement for rare or critical standalone notes.
- [dataset] Skoda (`skoda`) - not_novel: Standard benchmark dataset; doesn't meet the requirement for rare or critical standalone notes.

## Links

- [Abstract](https://arxiv.org/abs/2604.08910)
- [PDF](https://arxiv.org/pdf/2604.08910)

