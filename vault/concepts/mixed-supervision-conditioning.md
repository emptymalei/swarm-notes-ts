---
created_at: '2026-04-14T05:02:20Z'
generated_stub: true
modified_at: '2026-04-15T05:06:46Z'
processed_at: '2026-04-14T05:02:20Z'
slug: mixed-supervision-conditioning
source_papers:
- '[[arxiv-260411707-representations-before-pixels-semantics-guided-hierarchical]]'
title: Mixed Supervision Conditioning
type: concept
---

# Mixed Supervision Conditioning

> *Auto-generated stub. Edit this file to add more details.*

A training strategy for hierarchical models that interleaves ground-truth and predicted latent representations to improve robustness to autoregressive error accumulation.


## Why It Matters

It addresses the critical train-test distribution shift inherent in multi-stage autoregressive forecasting models where downstream modules are trained on ground-truth priors but evaluated on model-generated ones.

## Evidence

> To address this, we introduce two conditioning strategies, nested dropout and mixed supervision, that improve robustness to imperfect autoregressive predictions.

## Related Papers

- [[arxiv-260411707-representations-before-pixels-semantics-guided-hierarchical]]