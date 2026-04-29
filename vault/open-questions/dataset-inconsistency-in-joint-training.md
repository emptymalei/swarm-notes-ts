---
created_at: '2026-04-29T05:11:09Z'
source_papers:
- '[[arxiv-260425559-representing-the-surface-ocean-in-ecmwfs-data-driven-forecas]]'
title: Dataset Inconsistency in Joint Training
---

**Background:** Machine learning Earth system models are often trained on datasets derived from diverse sources, such as reanalyses, which may possess inconsistent forcing or data assimilation configurations across atmospheric and oceanic components. Training on these disparate, partially incompatible sources can lead to degradation in forecast performance for specific components during joint modeling.

**Question / Future Work:** Research is required to develop robust training strategies, dataset alignment methods, or truly coupled reanalysis pipelines to mitigate the impact of data inconsistencies when integrating heterogeneous Earth system components into a unified machine learning model.

**Why It Matters:** This is a critical bottleneck for the development of high-fidelity, data-driven Earth system models, as performance gains from coupling can be overshadowed by inconsistencies in the underlying training data infrastructure.

**Evidence:** This degradation highlights a fundamental challenge of joint training across partially incompatible datasets. While the marine datasets are forced by atmospheric fields consistent with those used in training, the atmospheric reanalysis ERA5 (used for pre-training) and the operational atmospheric analysis (used for fine-tuning) are forced by different ocean representations that do not match the marine training datasets.