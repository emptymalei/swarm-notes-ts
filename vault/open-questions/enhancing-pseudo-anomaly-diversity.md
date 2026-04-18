---
created_at: '2026-04-17T05:07:07Z'
modified_at: '2026-04-18T04:53:47Z'
source_papers:
- '[[arxiv-260413924-aster-latent-pseudo-anomaly-generation-for-unsupervised-time]]'
title: Enhancing Pseudo-Anomaly Diversity
---

**Background:** Time-series anomaly detection often relies on the generation of pseudo-anomalies in latent space to facilitate adversarial training of classifiers, where the diversity of these samples significantly influences the robustness of the resulting detection boundaries.

**Question / Future Work:** There is a need to improve the latent perturbator module to enforce greater diversity in generated pseudo-anomalies through advanced sampling techniques, architectural constraints, or learnable token inputs to address observed sparsity and limited variance in anomalous representations.

**Why It Matters:** The limited diversity of generated pseudo-anomalies restricts the model's ability to learn complex decision boundaries, directly impacting performance on datasets with varied or rare anomalies.

**Evidence:** Future research could focus on further enhancing the perturbator by enforcing anomaly diversity through advanced latent sampling, constraints, or more complex decoder inputs (e.g., learnable tokens)