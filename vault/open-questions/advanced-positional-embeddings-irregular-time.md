---
created_at: '2026-03-29T20:15:47Z'
source_papers:
- '[[openalex-2603.25597-spatiotemporal-system-forecasting-with-irregular-time-steps]]'
title: Advanced Positional Embeddings for Irregularity
---

**Background:** The reliance on fixed, non-trainable sinusoidal positional embeddings to encode relative temporal order may limit its ability to accurately capture complex temporal relationships in irregular time series.

**Question / Future Work:** Explore and integrate advanced, learned positional embedding techniques, such as Attention with Linear Biases (ALiBi) or Rotary Position Embedding (RoPE), to enhance the model's ability to capture relative temporal relationships within the irregularly sampled sequences.

**Why It Matters:** Positional encodings are crucial for transformers on sequences, and adapting them for irregular time series—where standard methods can fail—is key to improving temporal modeling fidelity.

**Evidence:** To efficiently handle relative time embedding in irregular time series, future work could consider advanced positional embedding techniques, such as Attention with Linear Biases (ALiBi) [82] and Rotary Position Embedding (RoPE) [83], which can better capture relative temporal relationships without explicit positional encodings.