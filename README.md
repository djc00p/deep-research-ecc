# 🔍 Deep Research

[![ClawHub Skill](https://img.shields.io/badge/ClawHub-Skill-blue)](https://clawhub.ai/djc00p/deep-research-ecc) [![Agent Skill](https://img.shields.io/badge/Agent-Skill-blue)](#) [![Citations](https://img.shields.io/badge/Citations--Required-blue.svg)](https://en.wikipedia.org/wiki/Wikipedia:Citing_sources) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Deep Research** produces thorough, cited research reports from multiple web sources — using search and fetch tools to gather, then synthesizing with evidence attribution attached to every claim.

The differentiator from a quick lookup is **citation discipline**. A research report without sources is an essay with extra confidence. This skill treats "insufficient data found" as a valid, respectable conclusion.

---

## 🎯 When to Activate

* User asks to research any topic in depth
* Competitive analysis, technology evaluation, or market sizing
* Due diligence on companies, investors, or technologies
* *"Research"*, *"deep dive"*, *"investigate"*, *"what's the current state of"*

---

## 🚀 Quick Start

1. **Clarify the goal** — learning, decision, or writing? The output shape depends on it
2. **Plan 3–5 research sub-questions**
3. **Execute multi-source search** using `web_search` (15–30 sources total)
4. **Deep-read 3–5 key sources** with `web_fetch`
5. **Synthesize** into a structured report with citations

---

## 📐 Key Concepts

* **Multi-source synthesis** — combine data from academic, official, and reputable news sources
* **Citation discipline** — every claim has a source; cross-reference critical facts
* **Recency focus** — prefer sources from the last 12 months
* **Separate fact from inference** — label estimates, projections, and opinions clearly
* **Acknowledge gaps** — say *"insufficient data found"* rather than hallucinate

---

## 🧭 The Five Principles in Practice

### Citation discipline

Not "according to some sources" — a specific claim maps to a specific source. When two sources disagree, the report says so and explains which is more credible and why.

### Fact vs. inference

```text
FACT:      Kraken's published fee schedule lists 0.26% taker on the standard tier.
INFERENCE: At $50K monthly volume, fees likely fall into a lower tier (~0.16%).
PROJECTION:At current growth, that volume crosses into the next tier by Q3.
```

Each label tells the reader exactly how much weight to put on the line.

### Acknowledging gaps

If the research turns up three sources for a claim and nothing for the counter-argument, the report says *"no published counter-argument found"* rather than quietly implying consensus.

---

## 🎯 Common Use Cases

* **Competitive landscapes** and market sizing
* **Technology evaluations** — *"Rust vs Go"*
* **Business strategy research** — *"bootstrapping SaaS"*
* **Current events** and trend analysis
* **Due diligence** on companies, products, or investors

---

## 📊 Report Shape

```text
## Executive Summary
[3–5 sentences answering the core question]

## Findings
### Sub-question 1
[Sourced claims, cross-referenced]

## Evidence
[Detailed source-by-source breakdown]

## Gaps & Conflicts
[Where sources disagree, where data is missing]

## Conclusions
[Labeled as fact, inference, or projection]
```

---

## 📚 References

* `references/workflow.md` — detailed 6-step workflow with the report template
* `references/examples.md` — example research queries and output formats

---

**Adapted from [everything-claude-code](https://github.com/affanm/everything-claude-code) by [@affaan-m](https://github.com/affaan-m) (MIT).**

**Published by [@djc00p](https://github.com/djc00p)**
