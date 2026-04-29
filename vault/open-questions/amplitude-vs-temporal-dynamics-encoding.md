---
created_at: '2026-04-29T05:12:34Z'
source_papers:
- '[[arxiv-260424942-independent-component-based-encoding-models-of-brain-activit]]'
title: Encoding Model Amplitude Accuracy
---

**Background:** Independent component analysis (ICA) decomposes fMRI data into spatially independent components and corresponding time series, which can then be used to train encoding models that map linguistic stimuli to neural responses. However, correlations between predicted and actual time series can be high despite significant discrepancies in signal amplitude, indicating that current models struggle to capture absolute magnitude in addition to temporal dynamics.

**Question / Future Work:** A systematic investigation is needed to determine the factors—such as data normalization, model regularization, or variations in the neural-to-BOLD coupling—that lead to the decoupling of temporal prediction accuracy from signal amplitude estimation in component-based encoding models. Understanding these drivers is essential for building encoding models that can accurately recover the full dynamical range of brain activity.

**Why It Matters:** This is a fundamental limitation in the interpretability and utility of neural encoding models. If models only capture temporal shapes but fail to model signal amplitude, they cannot fully characterize the neural responses or differentiate between varying intensities of neural engagement across conditions.