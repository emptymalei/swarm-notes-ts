---
created_at: '2026-04-08T04:58:05Z'
source_papers:
- '[[arxiv-260405064-dynamic-linear-coregionalization-for-realistic-synthetic-mul]]'
title: Retention-Adaptation Trade-off in FMTS
---

**Background:** Foundation models for time series often rely on synthetic pretraining to generate priors for downstream tasks, but current methods frequently lack access to the original pretraining corpora of established models.

**Question / Future Work:** When fine-tuning established time series foundation models without access to their original training data, it remains unclear how to optimally balance the retention of previously learned temporal knowledge with the adaptation to new, dynamically generated synthetic datasets. This trade-off complicates the ability to consistently improve model performance through auxiliary synthetic pretraining.

**Why It Matters:** As more foundation models become available without public training data, developing principled methods for fine-tuning these models on new synthetic data without catastrophic forgetting is essential for practical application.

**Evidence:** To mitigate potential overfitting to DynLMC, we freeze all but the final three layers and adopt a reduced learning rate. Nevertheless, the absence of the original pretraining distribution may limit our ability to balance knowledge retention and adaptation.