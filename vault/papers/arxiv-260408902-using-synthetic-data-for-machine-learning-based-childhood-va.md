---
# CSL-compatible fields
title: "Using Synthetic Data for Machine Learning-based Childhood Vaccination Prediction in Narok, Kenya"
author:
  - literal: "Jimmy Bach"
  - literal: "Yang Li"
  - literal: "Yaqi Liu"
  - literal: "John Sankok"
  - literal: "Rose Kimani"
  - literal: "Carrie B. Dolan"
  - literal: "Julius N. Odhiambo"
  - literal: "Haipeng Chen"
issued:
  date-parts:
    - [2026, 4, 10]
url: "https://arxiv.org/abs/2604.08902"

# Custom fields
paper_id: "2604.08902"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "tabular-data"
  - "privacy-preserving-ml"
  - "healthcare-ai"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-13T05:11:03Z"
created_at: "2026-04-13T05:11:03Z"
---

# Using Synthetic Data for Machine Learning-based Childhood Vaccination Prediction in Narok, Kenya

**Authors**: Jimmy Bach, Yang Li, Yaqi Liu, John Sankok, Rose Kimani, Carrie B. Dolan, Julius N. Odhiambo, Haipeng Chen
**Date**: 2026-04-10
**Paper ID**: [arxiv:2604.08902](https://arxiv.org/abs/2604.08902)

## Summary

This paper addresses the challenge of limited and sensitive health data in nomadic populations by developing machine learning models for childhood vaccination prediction in Narok, Kenya. By digitizing 8 years of vaccination registry records, the authors train classification models to identify children at high risk of missing doses. Furthermore, they introduce a tabular diffusion-based synthetic data generation approach to preserve patient privacy, demonstrating that models trained on synthetic data perform comparably to those trained on real-world records.

## Key Contributions

- Digitized and curated 8 years of historical childhood vaccination records for the Maasai population in Narok County, Kenya.
- Demonstrated that XGBoost and Logistic Regression models can achieve over 90% F1-score in identifying children at risk of missing vaccinations.
- Validated that training models on tabular diffusion-based synthetic data (TabSyn) maintains predictive performance while ensuring patient privacy in resource-constrained environments.

## Open Questions & Future Work

- [[synthetic-data-longitudinal-clinical-utility]]

## Archivist Review

I have reviewed the paper and the candidate open question. The proposed concepts (e.g., tabular diffusion models) are well-established and do not warrant new entries, while the datasets are local and not reusable. The open question regarding the clinical utility of synthetic data for longitudinal health forecasting is a substantial research bottleneck and has been renamed to better reflect its generality.

### Approved Open Questions
- Synthetic Data Clinical Utility: This is technically significant because it addresses the inherent limits of current generative models in capturing long-term clinical dependencies, which is critical for the reliability of privacy-preserving clinical decision support systems.

## Links

- [Abstract](https://arxiv.org/abs/2604.08902)
- [PDF](https://arxiv.org/pdf/2604.08902)

