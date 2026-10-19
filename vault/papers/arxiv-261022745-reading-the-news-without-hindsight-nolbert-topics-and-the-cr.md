---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Reading the News Without Hindsight: NoLBERT Topics and the Cross-Section of Stock Returns"
description: "This paper investigates hindsight bias in financial news models by proposing NoLBERT, a transformer encoder pre-trained exclusively on historical data from 1976 to 1995. The authors adapt the model into a sentence encoder via contrastive fine-tuning and evaluate it against LDA and FinBERT on a corpus of 1.26 million articles to forecast returns for the 1,000 largest US stocks. Results indicate that while ensembling various readers produces a significant net Sharpe ratio, individual models often overfit, and extending the look-back window for attention features is crucial for predictive stability."
resource: "https://arxiv.org/abs/2610.22745"
tags:
  - "financial-time-series"
  - "large-language-models"
  - "time-series-forecasting"
  - "contrastive-learning"
  - "nlp"
  - "forecasting"
  - "transformer"
timestamp: "2026-10-19T04:36:52Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Kevin Foley"
  - literal: "Jonathan Hartadi"
  - literal: "Shivesh Prakash"
  - literal: "Charishma Takkallapalli"
  - literal: "Swapnil Vatsal"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22745"
paper_source: "arxiv"
architectures:
  - "transformer"
concepts:
  - name: "nolbert"
    description: "A transformer-based encoder pre-trained on historical text (1976-1995) to prevent data leakage during financial news sentiment analysis and return forecasting."
datasets:
  []
open_questions:
  - name: "disentangling-adaptation-vs-chronological-effects"
    description: "It remains unresolved whether the performance differences between point-in-time encoders (like NoLBERT) and modern sentence transformers (like MiniLM) are driven by the avoidance of look-ahead bias or by the unsupervised contrastive fine-tuning recipes applied to the former. Isloating these factors requires applying identical adaptation protocols to both classes of models to determine the true marginal utility of chronological pretraining in financial forecasting."
  - name: "dynamic-narrative-topic-refitting"
    description: "Investigating the impact of dynamically refitting topic models or updating embedding centroids over time is an open area for research. Current static models show a significant drop in coherence when applied to text outside their training window, and it is unknown if regular temporal updates would improve the stability or predictive power of narrative-based attention shocks."
skill: "GeneralMLSkill"
processed_at: "2026-10-19T04:36:52Z"
created_at: "2026-10-19T04:36:52Z"
---

# Reading the News Without Hindsight: NoLBERT Topics and the Cross-Section of Stock Returns

**Authors**: Kevin Foley, Jonathan Hartadi, Shivesh Prakash, Charishma Takkallapalli, Swapnil Vatsal
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22745](https://arxiv.org/abs/2610.22745)

## Summary

This paper investigates hindsight bias in financial news models by proposing NoLBERT, a transformer encoder pre-trained exclusively on historical data from 1976 to 1995. The authors adapt the model into a sentence encoder via contrastive fine-tuning and evaluate it against LDA and FinBERT on a corpus of 1.26 million articles to forecast returns for the 1,000 largest US stocks. Results indicate that while ensembling various readers produces a significant net Sharpe ratio, individual models often overfit, and extending the look-back window for attention features is crucial for predictive stability.

## Key Contributions

- Introduced NoLBERT, a pre-trained encoder that eliminates hindsight bias in financial news analysis by training strictly on text predating the evaluation period (1976-1995).
- Demonstrated that increasing the window for measuring 'attention shocks' from 5 to 63 trading days significantly improves the rank Information Coefficient (IC) across multiple NLP models.
- Identified a critical generalization gap in financial forecasting where the highest-scoring models on validation sets failed to achieve profitability in out-of-sample testing.
- Established that NoLBERT provides more stable topic representations for stock returns than modern counterparts like FinBERT while matching the predictive performance of LDA.

## Limitations

The model ensemble fails to outperform a price-only benchmark when adjusted for search bias, and individual models show significant susceptibility to overfitting during the validation phase.

## Open Questions & Future Work

- [[disentangling-adaptation-vs-chronological-effects]]
- [[dynamic-narrative-topic-refitting]]

## Key Concepts

- [[nolbert]]: A transformer-based encoder pre-trained on historical text (1976-1995) to prevent data leakage during financial news sentiment analysis and return forecasting.

## Archivist Review

I approved NoLBERT as it represents a significant methodological shift towards hindsight-free pre-training in financial NLP. The open questions regarding the disentanglement of data age from adaptation methods and the need for dynamic topic refitting are well-supported by the paper's findings on coherence degradation and generalization gaps. I rejected 'Attention Shocks' as it is a specific implementation detail for feature construction rather than a broadly reusable concept.

### Approved Concepts
- NoLBERT: Directly addresses hindsight bias in financial NLP by enforcing a strict temporal boundary on pre-training data, providing a more realistic baseline for financial backtesting than models like FinBERT.

### Approved Open Questions
- Disentangling Adaptation and Chronological Effects: Quantifying the specific impact of look-ahead bias versus architectural or adaptation gains is critical for designing valid backtests in financial machine learning.
- Dynamic Narrative Topic Refitting: Financial markets and their textual representations are non-stationary; determining effective methods for maintaining representation quality over long horizons is a significant engineering challenge.

### Rejected Candidates
- [concept] Attention Shocks (`attention-shocks`) - paper_local: The term 'attention shocks' is used here more as a descriptive variable name for specific feature engineering rather than a novel, reusable architecture or foundational technique.

## Links

- [Abstract](https://arxiv.org/abs/2610.22745)
- [PDF](https://arxiv.org/pdf/2610.22745)

