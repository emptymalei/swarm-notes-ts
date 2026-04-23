---
created_at: '2026-04-22T05:03:31Z'
generated_stub: true
modified_at: '2026-04-23T05:09:39Z'
processed_at: '2026-04-22T05:03:31Z'
slug: stochastic-attention
source_papers:
- '[[arxiv-260419530-calibrating-scientific-foundation-models-with-inference-time]]'
title: Stochastic Attention
type: concept
---

# Stochastic Attention

> *Auto-generated stub. Edit this file to add more details.*

An inference-time modification to transformer attention mechanisms that produces calibrated predictive ensembles via multinomial sampling.


## Why It Matters

It enables uncertainty quantification in deterministic foundation models through a plug-and-play inference-time modification, avoiding costly retraining.

## Evidence

> We propose Stochastic Attention, a lightweight inference-time modification that randomizes attention by replacing softmax weights with normalized multinomial samples controlled by a single concentration parameter, and produces predictive ensembles without retraining.

## Related Papers

- [[arxiv-260419530-calibrating-scientific-foundation-models-with-inference-time]]