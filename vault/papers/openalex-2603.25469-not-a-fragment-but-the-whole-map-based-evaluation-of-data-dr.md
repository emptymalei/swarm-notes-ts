---
# CSL-compatible fields
title: "Not a fragment, but the whole: Map-based evaluation of data-driven Fire Danger Index models"
author:
  - literal: "Shahbaz Alvi"
  - literal: "Italo Epicoco"
  - literal: "José María Costa-Saura"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25469"

# Custom fields
paper_id: "2603.25469"
paper_source: "openalex"
domain: "other"
tags:
  - "forecasting"
  - "evaluation metrics"
  - "ensemble methods"
architectures:
  []
datasets:
  []
concept_slugs:
  - "map-based-fdi-evaluation"
  - "false-positive-reduction-operational-ml"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:17:14Z"
created_at: "2026-03-29T20:17:14Z"
---

# Not a fragment, but the whole: Map-based evaluation of data-driven Fire Danger Index models

**Authors**: Shahbaz Alvi, Italo Epicoco, José María Costa-Saura
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25469](https://arxiv.org/abs/2603.25469)

## Summary

This paper addresses the inadequacy of standard machine learning classifier metrics for evaluating operational Fire Danger Index (FDI) forecasting models, which often overlook the critical impact of false positives. The authors propose a novel, map-based evaluation paradigm explicitly designed to align model performance with real-world decision-making processes in forest fire management. The study systematically assesses model accuracy alongside the crucial aspect of false alarm rates, which standard evaluation often neglects. Finally, the work demonstrates that utilizing an ensemble of machine learning models yields superior performance by simultaneously improving fire identification capability and reducing costly false positives.

## Key Contributions

- Proposal of a novel, map-based evaluation method for Fire Danger Index (FDI) models that aligns performance metrics with real-world operational decision-making.
- Systematic assessment of model performance focusing on accurate fire identification while rigorously quantifying and penalizing false positive rates (false alarms).
- Demonstration that ensembling machine learning models improves the balance between correct fire identification and the reduction of false positives in FDI forecasting.

## Limitations

The abstract does not explicitly detail limitations, but the focus on FDI suggests limitations might involve generalization across different geographical/climatic regions or the specific set of predictors used.

## Open Questions & Future Work

- [[optimal-cnn-depth-false-positive-rejection]]

## Key Concepts

- [[map-based-fdi-evaluation]]: A novel evaluation methodology for Fire Danger Index (FDI) models that incorporates spatial mapping and operational decision-making context, explicitly considering the impact of false positives.
- [[false-positive-reduction-operational-ml]]: A specific evaluation focus on minimizing false alarms (false positives) in a fire danger forecasting context due to their critical relevance in operational decision-making.

## Archivist Review

Two core concepts were approved as they represent novel, reusable methodological contributions: a map-based evaluation scheme aligned with operational decisions and the explicit focus on false positive reduction as a primary goal. One open question was approved, as it highlights an unresolved mechanistic finding regarding optimal model depth for confident 'negative' predictions, which is important for high-stakes classification. Other candidates, such as general ensemble methods or the domain-specific FDI forecasting, were rejected for being too generic or too localized, respectively.

### Approved Concepts
- Map-based Fire Danger Index Evaluation: This is the core methodological contribution, addressing the gap between standard ML metrics and operational relevance for fire forecasting.
- False Positive Reduction in Fire Prediction: Explicitly framing false positive rate reduction as a primary operational goal distinguishes this work from standard accuracy-focused ML evaluation.

### Approved Open Questions
- Optimal CNN Depth for No-Fire Confidence: Identifying the optimal network depth is crucial for balancing fire detection (high recall) with false positive rejection (confident no-fire flagging), which directly impacts operational trust and resource allocation.

### Rejected Candidates
- [concept] Ensemble Methods in FDI Forecasting (`ensemble-methods-forecasting`) - not_novel: The use of ensemble methods in machine learning is too generic to warrant a specific note, despite its application here.
- [concept] Fire Danger Index Forecasting (`fire-danger-index-forecasting`) - paper_local: This is a domain-specific application, not a reusable general ML concept or method.
- [concept] Daily FDI Model Evaluation Paradigm (`daily-fdi-model-evaluation-paradigm`) - subcomponent_of_broader_mechanism: This is too specific to the paper's local framing (Daily FDI) and is subsumed by the 'Map-based Fire Danger Index Evaluation' concept.

## Links

- [Abstract](https://arxiv.org/abs/2603.25469)
- [PDF](https://arxiv.org/pdf/2603.25469)

