---
# CSL-compatible fields
title: "Synthetic data in cryptocurrencies using generative models"
author:
  - literal: "André Saimon S. Sousa"
  - literal: "Otto Pires"
  - literal: "Frank Acasiete"
  - literal: "Oscar M. Granados"
  - literal: "Valéria Loureiro da Silva"
  - literal: "Hugo Saba"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.16182"

# Custom fields
paper_id: "2604.16182"
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
processed_at: "2026-04-20T05:09:02Z"
created_at: "2026-04-20T05:09:02Z"
---

# Synthetic data in cryptocurrencies using generative models

**Authors**: André Saimon S. Sousa, Otto Pires, Frank Acasiete, Oscar M. Granados, Valéria Loureiro da Silva, Hugo Saba
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.16182](https://arxiv.org/abs/2604.16182)

## Summary

This paper addresses privacy and accessibility constraints in financial research by proposing a Conditional Generative Adversarial Network (CGAN) for synthesizing cryptocurrency price time series. The framework utilizes an LSTM-based generator and an MLP discriminator to model complex market dynamics while remaining computationally efficient. Empirical results across multiple crypto-assets confirm that the synthetic series successfully capture relevant temporal patterns and market trends. The approach serves as a viable, privacy-preserving tool for financial simulation, market behavior analysis, and anomaly detection tasks.

## Key Contributions

- Proposes a CGAN-based framework using an LSTM-based generator and MLP discriminator to synthesize cryptocurrency price time series.
- Demonstrates that the generative approach preserves key market dynamics and temporal patterns observed in real crypto-asset price data.
- Establishes that the proposed model provides a computationally efficient alternative for simulating financial data for tasks like anomaly detection and market analysis.

## Open Questions & Future Work

- [[gan-volatility-smoothing-limitation]]

## Archivist Review

I have approved the open question regarding GAN volatility smoothing, as this is a well-documented and persistent limitation in generative financial modeling that requires further research. I rejected the proposed concept of an 'LSTM-based CGAN' because it is a generic combination of established architectures rather than a distinct or novel methodological contribution.

### Approved Open Questions
- Reproducing volatility in GANs: Smoothing of volatility peaks renders synthetic data less useful for stress testing and risk management, where capturing extreme tail risk is crucial.

### Rejected Candidates
- [concept] LSTM-based CGAN for Crypto Synthesis (`lstm-cgan-for-crypto-synthesis`) - not_novel: The combination of an LSTM and a CGAN is a standard generative approach and does not constitute a distinct, novel architectural concept worthy of a permanent vault note.

## Links

- [Abstract](https://arxiv.org/abs/2604.16182)
- [PDF](https://arxiv.org/pdf/2604.16182)

