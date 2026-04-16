---
created_at: '2026-04-15T05:04:05Z'
generated_stub: true
modified_at: '2026-04-16T05:08:17Z'
processed_at: '2026-04-15T05:04:05Z'
slug: gradient-based-distribution-shift-detection
source_papers:
- '[[arxiv-260412425-forecasting-the-past-gradient-based-distribution-shift-detec]]'
title: Gradient-Based Distribution Shift Detection
type: concept
---

# Gradient-Based Distribution Shift Detection

> *Auto-generated stub. Edit this file to add more details.*

A post-hoc method using the L2 norm of forecasting loss gradients to quantify distribution shifts in sequence prediction models.


## Why It Matters

This provides a post-hoc, model-agnostic mechanism for detecting distributional shifts in sequence forecasting tasks without modifying the primary model.

## Evidence

> The L2 norm of the gradient of this forecasting loss with respect to the decoder's final layer defines a score to identify distribution shifts.

## Related Papers

- [[arxiv-260412425-forecasting-the-past-gradient-based-distribution-shift-detec]]