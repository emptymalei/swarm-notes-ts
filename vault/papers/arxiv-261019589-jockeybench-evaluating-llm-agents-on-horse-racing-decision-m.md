---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "JockeyBench: Evaluating LLM Agents on Horse-Racing Decision-Making"
description: "JockeyBench is a benchmark designed to evaluate LLM agents in the context of repeated event forecasting and high-stakes decision-making using historical Japanese horse racing data. The evaluation protocol incorporates time-gated evidence and priced tools to measure not only forecasting accuracy but also resource efficiency and net financial utility. The study compares two workflows—executing reusable LLM-written code versus per-race prompting—and finds that while the former is more cost-effective, all configurations struggle to achieve positive profitability. These results highlight a critical gap between predictive capability and real-world economic utility in current LLM agents."
resource: "https://arxiv.org/abs/2610.19589"
tags:
  - "llm-agents"
  - "llm-agent-evaluation"
  - "forecasting"
  - "time-series"
  - "decision-making"
  - "benchmarking"
  - "financial-time-series"
  - "risk-management"
timestamp: "2026-10-18T00:45:05Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Zhongwei Xie"
  - literal: "Xingsu Li"
  - literal: "Jingqiao Yu"
  - literal: "Zihao Wang"
  - literal: "Hong ChiTat"
  - literal: "Zhaowei Wang"
  - literal: "Weizhi Du"
  - literal: "Yuxuan Liu"
  - literal: "Huihao Jing"
  - literal: "Jiaxin Bai"
  - literal: "Yangqiu Song"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19589"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "jockeybench"
    description: "A benchmark and evaluation protocol for LLM agents focusing on repeated event forecasting and high-stakes decision-making."
  - name: "priced-tool-evaluation"
    description: "An evaluation paradigm that incorporates the monetary or resource costs of data acquisition and tool usage into the assessment of an agent's performance."
datasets:
  - name: "JockeyBench"
    description: "A benchmark dataset derived from 324 historical Japanese horse races, featuring time-gated evidence and priced information tools for evaluating LLM agent decision-making."
open_questions:
  - name: "llm-agent-market-efficiency-gap"
    description: "How can LLM agents be improved to identify and exploit predictive signals that are not already priced into competitive markets, particularly when research costs are accounted for?"
  - name: "selection-bias-calibration-reversal"
    description: "What causes the reversal of mean probability bias on selected actions compared to baseline forecasts, and how can agents maintain calibration during the transition from prediction to action selection?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:45:05Z"
created_at: "2026-10-18T00:45:05Z"
---

# JockeyBench: Evaluating LLM Agents on Horse-Racing Decision-Making

**Authors**: Zhongwei Xie, Xingsu Li, Jingqiao Yu, Zihao Wang, Hong ChiTat, Zhaowei Wang, Weizhi Du, Yuxuan Liu, Huihao Jing, Jiaxin Bai, Yangqiu Song
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19589](https://arxiv.org/abs/2610.19589)

## Summary

JockeyBench is a benchmark designed to evaluate LLM agents in the context of repeated event forecasting and high-stakes decision-making using historical Japanese horse racing data. The evaluation protocol incorporates time-gated evidence and priced tools to measure not only forecasting accuracy but also resource efficiency and net financial utility. The study compares two workflows—executing reusable LLM-written code versus per-race prompting—and finds that while the former is more cost-effective, all configurations struggle to achieve positive profitability. These results highlight a critical gap between predictive capability and real-world economic utility in current LLM agents.

## Key Contributions

- Introduced JockeyBench, a novel benchmark for evaluating LLM agents on repeated event forecasting using 324 historical Japanese horse races.
- Developed an evaluation protocol that integrates priced tools and research fees, allowing for the assessment of agents' resource use versus decision utility.
- Compared two distinct agent workflows (reusable LLM-written programs vs. per-race LLM forecasting), finding that reusable programs offer higher efficiency and mean profit.
- Identified a specific probability bias reversal in LLM agents, where the calibration of forecasts differs significantly for bets actually selected by the agent.

## Limitations

All tested agent configurations resulted in negative mean profit under realistic settlement rules (Capped-Kelly), suggesting significant remaining challenges in achieving profitability in efficient markets.

## Open Questions & Future Work

- [[llm-agent-market-efficiency-gap]]
- [[selection-bias-calibration-reversal]]

## Key Concepts

- [[jockeybench]]: A benchmark and evaluation protocol for LLM agents focusing on repeated event forecasting and high-stakes decision-making.
- [[priced-tool-evaluation]]: An evaluation paradigm that incorporates the monetary or resource costs of data acquisition and tool usage into the assessment of an agent's performance.

## Archivist Review

Approved JockeyBench and Priced Tool Evaluation as they represent the primary benchmark contribution and the novel economic evaluation methodology respectively. The open questions were approved because they highlight critical unresolved issues in market-based agent performance and decision-dependent calibration. Generic forecasting terms and standard time-series procedures were rejected to maintain the vault's focus on unique contributions.

### Approved Concepts
- JockeyBench: It provides a structured environment for evaluating LLM agents on repeated, time-sensitive decision-making with financial consequences.
- Priced Tool Evaluation: It introduces an economic dimension to agent evaluation by accounting for the cost of information acquisition relative to the utility of the resulting decision.

### Approved Open Questions
- Closing the Profitability Gap in Efficient Markets: Establishing profitability in efficient markets is the ultimate test for autonomous agents in financial and competitive domains.
- Probability Bias Reversal in Action Selection: Miscalibration during action selection leads to catastrophic risk management failures in high-stakes environments.

### Rejected Candidates
- [concept] Time-Gated Evidence (`time-gated-evidence`) - not_novel: Time-gating is a standard procedure in time-series and forecasting research to prevent data leakage and is not a novel contribution of this paper.
- [concept] Repeated Event Forecasting (`repeated-event-forecasting`) - generic: This is a broad problem category in statistics and machine learning rather than a specific mechanism or contribution introduced by the paper.

## Datasets

- [[JockeyBench]]

## Links

- [Abstract](https://arxiv.org/abs/2610.19589)
- [PDF](https://arxiv.org/pdf/2610.19589)

