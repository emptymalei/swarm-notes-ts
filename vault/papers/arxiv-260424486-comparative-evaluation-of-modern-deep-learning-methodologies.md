---
# CSL-compatible fields
title: "Comparative Evaluation of Modern Deep Learning Methodologies for Portfolio Optimization"
author:
  - literal: "Samuel Ozechi"
  - literal: "Banjo Francis"
  - literal: "Wisdom Yakanu"
  - literal: "Joe Wayne Byers"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24486"

# Custom fields
paper_id: "2604.24486"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "transformer-gnn-portfolio-optimization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "transformer-gnn-portfolio-optimization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:13:55Z"
created_at: "2026-04-29T05:13:55Z"
---

# Comparative Evaluation of Modern Deep Learning Methodologies for Portfolio Optimization

**Authors**: Samuel Ozechi, Banjo Francis, Wisdom Yakanu, Joe Wayne Byers
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24486](https://arxiv.org/abs/2604.24486)

## Summary

This paper provides a comparative study of deep learning methodologies, including GNNs, DRL, Transformers, and Autoencoders, applied to portfolio optimization tasks such as return forecasting and asset allocation. By testing these models against traditional financial strategies like Mean-Variance Optimization (MVO), the authors show that hybrid models capturing both temporal and relational structures outperform individual deep learning architectures. Specifically, the Transformer+GNN approach yields superior stability in risk-adjusted performance, though traditional MVO remains highly competitive in maximizing returns when fed with high-quality predictive inputs.

## Key Contributions

- Evaluates a comparative suite of deep learning models (GNN, DRL, Transformers, Autoencoders) against traditional financial baselines like MVO and 60/40.
- Introduces hybrid architectures (Transformer+GNN and Autoencoder+DRL) that improve stability and risk control by capturing cross-asset relational dependencies alongside temporal dynamics.
- Demonstrates that while standalone deep learning models show limitations in market structural awareness, hybrid configurations significantly reduce volatility and maximum drawdown compared to traditional baselines.

## Key Concepts

- [[transformer-gnn-portfolio-optimization]]: A hybrid model architecture that combines Transformer temporal modeling with GNN-based asset relational learning to improve portfolio risk metrics.

## Archivist Review

I approved the Transformer-GNN concept but mapped it to the existing vault slug 'transformer-gnn-portfolio-optimization' to maintain consistency. The paper provides a standard empirical comparison rather than a novel theoretical framework, so no further concepts or open questions were deemed sufficiently impactful for permanent entry.

### Approved Concepts
- Transformer-GNN Hybrid Portfolio Optimization: Demonstrates the benefit of merging graph-based relational modeling with temporal attention for asset allocation stability.

### Rejected Candidates
- [concept] Transformer-GNN Hybrid Portfolio Optimization (`transformer-gnn-hybrid-portfolio-optimization`) - duplicate_existing: The proposed slug is redundant; using the existing slug 'transformer-gnn-portfolio-optimization' instead.

## Links

- [Abstract](https://arxiv.org/abs/2604.24486)
- [PDF](https://arxiv.org/pdf/2604.24486)

