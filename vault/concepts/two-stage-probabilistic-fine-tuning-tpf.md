---
title: "Two-stage Probabilistic Fine-tuning (TPF)"
slug: "two-stage-probabilistic-fine-tuning-tpf"
type: concept
generated_stub: true
source_papers:
  - "[[arxiv-260409041-u-cast-a-surprisingly-simple-and-efficient-frontier-probabil]]"
processed_at: "2026-04-13T05:10:11Z"
created_at: "2026-04-13T05:10:11Z"
---

# Two-stage Probabilistic Fine-tuning (TPF)

> *Auto-generated stub. Edit this file to add more details.*

A two-stage training strategy combining deterministic pre-training with CRPS-based probabilistic fine-tuning and Monte Carlo Dropout to achieve competitive probabilistic performance.


## Why It Matters

Provides a generalized, compute-efficient framework for adapting standard deterministic architectures to probabilistic forecasting tasks without requiring complex generative backbones.

## Evidence

> deterministic pre-training on Mean Absolute Error followed by short probabilistic fine-tuning on the Continuous Ranked Probability Score (CRPS) using Monte Carlo Dropout for stochasticity

## Related Papers

- [[arxiv-260409041-u-cast-a-surprisingly-simple-and-efficient-frontier-probabil]]
