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
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  - "kepler-tess-stellar-light-curves"
concept_slugs:
  []
dataset_slugs:
  - "kepler-tess-stellar-light-curves"
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:47:30Z"
created_at: "2026-04-11T04:47:30Z"
---

# ASTRAFier: A Novel and Scalable Transformer-based Stellar Variability Classifier

**Authors**: Paul F. X. Gregory, Jeroen Audenaert, Mykyta Kliapets, Daniel Muthukrishna, Andrew Tkachenko, Marek Skarka, Marc Hon, George R. Ricker
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07437](https://arxiv.org/abs/2604.07437)

## Summary

ASTRAFier is an end-to-end Transformer-based classification framework designed for stellar light curve analysis without the need for manual feature engineering. By combining BiLSTM and CNN components, the model achieves high classification accuracy on benchmark datasets from the Kepler and TESS missions. The authors demonstrate the system's scalability by processing approximately 2.8 million light curves and releasing the resulting catalog for the astronomical community.

## Key Contributions

- Introduces ASTRAFier, a Transformer-based architecture that integrates BiLSTM and CNN modules for end-to-end stellar light curve classification.
- Eliminates the need for manual feature engineering by processing raw time series data directly.
- Demonstrates large-scale efficacy by classifying 2.8 million TESS light curves and releasing a public stellar variability catalog.

## Open Questions & Future Work

- [[self-supervised-astronomical-foundation-models]]

## Archivist Review

The paper proposes a specific architectural combination (Transformer + BiLSTM + CNN) for stellar classification, which is treated as a local implementation detail rather than a distinct, reusable paradigm shift. I approved the Kepler and TESS datasets as they represent a massive, shared standard resource in the domain, and identified the transition to self-supervised astronomical foundation models as a key, tracking-worthy research direction. Other candidates were rejected for being domain-specific implementation challenges rather than foundational scientific questions.

### Approved Open Questions
- Self-supervised Foundation Models for Astronomy: Addressing the dependence on labeled data is a fundamental bottleneck in scaling machine learning models to the millions of light curves produced by modern space missions.

### Rejected Candidates
- [open_question] Modeling Extended Mission Light Curves (`modeling-extended-mission-light-curves`) - other: This is a routine technical optimization problem regarding input length and sequence processing rather than a fundamental research bottleneck.

## Datasets

- [[kepler-tess-stellar-light-curves]]

## Links

- [Abstract](https://arxiv.org/abs/2604.07437)
- [PDF](https://arxiv.org/pdf/2604.07437)

