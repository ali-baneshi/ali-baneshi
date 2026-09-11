# Ali Baneshi

**Independent Researcher · Quantitative Systems & Architecture**

I’m an independent researcher and self-taught R&D engineer working on quantitative finance, autonomous agents, and developer tools.

Most of my work starts before the code. I first try to understand the problem, define what the system is supposed to do, and identify what can actually be measured. From there, I turn the ideas into practical implementations and test them against their intended scope.

I’m particularly interested in systems where correctness, limitations, and failure cases matter as much as the final result.

## How I Work

### Research

I start by learning the fundamentals of the problem and looking at how others have approached it. I try to separate established knowledge from assumptions, then turn uncertain parts into questions that can be tested.

### Problem Definition

I define the problem before choosing a solution. This includes clarifying the scope, constraints, success criteria, and non-goals. A clear definition is often more valuable than an early implementation.

### System Design

I design systems around clear responsibilities, interfaces, and failure boundaries. When choosing an algorithm or technology, I consider correctness, complexity, performance, resource usage, and maintainability—not just whether it works in a simple example.

### Implementation and Validation

I turn design decisions into small, testable pieces of software. I use modern development tools when they are useful, when they are useful, but generated code is never treated as proof of correctness.

Testing, code review, deterministic checks, and reproducible experiments are used to find out whether an implementation behaves as intended.

The process is iterative. Implementation reveals weaknesses in the design, evaluation challenges the original assumptions, and the resulting evidence shapes the next version.

## Selected Projects

### defi-arbitrage-core · Python

Research infrastructure for analyzing DeFi arbitrage opportunities across multiple networks.

The project focuses on market modeling, route analysis, deterministic validation, and reproducible off-chain evaluation. Research and live execution are kept separate so that a simulated opportunity is not mistaken for a validated trading system.

### Exchange-Quant · Python

A market microstructure research project focused on forecasting future aggressor-side trade flow.

The forecasting work is kept separate from order execution and position management. Strong predictive performance can be useful, but it does not by itself prove that a trading strategy is profitable.

### DN · Rust

A local-first command-line tool for inspecting repositories and producing structured code-review findings.

It is intended to support repeatable analysis for developers, maintainers, reviewers, and CI workflows.

### phca-v3

An experimental architecture for perception, prediction, memory, and decision-making under explicit limits on computation, memory, and time.

The project explores how an agent can make decisions when its resources are limited and its internal state must be managed deliberately.

## Technical Focus

- **Languages:** Python, Rust
- **Research areas:** Quantitative finance, market microstructure, resource-bounded autonomous agents
- **Engineering priorities:** Reproducibility, deterministic evaluation, clear system boundaries, fail-closed behavior, and maintainability

## Contact

[baneshi712@gmail.com](mailto:baneshi712@gmail.com)
