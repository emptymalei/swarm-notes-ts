---
# CSL-compatible fields
title: "Hybrid Deep Learning Approach for Coupled Demand Forecasting and Supply Chain Optimization"
author:
  - literal: "Nusrat Yasmin Nadia"
  - literal: "Md Habibul Arif"
  - literal: "Habibor Rahman Rabby"
  - literal: "Md Iftekhar Monzur Tanvir"
  - literal: "Md. Jakir Hossen"
  - literal: "M. F. Mridha"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21567"

# Custom fields
paper_id: "2604.21567"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:07:48Z"
created_at: "2026-04-24T05:07:48Z"
---

# Hybrid Deep Learning Approach for Coupled Demand Forecasting and Supply Chain Optimization

**Authors**: Nusrat Yasmin Nadia, Md Habibul Arif, Habibor Rahman Rabby, Md Iftekhar Monzur Tanvir, Md. Jakir Hossen, M. F. Mridha
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21567](https://arxiv.org/abs/2604.21567)

## Summary

This paper presents HAF-DS, a hybrid AI framework that integrates LSTM-based demand forecasting with MILP optimization for enhanced supply chain resilience. By embedding temporal demand features into a prescriptive optimization layer, the model simultaneously minimizes forecasting error and operational costs. Experimental results on textile and PPE supply chain datasets indicate that this coupled approach significantly outperforms isolated statistical and deep learning forecasting methods.

## Key Contributions

- Introduces HAF-DS, a hybrid architecture coupling LSTM-based demand forecasting with MILP-based supply chain optimization.
- Achieves a 14.7% reduction in MAE and 12.4% reduction in RMSE compared to baseline methods on textile and PPE supply chain data.
- Demonstrates substantial operational improvements, including a 27.5% reduction in stockouts and a 5.4% decrease in inventory costs.

## Open Questions & Future Work

- [[robustness-to-extreme-demand-shocks]]

## Archivist Review

The paper describes a specific application of a well-known hybrid predictive-prescriptive framework (LSTM coupled with MILP). The framework itself is too application-specific to qualify as a novel, reusable concept, but the identified failure mode regarding demand shocks is a sufficiently significant and well-documented bottleneck in predictive-prescriptive supply chain modeling.

### Approved Open Questions
- Robustness to extreme demand shocks: Failure cases during demand shocks are critical bottlenecks for the deployment of predictive-prescriptive systems in real-world supply chains where resilience against tail-end risks is essential.

### Rejected Candidates
- [concept] HAF-DS (`haf-ds`) - paper_local: This is a specific framework instantiation of a common hybrid predictive-prescriptive architectural pattern rather than a reusable core concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.21567)
- [PDF](https://arxiv.org/pdf/2604.21567)

