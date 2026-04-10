---
# CSL-compatible fields
title: "ASTRAFier: A Novel and Scalable Transformer-based Stellar Variability Classifier"
author:
  - literal: "Paul F. X. Gregory"
  - literal: "Jeroen Audenaert"
  - literal: "Mykyta Kliapets"
  - literal: "Daniel Muthukrishna"
  - literal: "Andrew Tkachenko"
  - literal: "Marek Skarka"
  - literal: "Marc Hon"
  - literal: "George R. Ricker"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07437"

# Custom fields
paper_id: "2604.07437"
paper_source: "arxiv"
domain: "time-series"
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
processed_at: "2026-04-10T15:30:31Z"
created_at: "2026-04-10T15:30:31Z"
---

# ASTRAFier: A Novel and Scalable Transformer-based Stellar Variability Classifier

**Authors**: Paul F. X. Gregory, Jeroen Audenaert, Mykyta Kliapets, Daniel Muthukrishna, Andrew Tkachenko, Marek Skarka, Marc Hon, George R. Ricker
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07437](https://arxiv.org/abs/2604.07437)

## Summary

ASTRAFier is a novel, end-to-end Transformer-based architecture designed for stellar variability classification, which integrates BiLSTM and CNN components to process raw photometric light curves. By removing the need for manual feature engineering, the model provides a scalable and efficient framework for large-scale astronomical data analysis. The model's effectiveness is validated on Kepler and TESS datasets, achieving high classification accuracy, and its practical utility is demonstrated through the classification of 2.8 million TESS light curves and the release of a new stellar variability catalog.

## Key Contributions

- Introduces ASTRAFier, a hybrid Transformer, BiLSTM, and CNN model for light curve classification that eliminates the need for manual feature engineering.
- Achieves 94.26% classification accuracy on Kepler data and 88.22% on TESS data.
- Demonstrates scalability by classifying approximately 2.8 million TESS light curves and releasing the resulting catalog.

## Open Questions & Future Work

- [[overfitting-in-small-labeled-astronomical-datasets]]
- [[scaling-transformer-models-to-long-sequences]]

## Archivist Review

The paper introduces a domain-specific model (ASTRAFier) that combines existing architectural components, which does not merit a new standalone concept note as it is an application rather than a methodological contribution. However, the identified challenges regarding overfitting in small labeled scientific datasets and the computational limitations of Transformers on long-range light curve sequences represent significant, recurring open research questions in time-series analysis and were approved accordingly. The Kepler and TESS datasets were rejected as they are standard, broad-utility astronomical benchmarks already widely utilized and not unique to this specific research work.

### Approved Open Questions
- Overfitting in astronomical classification: Scaling classification accuracy without proportional increases in human-labeled data is a fundamental bottleneck in high-throughput astronomical surveys.
- Scalability to long sequences: Efficiently handling longer temporal sequences is crucial for maximizing scientific throughput in future high-cadence space missions.

### Rejected Candidates
- [concept] ASTRAFier (`astrafier`) - subcomponent_of_broader_mechanism: This is a specific model implementation (a hybrid architecture) rather than a reusable architectural pattern or methodology; the individual components (BiLSTM, CNN, Transformer) are well-known, and the combination is a domain-specific instance.

## Links

- [Abstract](https://arxiv.org/abs/2604.07437)
- [PDF](https://arxiv.org/pdf/2604.07437)

