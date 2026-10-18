---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Communicating Uncertainty in AI-Supported Nurse Scheduling: Expert Co-Design and Evaluation of an Explainable AI Prototype"
description: "This paper explores the design and evaluation of an explainable AI (XAI) prototype for nurse scheduling, a complex optimization task in healthcare. Through an iterative co-design process and a mixed-methods study involving expert users and eye tracking, the researchers investigated how uncertainty communication and AI explanations affect professional decision-making. The results indicate a significant challenge: uncertainty in forecasts is often misinterpreted and lowers confidence, while explanations—though well-received—fail to increase advice acceptance. The study culminates in eight design implications aimed at creating more effective human-AI collaboration tools for the healthcare sector."
resource: "https://arxiv.org/abs/2610.18679"
tags:
  - "healthcare-ai"
  - "explainable-ai"
  - "uncertainty-quantification"
  - "decision-support"
  - "resource-allocation"
  - "human-computer-interaction"
  - "forecasting"
timestamp: "2026-10-18T00:54:36Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Alice Rollwagen"
  - literal: "Emily Schiller"
  - literal: "Anton Hummel"
  - literal: "Kathrin Ebertsch"
  - literal: "Andreas Riener"
  - literal: "Jan-Philipp Steghöfer"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18679"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "uncertainty-communication-optimization"
    description: "How can uncertainty be communicated in high-stakes environments like healthcare to prevent misinterpretation and avoid eroding decision-maker confidence? Research is needed to identify presentation formats—whether visual, verbal, or numerical—that effectively bridge the gap between statistical probability and human intuition."
  - name: "xai-perception-performance-gap"
    description: "Why do positive perceptions of AI explanations not translate into higher advice acceptance or confidence, and what specific types of explanations are required to bridge this gap? This involves distinguishing between 'satisfying' explanations and 'actionable' ones that provide utility for expert tasks."
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:54:36Z"
created_at: "2026-10-18T00:54:36Z"
---

# Communicating Uncertainty in AI-Supported Nurse Scheduling: Expert Co-Design and Evaluation of an Explainable AI Prototype

**Authors**: Alice Rollwagen, Emily Schiller, Anton Hummel, Kathrin Ebertsch, Andreas Riener, Jan-Philipp Steghöfer
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18679](https://arxiv.org/abs/2610.18679)

## Summary

This paper explores the design and evaluation of an explainable AI (XAI) prototype for nurse scheduling, a complex optimization task in healthcare. Through an iterative co-design process and a mixed-methods study involving expert users and eye tracking, the researchers investigated how uncertainty communication and AI explanations affect professional decision-making. The results indicate a significant challenge: uncertainty in forecasts is often misinterpreted and lowers confidence, while explanations—though well-received—fail to increase advice acceptance. The study culminates in eight design implications aimed at creating more effective human-AI collaboration tools for the healthcare sector.

## Key Contributions

- Developed an AI-supported decision support system (DSS) prototype for nurse scheduling using a human-centered co-design approach with healthcare experts.
- Conducted a mixed-methods user study utilizing eye tracking, thematic analysis, and questionnaires to evaluate expert interaction with AI forecasts and explanations.
- Identified that uncertainty communication in staffing forecasts is frequently misinterpreted by professionals and can lead to reduced decision confidence.
- Demonstrated that while AI explanations are positively perceived, they do not necessarily increase advice acceptance or decision confidence in high-stakes healthcare scheduling.
- Formulated eight specific design implications for improving transparency and effectiveness in AI-supported healthcare decision-making tools.

## Limitations

The study's findings are based on a specific prototype and a limited pool of expert users; the generalizability to other medical domains or different AI model architectures remains to be tested.

## Open Questions & Future Work

- [[uncertainty-communication-optimization]]
- [[xai-perception-performance-gap]]

## Archivist Review

The paper is an empirical HCI study focused on user interaction with AI-supported decision tools. It does not introduce new machine learning architectures or named datasets. Therefore, no concepts or datasets were approved. Two open questions were approved as they identify fundamental bottlenecks in the communication of uncertainty and the utility of explainable AI (XAI) that are highly relevant to the broader field of human-AI collaboration in expert domains.

### Approved Open Questions
- Uncertainty Communication Gap in Experts: Understanding how to present probabilistic data is critical for the safe and effective deployment of AI in clinical and operational healthcare settings.
- The XAI Perception-Performance Gap: This highlights a potential failure in current XAI strategies to provide 'actionable' explanations that truly support expert decision-making rather than just providing post-hoc justification.

### Rejected Candidates
- [concept] Uncertainty Misinterpretation in Healthcare (`uncertainty-misinterpretation-in-healthcare`) - not_reusable: This is an empirical finding from a user study rather than a reusable machine learning architecture, technique, or representation.
- [concept] Nurse Scheduling Decision Support Prototype (`nurse-scheduling-decision-support-prototype`) - paper_local: The prototype is a specific system implementation designed for the study's evaluation rather than a generalizable framework or model.

## Links

- [Abstract](https://arxiv.org/abs/2610.18679)
- [PDF](https://arxiv.org/pdf/2610.18679)

