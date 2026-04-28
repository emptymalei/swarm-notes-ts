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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "transformer-gnn-portfolio-optimization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:14:26Z"
created_at: "2026-04-28T05:14:26Z"
---

# Comparative Evaluation of Modern Deep Learning Methodologies for Portfolio Optimization

**Authors**: Samuel Ozechi, Banjo Francis, Wisdom Yakanu, Joe Wayne Byers
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24486](https://arxiv.org/abs/2604.24486)

## Summary

This study evaluates various deep learning architectures for portfolio optimization by integrating them with traditional financial models. Through backtesting on a diverse set of equities, ETFs, and bonds from 2015-2023, the authors demonstrate that hybrid models, specifically Transformer+GNNs, excel in risk management and stability. The results indicate that while deep learning effectively handles market complexity, traditional Mean-Variance Optimization remains highly competitive for return-focused strategies when provided with high-quality neural-derived inputs.

## Key Contributions

- Evaluates four distinct deep learning paradigms—GNNs, DRL, Transformers, and Autoencoders—on historical financial asset data (2015-2023).
- Demonstrates that hybrid Transformer+GNN architectures significantly outperform standalone models in volatility and maximum drawdown metrics.
- Establishes that integrating deep-learned inputs into traditional Mean-Variance Optimization (MVO) provides superior Sharpe ratios compared to purely neural approaches.

## Key Concepts

- [[transformer-gnn-portfolio-optimization]]: A hybrid architecture combining Transformer-based temporal modeling with Graph Neural Networks for relational asset structure analysis in portfolio management.

## Archivist Review

The paper provides a comparative empirical study rather than a foundational new methodology. The proposed hybrid concept was rejected because combining Transformers and GNNs is an established approach in time-series and relational modeling, making this specific instantiation a domain-specific application rather than a novel conceptual contribution. No other candidates were provided for consideration.

### Approved Concepts
- Transformer+GNN Portfolio Optimization: The paper identifies this hybrid as achieving the best risk management metrics (volatility and drawdown) compared to standalone architectures.

### Rejected Candidates
- [concept] Transformer+GNN Portfolio Optimization (`transformer-gnn-portfolio-optimization`) - not_novel: While a valid finding, this specific application to portfolio optimization is too narrow; the underlying architectural combination of Transformers and GNNs is already well-understood in the literature.

## Links

- [Abstract](https://arxiv.org/abs/2604.24486)
- [PDF](https://arxiv.org/pdf/2604.24486)

