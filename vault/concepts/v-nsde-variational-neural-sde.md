---
title: "Variational Neural Stochastic Differential Equation (V-NSDE)"
slug: "v-nsde-variational-neural-sde"
type: concept
generated_stub: true
source_papers:
  - "[[arxiv-2604.00669-embedded-variational-neural-stochastic-differential-equation]]"
processed_at: "2026-04-02T05:37:59Z"
created_at: "2026-04-02T05:37:59Z"
---

# Variational Neural Stochastic Differential Equation (V-NSDE)

> *Auto-generated stub. Edit this file to add more details.*

A generative framework that models continuous-time latent trajectories using Neural SDEs conditioned on embedding-aware drift and diffusion functions.


## Why It Matters

V-NSDE provides a novel hybrid architecture that combines continuous-time stochastic dynamics with variational generative modeling, specifically designed to disentangle noise from trends in heterogeneous time-series data.

## Evidence

> This model uses an encoder and a decoder. The encoder takes the initial observations and district embeddings and translates them into a Gaussian distribution... Then the obtained latent state initiates the Neural SDE... governing functions depend on the time index, latent state, and district embedding.

## Related Papers

- [[arxiv-2604.00669-embedded-variational-neural-stochastic-differential-equation]]
