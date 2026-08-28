# Datasets and Benchmarks

This file contains datasets and benchmarks relevant to Agentic AI Error Propagation.

Each resource will be evaluated and documented using the following information:

- Dataset or benchmark name
- Source
- Description
- Application
- Link
- Relevance to Agentic AI Error Propagation

The selected datasets and benchmarks will be verified before inclusion in the repository.

## 1. AgentErrorBench

**Source:** Zhu et al.

**Description:** AgentErrorBench is a benchmark introduced for studying and evaluating failures in LLM-based agents, using annotated agent trajectories from environments including ALFWorld, GAIA, and WebShop.

**Application:** Agent failure classification, root-cause analysis, error diagnosis, and debugging.

**Relevance:** It is directly relevant to this repository because it focuses on identifying and analyzing failures that occur during multi-step LLM agent execution.

**Link:** [AgentErrorBench / AgentDebug Paper](https://arxiv.org/abs/2509.25370)

---

## 2. AgentBench

**Source:** THUDM

**Description:** AgentBench is a multi-dimensional benchmark for evaluating LLMs as autonomous agents across eight interactive environments, including operating systems, databases, knowledge graphs, games, puzzles, ALFWorld, WebShop, and Mind2Web.

**Application:** Evaluating agent reasoning, planning, decision-making, and interaction with different environments.

**Relevance:** Its multi-turn interactive tasks make it useful for studying how errors during one stage of an agent trajectory can influence later decisions and task outcomes.

**Link:** [Official AgentBench Repository](https://github.com/THUDM/AgentBench)

---

## 3. WebArena

**Source:** WebArena Project

**Description:** WebArena is a realistic and reproducible web environment containing functional websites and long-horizon tasks designed for autonomous web agents.

**Application:** Training and evaluating autonomous web-navigation agents on realistic multi-step tasks.

**Relevance:** Its long-horizon web tasks provide an environment for studying accumulated errors and failures across sequences of dependent actions.

**Link:** [Official WebArena Repository](https://github.com/web-arena-x/webarena)

---

## 4. ToolSandbox

**Source:** Apple Machine Learning Research

**Description:** ToolSandbox is a stateful, conversational benchmark for evaluating LLM tool-use capabilities, including stateful tool execution and implicit dependencies between tool calls.

**Application:** Evaluating tool use, state-dependent behavior, conversational interaction, and intermediate as well as final task performance.

**Relevance:** Dependencies between tool calls make ToolSandbox particularly useful for studying how an incorrect intermediate state or tool result can influence subsequent agent actions.

**Link:** [Official ToolSandbox Paper](https://aclanthology.org/2025.findings-naacl.65/)

---

## 5. SWE-bench

**Source:** Princeton NLP

**Description:** SWE-bench is a benchmark containing real-world software engineering issues collected from GitHub. Given a codebase and an issue, an AI system must generate a patch intended to resolve the problem.

**Application:** Evaluating autonomous software-engineering agents on real-world coding and debugging tasks.

**Relevance:** SWE-bench involves multi-step reasoning, code modification, execution, and debugging, making it useful for studying how mistakes during one stage can affect subsequent stages and final task success.

**Link:** [Official SWE-bench Repository](https://github.com/SWE-bench/SWE-bench)
