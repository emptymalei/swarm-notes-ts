---
created_at: '2026-05-10T05:21:05Z'
source_papers:
- '[[arxiv-260505683-spectral-lens-activation-and-gradient-spectra-as-diagnostics]]'
title: Spectral Predictivity for Downstream Performance
---

**Background:** Spectral diagnostic measurements for LLMs, such as activation covariance and gradient SVD spectra, currently target pretraining validation loss as a performance metric.

**Question / Future Work:** It is unknown whether the identified early-training spectral-tail diagnostics, which currently forecast pretraining token efficiency, also predict downstream few-shot or zero-shot capability acquisition.

**Why It Matters:** This is critical for practitioners who are ultimately interested in the downstream utility of a model rather than the proxy metric of pretraining loss.

**Evidence:** The current efficiency target is pretraining validation loss rather than downstream capability, so extending the same early-tail diagnostic to zero-shot or few-shot behavior remains an open question.