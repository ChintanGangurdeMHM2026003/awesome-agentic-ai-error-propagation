# GitHub Implementations

This file contains high-quality GitHub repositories relevant to Agentic AI Error Propagation.

Each repository will be evaluated based on:

- Documentation quality
- Source-code availability
- Recent maintenance or activity
- Examples or tutorials
- Reproducibility
- License
- Connection to a research paper or recognized project
- Relevance to the research topic

## 1. AgentDebug

**Repository:** [AgentDebug](https://github.com/ulab-uiuc/AgentDebug)

**What it implements:** A debugging framework for identifying root-cause failures in LLM agent trajectories and providing corrective feedback.

**Why relevant:** Directly addresses agent error detection, root-cause diagnosis, and recovery from failures in multi-step agent tasks.

---

## 2. AgentBench

**Repository:** [AgentBench](https://github.com/THUDM/AgentBench)

**What it implements:** A comprehensive benchmark and evaluation framework containing multiple interactive environments for evaluating LLM agents.

**Why relevant:** Its multi-turn interactive environments provide a practical setting for studying reasoning, decision-making, and failures across multi-step agent trajectories.

---

## 3. WebArena

**Repository:** [WebArena](https://github.com/web-arena-x/webarena)

**What it implements:** A realistic, reproducible, and self-hostable web environment for building and evaluating autonomous agents.

**Why relevant:** Its long-horizon web tasks allow researchers to study failures that occur across sequences of dependent browser actions.

---

## 4. AgentDojo

**Repository:** [AgentDojo](https://github.com/ethz-spylab/agentdojo)

**What it implements:** A dynamic environment for evaluating prompt-injection attacks and defenses in LLM agents.

**Why relevant:** Demonstrates how untrusted or malicious information encountered during agent execution can influence subsequent actions and decisions.

---

## 5. WebShop

**Repository:** [WebShop](https://github.com/princeton-nlp/WebShop)

**What it implements:** A simulated e-commerce environment for evaluating grounded language agents performing web-based shopping tasks.

**Why relevant:** Agents perform multiple navigation and interaction steps, making the environment useful for studying trajectory-level failures and the effects of incorrect intermediate actions.

---

## 6. SWE-agent

**Repository:** [SWE-agent](https://github.com/SWE-agent/SWE-agent)

**What it implements:** An autonomous software-engineering agent that uses tools to inspect repositories, modify code, and attempt to resolve real GitHub issues.

**Why relevant:** Its iterative code editing, execution, and debugging workflow provides a realistic environment for studying how errors can propagate across multiple agent steps.
