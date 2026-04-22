---
title: "Correlation-Aware Loss"
slug: "correlation-aware-loss"
type: concept
generated_stub: true
source_papers:
  - "[[arxiv-260418727-skillful-global-ocean-emulation-and-the-role-of-correlation]]"
processed_at: "2026-04-22T05:05:15Z"
created_at: "2026-04-22T05:05:15Z"
---

# Correlation-Aware Loss

> *Auto-generated stub. Edit this file to add more details.*

A loss function based on the Mahalanobis distance that improves multivariate forecast skill by accounting for correlations between target variable tendencies.


## Why It Matters

This technique replaces standard MSE by explicitly modeling the covariance structure of target variables, which the paper proves is critical for stable ocean emulation.

## Evidence

> demonstrate the use of Mahalanobis distance as loss that improves the forecast skill... by explicitly accounting for the correlations between tendencies of the target variables.

## Related Papers

- [[arxiv-260418727-skillful-global-ocean-emulation-and-the-role-of-correlation]]
