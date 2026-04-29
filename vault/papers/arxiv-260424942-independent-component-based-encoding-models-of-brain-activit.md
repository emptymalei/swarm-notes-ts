---
# CSL-compatible fields
title: "Independent-Component-Based Encoding Models of Brain Activity During Story Comprehension"
author:
  - literal: "Kamya Hari"
  - literal: "Taha Binhuraib"
  - literal: "Jin Li"
  - literal: "Cory Shain"
  - literal: "Anna A. Ivanova"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24942"

# Custom fields
paper_id: "2604.24942"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "independent-component-based-encoding-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:12:34Z"
created_at: "2026-04-29T05:12:34Z"
---

# Independent-Component-Based Encoding Models of Brain Activity During Story Comprehension

**Authors**: Kamya Hari, Taha Binhuraib, Jin Li, Cory Shain, Anna A. Ivanova
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24942](https://arxiv.org/abs/2604.24942)

## Summary

This paper introduces an independent component (IC)-based encoding framework for fMRI data to overcome limitations of traditional voxelwise models, such as high noise and spatial variability. By decomposing fMRI signals into ICs and predicting them from large language model representations of linguistic stimuli, the authors identify spatially and temporally consistent cognitive networks related to story comprehension. The results demonstrate that the method successfully isolates stimulus-driven activity, providing a more robust and interpretable approach for cross-subject neural analysis.

## Key Contributions

- Introduced an IC-based encoding framework that improves signal-to-noise ratio by dissociating stimulus-driven neural signals from noise.
- Demonstrated that predictive ICs capture functionally consistent networks (auditory/language) across subjects despite individual variations.
- Validated that the framework effectively filters out motion artifacts by showing poor predictive performance on ICA-AROMA identified noise components.

## Open Questions & Future Work

- [[amplitude-vs-temporal-dynamics-encoding]]
- [[ica-model-order-selection]]

## Key Concepts

- [[independent-component-based-encoding-framework]]: An fMRI encoding framework that predicts independent component time series derived from naturalistic stimulus data to capture functional neural networks.

## Archivist Review

The independent component-based encoding framework is a robust methodological shift in neuroimaging analysis and is approved for the vault. Two open questions concerning amplitude estimation and model order selection are also approved as they highlight fundamental, unresolved bottlenecks in ICA-based neural encoding that transcend this specific study.

### Approved Concepts
- Independent Component-based Encoding Framework: Shifts the focus of encoding models from individual voxels to functional networks, improving noise dissociation and inter-subject comparability.

### Approved Open Questions
- Encoding Model Amplitude Accuracy: This is a fundamental limitation in the interpretability and utility of neural encoding models. If models only capture temporal shapes but fail to model signal amplitude, they cannot fully characterize the neural responses or differentiate between varying intensities of neural engagement across conditions.
- Optimal ICA Model Order: Model order selection is a classic, unresolved meta-parameter issue in ICA-based neuroimaging. Without a clear heuristic or validation standard, researchers may choose arbitrary component counts, limiting the comparability of results across different datasets and studies.

## Links

- [Abstract](https://arxiv.org/abs/2604.24942)
- [PDF](https://arxiv.org/pdf/2604.24942)

