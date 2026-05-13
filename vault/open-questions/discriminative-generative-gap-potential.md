---
created_at: '2026-05-13T05:24:07Z'
source_papers:
- '[[arxiv-260511978-on-predicting-the-post-training-potential-of-pre-trained-llm]]'
title: Discriminative-Generative Gap Potential
---

**Background:** The performance of pre-trained language models on downstream tasks is heavily dependent on post-training, yet predicting this potential before costly alignment remains a significant research challenge. Current base-model evaluation techniques correlate poorly with the actual generative performance achieved after fine-tuning.

**Question / Future Work:** Future research must determine whether discriminative capability is a sufficient condition for generative potential across open-ended tasks and if models proficient at discriminating high-quality output can be consistently aligned. Validating this relationship is essential for ensuring that using discriminative proxies for foundation model selection does not result in systemic alignment failure.

**Why It Matters:** Defining the limits of using discriminative proxies to predict generative downstream performance is critical for the reliability of compute-efficient model development.

**Evidence:** Our core premise relies on the GD-Potential hypothesis: that the ability to discriminate quality predicts the ability to generate it. While our experiments show a strong correlation... this relationship may not hold linearly in all scenarios.