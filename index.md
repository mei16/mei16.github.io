---
title: Applied AI Scientist & Engineer
---

# Applied AI Scientist & Engineer

**Research Focus: Long-term Memory · Context Engineering · Personalized AI**

My background is in machine learning, information retrieval, search ranking, recommendation, and personalization. I am exploring how these foundations can help AI agents remember, retrieve, organize, and continuously improve their context over time.

[GitHub](https://github.com/mei16) · [X](https://x.com/yunzhongliu)

---

## Personal Memory Lab: Long-term Memory and Context Engineering for AI Agents

*Research project — in progress; experiments are planned, not yet reported.*

### Motivation

An AI agent's effectiveness depends not only on its underlying model, but also on the information available to it at the right moment. As agents accumulate experience, selecting relevant memories, resolving outdated information, and adapting context to individual users become important research problems.

My goal is to investigate these problems through reproducible experiments, drawing on information retrieval, ranking, personalization, and feedback-driven optimization.

### Research questions

- **Memory formation:** What should an agent retain, summarize, update, or forget?
- **Memory retrieval and ranking:** How should relevance, recency, importance, and user intent influence retrieval?
- **Personalized context engineering:** How can an agent construct useful context under a limited token budget?
- **Context evolution:** Can reflection and feedback improve memory and context policies over time?

### Experimental roadmap

1. Establish baselines using public or synthetic multi-session conversation datasets.
2. Compare lexical, dense, and hybrid retrieval with different ranking strategies.
3. Evaluate structured memory, temporal updates, and context selection under controlled token budgets.
4. Explore feedback-driven optimization inspired by GEPA (Reflective Prompt Evolution) and ACE (Agentic Context Engineering).

Evaluation will consider retrieval quality, downstream task accuracy, temporal consistency, personalization, latency, and token cost. Comparisons will use consistent models and held-out test cases where possible.

### Planned outputs

I intend to share reproducible code, experimental findings, technical notes, and research questions as the project develops. Public experiments will use public or synthetic data, independent of proprietary systems and private user records.

The central question is: **How can AI agents use experience to construct better context for their next task?**
