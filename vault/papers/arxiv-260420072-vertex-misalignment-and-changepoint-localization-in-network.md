---
# CSL-compatible fields
title: "Vertex misalignment and changepoint localization in network time series"
author:
  - literal: "Tianyi Chen"
  - literal: "Mohammad Sharifi Kiasari"
  - literal: "Sijing Yu"
  - literal: "Youngser Park"
  - literal: "Avanti Athreya"
  - literal: "Vince Lyzinski"
  - literal: "Caree E Priebe"
  - literal: "Zachary Lubberts"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20072"

# Custom fields
paper_id: "2604.20072"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "network-analysis"
  - "changepoint-detection"
architectures:
  []
datasets:
  []
concept_slugs:
  - "euclidean-mirrors"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:08:15Z"
created_at: "2026-04-23T05:08:15Z"
---

# Vertex misalignment and changepoint localization in network time series

**Authors**: Tianyi Chen, Mohammad Sharifi Kiasari, Sijing Yu, Youngser Park, Avanti Athreya, Vince Lyzinski, Caree E Priebe, Zachary Lubberts
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20072](https://arxiv.org/abs/2604.20072)

## Summary

This paper investigates the robustness of changepoint localization in dynamic network time series when vertex correspondence is unknown or misspecified. Through two illustrative models, the authors demonstrate that the effectiveness of localization methods—ranging from average degree statistics to Euclidean mirrors—depends on whether the network changepoint information resides in the marginal or joint distributions of latent vertex positions. Their findings show that vertex misalignment can render certain localization tasks impossible to solve using standard graph matching or optimal transport, highlighting a critical limitation in current network inference practices.

## Key Contributions

- Identifies that vertex misalignment in dynamic network time series differentially impacts changepoint localization depending on whether information is stored in marginal versus joint distributions.
- Demonstrates that in certain network models, vertex misalignment induces localization errors that are fundamentally uncorrectable by standard graph matching or optimal transport techniques.
- Compares various localization procedures, from simple average degree statistics to Euclidean mirrors, revealing the sensitivity of these methods to underlying latent position structures.

## Open Questions & Future Work

- [[intermediate-network-dynamics-modeling]]

## Key Concepts

- [[euclidean-mirrors]]: A changepoint localization technique for network time series that utilizes latent position structure.

## Archivist Review

The paper provides a formal investigation into the sensitivity of network changepoint localization to vertex misalignment, distinguishing between marginal and joint information structures. I approved 'Euclidean Mirrors' as a distinct methodological concept and formulated a broader open question regarding the need for intermediate models, as the initial candidate was slightly overly specific to the 'London/Atlanta' model naming convention used in the paper. No datasets were approved as none were central to the contribution.

### Approved Concepts
- Euclidean Mirrors: The paper identifies Euclidean mirrors as a distinct modern procedure for changepoint localization in dynamic networks, contrasting it with simple statistics like average degree.

### Approved Open Questions
- Intermediate network dynamics modeling: Addressing this gap is essential for building network time series models that are both analytically tractable and representative of the complex dynamics observed in empirical data.

## Links

- [Abstract](https://arxiv.org/abs/2604.20072)
- [PDF](https://arxiv.org/pdf/2604.20072)

