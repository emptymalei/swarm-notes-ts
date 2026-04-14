---
title: "Mixed Supervision Conditioning"
slug: "mixed-supervision-conditioning"
type: concept
generated_stub: true
source_papers:
  - "[[arxiv-260411707-representations-before-pixels-semantics-guided-hierarchical]]"
processed_at: "2026-04-14T05:02:20Z"
created_at: "2026-04-14T05:02:20Z"
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
