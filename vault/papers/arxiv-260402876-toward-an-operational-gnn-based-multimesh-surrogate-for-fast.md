---
# CSL-compatible fields
title: "Toward an Operational GNN-Based Multimesh Surrogate for Fast Flood Forecasting"
author:
  - literal: "Valentin Mercier"
  - literal: "Serge Gratton"
  - literal: "Lapeyre Corentin"
  - literal: "Gwenaël Chevallet"
issued:
  date-parts:
    - [2026, 4, 3]
url: "https://arxiv.org/abs/2604.02876"

# Custom fields
paper_id: "2604.02876"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series"
  - "spatiotemporal-modeling"
  - "graph-neural-networks"
  - "surrogate-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-06T05:02:38Z"
created_at: "2026-04-06T05:02:38Z"
---

# Toward an Operational GNN-Based Multimesh Surrogate for Fast Flood Forecasting

**Authors**: Valentin Mercier, Serge Gratton, Lapeyre Corentin, Gwenaël Chevallet
**Date**: 2026-04-03
**Paper ID**: [arxiv:2604.02876](https://arxiv.org/abs/2604.02876)

## Summary

This paper presents a GNN-based surrogate model to accelerate high-fidelity hydraulic flood forecasting on large, unstructured meshes. By utilizing a projected-mesh strategy and multimesh connectivity, the authors enable efficient training and extended spatial receptive fields. The model incorporates explicit boundary discharge features and pushforward training to enhance long-term autoregressive stability, achieving near-realtime performance suitable for rapid decision support in flood risk management.

## Key Contributions

- Introduces a graph neural network surrogate for flood forecasting using a projected-mesh strategy to handle high-resolution unstructured meshes.
- Demonstrates that multimesh connectivity effectively expands the spatial receptive field, improving prediction accuracy without increasing model depth.
- Validates that incorporating explicit discharge boundary conditions and pushforward training significantly improves long-range autoregressive rollout stability.
- Achieves a ~27,000x speedup (0.4s vs 180min) compared to traditional Telemac2D hydraulic solvers while maintaining operational accuracy.

## Links

- [Abstract](https://arxiv.org/abs/2604.02876)
- [PDF](https://arxiv.org/pdf/2604.02876)

