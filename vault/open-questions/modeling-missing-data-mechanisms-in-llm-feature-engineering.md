---
created_at: '2026-04-27T05:11:06Z'
source_papers:
- '[[arxiv-260422534-featehr-llm-leveraging-large-language-models-for-feature-eng]]'
title: Modeling Missing Data Mechanisms
---

**Background:** Large Language Models (LLMs) used for automated feature engineering in electronic health records (EHR) generate code based on clinical metadata, but they do not account for the underlying statistical mechanisms behind missing data. Clinical measurements are often missing for reasons that carry diagnostic information, rather than occurring at random.

**Question / Future Work:** Future research is needed to develop LLM-based feature engineering frameworks that explicitly incorporate statistical missingness mechanisms (e.g., distinguishing between data missing at random and data missing not at random) during the feature code generation process. Current methods treat missing values primarily as structural sparsity in the observation process, potentially losing diagnostic context regarding why certain clinical measurements were not performed.

**Why It Matters:** Modeling the mechanism of missingness is critical for clinical decision support, as the decision to order a test is often correlated with the patient's condition, and ignoring this may lead to biased predictions.