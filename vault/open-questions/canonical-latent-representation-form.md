---
created_at: '2026-04-28T05:13:22Z'
modified_at: '2026-04-29T05:12:59Z'
source_papers:
- '[[arxiv-260424662-information-bottleneck-for-learning-the-phase-space-of-dynam]]'
title: Canonicalizing Learned Latent Representations
---

**Background:** The latent representation learned by dynamical systems modeling methods like DySIB is defined only up to a smooth invertible reparameterization (gauge freedom).

**Question / Future Work:** It remains an open question to establish a canonical form for these latent representations to enable direct comparison between models, as current evaluations rely on probe networks which require ground-truth labels that are often unavailable in practice. Developing a transformation-invariant canonical form or a universal normalization technique is necessary for general model comparison and validation.

**Why It Matters:** This is fundamental for the scalability of latent-space discovery methods, as it would enable validation and cross-comparison of learned physical models without needing external ground-truth supervisory signals.

**Evidence:** A canonical form into which any equivalent representation could be transformed would resolve this. One natural candidate, in the spirit of recent geometry-based reconstruction approaches [76], is to diagonalize the linear part of the latent transition operator and order its eigenvalues, giving a normal-mode coordinate system. Whether this normal-mode form is enough in general, or whether a more flexible construction such as a normalizing flow [43] on top of the encoder is needed, remains open.