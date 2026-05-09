---
created_at: '2026-05-09T05:12:25Z'
source_papers:
- '[[arxiv-260505736-sdflow-similarity-driven-flow-matching-for-time-series-gener]]'
title: Universal Time Series Tokenizer
---

**Background:** Time series generative models often rely on dataset-specific VQ-VAE tokenizers with fixed, non-transferable codebooks.

**Question / Future Work:** There is a critical need to develop a universal time-series tokenizer with a shared, cross-domain codebook to move beyond dataset-specific architectures. This would enable unified latent spaces for multi-domain generative modeling and improve scalability.

**Why It Matters:** Universal tokenization is essential for scaling time series generative models across diverse domains and simplifying the pipeline for new applications.

**Evidence:** Currently, SDFlow uses a dataset-specific VQ tokenizer and codebook. A natural next step is to develop a universal time-series tokenizer with a shared codebook.