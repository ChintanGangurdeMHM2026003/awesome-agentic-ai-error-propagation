# Awesome Agentic AI Error Propagation

A curated collection of research papers, datasets, tools, implementations, and learning resources related to cascading failures and error propagation in multi-step autonomous AI agents. The repository focuses on understanding how errors introduced during planning, reasoning, memory, tool use, and multi-agent interaction can propagate through subsequent steps of an agent trajectory.

## Contents

- [Overview](#overview)
- [AI-Assisted Research Paper](#ai-assisted-research-paper)
- [Citation Integrity Audit](#citation-integrity-audit)
- [Survey and Failure Analysis](#survey-and-failure-analysis)
- [Foundational Agent Methods](#foundational-agent-methods)
- [Recent Research](#recent-research)
- [Benchmarks and Evaluation](#benchmarks-and-evaluation)
- [Multi-Agent Systems](#multi-agent-systems)
- [Safety and Reliability](#safety-and-reliability)
- [Datasets](#datasets)
- [Tools and Libraries](#tools-and-libraries)
- [GitHub Implementations](#github-implementations)
- [Tutorials and Learning Resources](#tutorials-and-learning-resources)
- [License](#license)

## Overview

Autonomous AI agents use large language models to reason, plan, use external tools, interact with environments, and complete tasks over multiple steps. Unlike a single-turn language model application, an agentic system produces intermediate decisions whose outputs can become inputs to later stages of the task. This makes reliability a system-level problem rather than only a question of individual model accuracy.

Error propagation occurs when an incorrect plan, action, observation, memory item, or intermediate conclusion is accepted by later stages and influences subsequent decisions. A small error introduced early in an agent trajectory can therefore lead to additional incorrect actions and eventually cause the entire task to fail. In multi-agent systems, errors can also propagate between agents through messages, shared memory, delegated subtasks, or shared state.

Research in this area investigates how agent failures can be classified, detected, localized, evaluated, and corrected. Important research directions include long-horizon agent evaluation, tool-use reliability, self-correction, reflection, memory, multi-agent coordination, prompt-injection safety, and automated debugging. Benchmarks such as AgentBench, WebArena, WebShop, GAIA, SWE-bench, and ToolSandbox provide environments for evaluating multi-step agent behavior.

This repository organizes research resources around these themes to help researchers and students understand the causes and consequences of cascading failures and explore methods for making autonomous AI agents more reliable.

## AI-Assisted Research Paper

[View the AI-Assisted Research Paper](paper/AI_Assisted_Research_Paper.pdf)

This paper was prepared as part of the earlier AI-assisted research activity on the same research topic.

## Citation Integrity Audit

[View the Citation Integrity Audit](citation-audit/Citation_Integrity_Audit.pdf)

The citation audit documents the verification of claims and references used in the AI-assisted research paper.

## Survey and Failure Analysis

Research focused directly on understanding and diagnosing agent failures.

## Foundational Agent Methods

Research introducing reasoning, acting, tool use, reflection, and self-correction methods.

## Recent Research

Recent work focusing on agent reliability, debugging, safety, and error propagation.

## Benchmarks and Evaluation

Benchmarks and environments used to evaluate autonomous and tool-using agents.

## Multi-Agent Systems

Research investigating communication, cooperation, delegation, and interaction between multiple AI agents.

## Safety and Reliability

Research addressing robustness, unsafe tool use, prompt injection, verification, and recovery from failures.

## Datasets

See [datasets/datasets.md](datasets/datasets.md).

## Tools and Libraries

See [tools/tools.md](tools/tools.md).

## GitHub Implementations

See [implementations/github-repositories.md](implementations/github-repositories.md).

## Tutorials and Learning Resources

See [tutorials/tutorials.md](tutorials/tutorials.md).

## License

This repository is licensed under the MIT License. See [LICENSE](LICENSE).
