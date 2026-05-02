---
created_at: '2026-05-02T05:07:18Z'
source_papers:
- '[[arxiv-260428149-explainable-load-forecasting-with-covariate-informed-time-se]]'
title: Explaining Probabilistic Load Forecasts
---

**Background:** Probabilistic load forecasting provides essential information about predictive uncertainty, which is critical for risk-aware decision-making in power grid operations. Currently, most post-hoc explainability methods for TSFMs are focused on interpreting point forecasts.

**Question / Future Work:** The current SHAP-based explainability framework is limited to interpreting point forecasts (median predictions). Extending this framework to explain probabilistic forecasts and quantify the drivers of model uncertainty is necessary to support risk-sensitive operational decisions. Future work should investigate how to attribute uncertainty to specific temporal windows or input covariates to provide a more comprehensive understanding of the model's predictive reliability.

**Why It Matters:** Understanding not just the 'why' of a prediction, but also the 'why' behind the uncertainty, is vital for high-stakes infrastructure applications where safety margins and risk management are paramount. Point-forecast explanations alone may lead to overconfidence in model reliability.