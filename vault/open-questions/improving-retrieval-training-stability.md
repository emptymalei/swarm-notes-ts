---
created_at: '2026-04-09T04:54:39Z'
source_papers:
- '[[arxiv-260407027-learning-to-query-history-nonstationary-classification-via-l]]'
title: Improving Retrieval Training Stability
---

**Background:** Retrieval-augmented models typically rely on training stability techniques such as variance reduction or regularization to prevent models from ignoring context, especially in scenarios involving discrete stochastic sampling and end-to-end training.

**Question / Future Work:** The current methodology requires careful tuning of score-based gradient estimators to manage high variance and prevent the classifier from ignoring historical context early in training. Future work should investigate alternate gradient estimators, variance-reducing baselines, and regularization strategies to improve overall training stability.

**Why It Matters:** Training stability is a critical bottleneck for deploying retrieval-augmented systems in real-world nonstationary environments, where high gradient variance can lead to sub-optimal convergence.

**Evidence:** Our system requires careful tuning to manage the high variance of the score-based gradient estimator and to prevent the classifier from ignoring historical context early in training.