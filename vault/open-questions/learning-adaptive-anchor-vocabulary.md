---
created_at: '2026-04-29T05:11:55Z'
source_papers:
- '[[arxiv-260425092-feature-anchors-for-time-series-sensor-based-human-activity]]'
title: Learning Adaptive Anchor Vocabularies
---

**Background:** Wearable human activity recognition (HAR) models often rely on handcrafted time-series features (TSFs) as fixed preprocessing steps or learn latent representations directly from raw signals. Recent approaches have begun exploring hybrid models where these handcrafted features serve as explicit intermediate representations, or "anchors," within a trainable neural architecture.

**Question / Future Work:** The feature-anchor formulation currently relies on a fixed, manually curated vocabulary of time-series feature (TSF) families. Future work is required to develop methods for learning an adaptive, task-specific, or sparsity-controlled anchor vocabulary, which could potentially improve computational efficiency and enhance the interpretability of the model.

**Why It Matters:** Automatically learning the most discriminative feature anchors could eliminate the need for manual feature engineering, making the TCNet framework more generalizable across different sensing domains.

**Evidence:** Learning a smaller, task-specific, or sparsity-controlled anchor vocabulary may further improve efficiency and sharpen interpretability.