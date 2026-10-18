---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TEX-MEX: Similarity-Guided Temporal Contrastive Learning for Time Series"
description: "TEX-MEX is a novel self-supervised learning framework designed to address the difficulty of finding meaningful augmentations in time series data. It unifies structural (morphological) and temporal similarity by using an encoder to identify similar windows in a batch and then relating them to their respective temporal shifts. The method achieves state-of-the-art results across various medical and sensor-based time series benchmarks, including PPG and ECG analysis. Notably, the authors release a 560K-parameter PPG foundation model that achieves superior performance while being 50x smaller than previous state-of-the-art unimodal foundation models."
resource: "https://arxiv.org/abs/2610.19557"
tags:
  - "time-series"
  - "self-supervised-learning"
  - "contrastive-learning"
  - "representation-learning"
  - "foundation-models"
  - "healthcare-ai"
  - "ppg"
  - "eeg"
  - "ecg"
  - "spatio-temporal"
timestamp: "2026-10-18T00:45:32Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Aditya Radhakrishnan"
  - literal: "Maxwell A. Xu"
  - literal: "Wanting Mao"
  - literal: "Santosh Kumar"
  - literal: "Harish Haresamudram"
  - literal: "James M. Rehg"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19557"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "tex-mex"
    description: "A self-supervised learning objective for time series that unifies structural and temporal similarity by relating a window to the temporal shifts of its morphologically similar peers."
datasets:
  []
open_questions:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:45:32Z"
created_at: "2026-10-18T00:45:32Z"
---

# TEX-MEX: Similarity-Guided Temporal Contrastive Learning for Time Series

**Authors**: Aditya Radhakrishnan, Maxwell A. Xu, Wanting Mao, Santosh Kumar, Harish Haresamudram, James M. Rehg
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19557](https://arxiv.org/abs/2610.19557)

## Summary

TEX-MEX is a novel self-supervised learning framework designed to address the difficulty of finding meaningful augmentations in time series data. It unifies structural (morphological) and temporal similarity by using an encoder to identify similar windows in a batch and then relating them to their respective temporal shifts. The method achieves state-of-the-art results across various medical and sensor-based time series benchmarks, including PPG and ECG analysis. Notably, the authors release a 560K-parameter PPG foundation model that achieves superior performance while being 50x smaller than previous state-of-the-art unimodal foundation models.

## Key Contributions

- Proposes TEX-MEX, a novel self-supervised learning objective that unifies structural (morphological) and temporal similarity for robust time-series representation learning.
- Demonstrates state-of-the-art performance across five diverse physiological domains: PPG, EEG, ECG, accelerometry, and continuous glucose monitoring.
- Introduces a highly efficient 560K-parameter PPG foundation model that outperforms existing models that are 50x larger in parameter count.
- Provides an open-source and open-weight foundation model to the community to support future research in wearable sensing and digital health.

## Limitations

The abstract does not explicitly discuss the potential sensitivity of the objective to the initial quality of the encoder used to identify structural similarities.

## Key Concepts

- [[tex-mex]]: A self-supervised learning objective for time series that unifies structural and temporal similarity by relating a window to the temporal shifts of its morphologically similar peers.

## Archivist Review

Approved the TEX-MEX concept as it introduces a novel method for time-series self-supervised learning that unifies structural and temporal similarity, offering a solution to the augmentation bottleneck. Rejected the open question on bootstrap stability as the analysis indicates the paper does not explicitly address or pose this as a future research direction. No datasets were approved as no specific named datasets were provided in the candidate list.

### Approved Concepts
- TEX-MEX: It addresses the fundamental difficulty of selecting meaningful positive/negative pairs in time-series contrastive learning by bridging the gap between structural morphology and temporal proximity.

### Rejected Candidates
- [open_question] Bootstrap Stability in Similarity-Guided SSL (`similarity-guided-bootstrap-stability`) - weak_evidence: The provided analysis explicitly states the paper does not discuss this sensitivity, and no evidence excerpt was provided to support it as an authored open question.

## Links

- [Abstract](https://arxiv.org/abs/2610.19557)
- [PDF](https://arxiv.org/pdf/2610.19557)

