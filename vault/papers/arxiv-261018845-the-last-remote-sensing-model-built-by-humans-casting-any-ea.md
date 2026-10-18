---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "The Last Remote Sensing Model Built by Humans? Casting Any Earth Observation Task as Recursive Self-Improvement"
description: "This paper proposes a shift in Earth Observation (EO) from manual model design to an automated agentic workflow. By defining any EO task through a 'harness' (available tools/data) and a 'verifier' (success criteria), the authors enable a general-purpose coding agent to build and recursively improve models. The approach unifies diverse problems like domain adaptation and low-shot learning into a single framework, outperforming current state-of-the-art models across six benchmarks—ranging from ship detection to canopy height estimation—while using a fraction of the traditional training data."
resource: "https://arxiv.org/abs/2610.18845"
tags:
  - "ai-agents"
  - "agentic-workflow"
  - "computer-vision"
  - "spatio-temporal-modeling"
  - "foundation-models"
  - "self-supervised-learning"
  - "time-series-analysis"
timestamp: "2026-10-18T00:53:01Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Sijie Zhao"
  - literal: "Zeqi Zhou"
  - literal: "Heli Qi"
  - literal: "Xuanchao Fu"
  - literal: "Zhuo Zheng"
  - literal: "Junshi Xia"
  - literal: "Junjue Wang"
  - literal: "Weihao Xuan"
  - literal: "Naoto Yokoya"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18845"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "harness-and-verifier-paradigm"
    description: "An Earth Observation framework that abstracts model development into a harness (available data/tools) and a verifier (success criteria) to enable agentic automation."
datasets:
  []
open_questions:
  - name: "noisy-verifier-stability-in-agentic-loops"
    description: "How do recursive agentic workflows maintain stability and avoid feedback loops of error propagation when the verifiers (e.g., physical models or sparse labels) are themselves noisy or biased?"
  - name: "agent-discovery-of-novel-inductive-biases"
    description: "Can agents discover novel, domain-specific inductive biases—particularly for multi-sensor fusion (SAR, optical, multispectral)—that human experts have not yet identified?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:53:01Z"
created_at: "2026-10-18T00:53:01Z"
---

# The Last Remote Sensing Model Built by Humans? Casting Any Earth Observation Task as Recursive Self-Improvement

**Authors**: Sijie Zhao, Zeqi Zhou, Heli Qi, Xuanchao Fu, Zhuo Zheng, Junshi Xia, Junjue Wang, Weihao Xuan, Naoto Yokoya
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18845](https://arxiv.org/abs/2610.18845)

## Summary

This paper proposes a shift in Earth Observation (EO) from manual model design to an automated agentic workflow. By defining any EO task through a 'harness' (available tools/data) and a 'verifier' (success criteria), the authors enable a general-purpose coding agent to build and recursively improve models. The approach unifies diverse problems like domain adaptation and low-shot learning into a single framework, outperforming current state-of-the-art models across six benchmarks—ranging from ship detection to canopy height estimation—while using a fraction of the traditional training data.

## Key Contributions

- Introduces the Harness and Verifier paradigm to cast any Earth Observation task as a recursive self-improvement problem solvable by agents.
- Demonstrates a general-purpose coding agent that automatically designs training recipes and tunes models across diverse sensor modalities (optical, SAR, multispectral).
- Achieves state-of-the-art results on six major EO benchmarks, outperforming human-built models while requiring significantly less labeled data (e.g., 11% for land-cover mapping).

## Limitations

The paradigm relies heavily on the availability of reliable 'verifiers' (benchmarks or physical models), and its performance is tied to the capabilities of the underlying general-purpose coding agent.

## Open Questions & Future Work

- [[noisy-verifier-stability-in-agentic-loops]]
- [[agent-discovery-of-novel-inductive-biases]]

## Key Concepts

- [[harness-and-verifier-paradigm]]: An Earth Observation framework that abstracts model development into a harness (available data/tools) and a verifier (success criteria) to enable agentic automation.

## Archivist Review

The approved concept 'Harness and Verifier Paradigm' captures the core methodological shift proposed by the paper, which unifies disparate Earth Observation tasks into a single agentic workflow. This abstraction is highly reusable across scientific machine learning. The approved open questions address critical bottlenecks in the stability of recursive loops and the potential for agents to surpass human-designed inductive biases, both of which are central to the future of AI for Earth Observation. Generic references to benchmarks and paper-local implementation details were rejected.

### Approved Concepts
- Harness and Verifier Paradigm: This paradigm shifts the focus of Remote Sensing from manual architecture design to task-level definition, allowing for the automation of model development and recursive self-improvement.

### Approved Open Questions
- Stability Under Noisy Verification: In real-world Earth Observation, 'ground truth' is often imperfect; understanding agent robustness to noise is critical for the deployment of these autonomous systems.
- Agent-Discovery of Novel Inductive Biases: Discovery of new inductive biases could lead to fundamental breakthroughs in how complex geophysical signals are processed and unified.

### Rejected Candidates
- [concept] Recursive Self-Improving EO Agent (`recursive-eo-agent`) - subcomponent_of_broader_mechanism: This is a specific implementation of the Harness and Verifier paradigm rather than a distinct conceptual framework.
- [dataset] Earth Observation Benchmarks (`earth-observation-benchmarks`) - generic: The abstract refers to six benchmarks generically without naming specific, reusable datasets.

## Links

- [Abstract](https://arxiv.org/abs/2610.18845)
- [PDF](https://arxiv.org/pdf/2610.18845)

