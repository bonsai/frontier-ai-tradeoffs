---
name: frontier-ai-tradeoffs
description: Apply principles of frontier AI progress learned from OpenAI engineering practice. Use when discussing or planning frontier model development, post-training, scaling, quality-speed trade-offs, capability-safety balances, Pareto frontier expansion, cost reduction, or inference optimization. Triggers include frontier AI, model scaling, trade-offs in AI, Pareto boundary, cost efficiency enabling leaps, OpenAI-style model progress.
---

# Frontier AI Tradeoffs

## Overview

Frontier AI development is not a linear process of simply making models smarter. Real progress consists of expanding the Pareto frontier by resolving or relaxing fundamental trade-offs. Mundane engineering wins on cost and speed often unlock the next capability leap.

## Core Principles

### Progress is multi-dimensional, not linear
- Do not treat capability as a single axis that only increases.
- Explicitly identify the active trade-offs in the current system (e.g., quality vs. latency, capability vs. safety/alignment, training cost vs. inference cost, scale vs. controllability).
- Frame success as expanding the set of simultaneously achievable points on the Pareto boundary rather than maximizing one metric.

### Cost and speed reductions are strategic
- Treat latency reductions, inference efficiency improvements, training cost cuts, and infrastructure optimizations as first-class research contributions.
- Recognize that seemingly incremental engineering work often removes the binding constraint that was blocking a larger capability or product leap.
- When evaluating work, ask whether it relaxes a real constraint that currently limits what the model or system can do.

### Reverse-engineer from the desired outcome
- Start from the concrete user or product constraint (latency budget, safety requirement, cost target, quality threshold).
- Work backward to choose model architecture, training recipe, post-training method, and infrastructure accordingly.
- Avoid optimizing isolated components without reference to the binding constraints of the full system.

## Decision Checklist

When proposing or evaluating a frontier AI effort:
1. Name the primary trade-off being addressed.
2. State which constraint is currently binding.
3. Describe how the proposed change expands the Pareto frontier (what becomes newly achievable).
4. Identify the cheapest or fastest experiment that would validate the expansion.
5. Note any secondary effects on other axes (safety, cost, latency, reliability).

## Anti-patterns to avoid
- Optimizing a metric in isolation while ignoring the binding system constraint.
- Assuming that "making the model smarter" is always the highest-leverage next step.
- Treating infrastructure, inference, and cost work as secondary to "research."
- Debating theoretical improvements without a concrete path to measurable Pareto expansion.

## KPI / Signs the skill is working

This skill is a perspective and attention director, not a rigid contract. Evaluate it by whether attention landed on the right constraints.

| KPI | Good sign | Bad sign |
|-----|-----------|----------|
| Constraint explicitness | The binding constraint is clearly named ("the bottleneck is X") | Stays at vague "make it smarter" |
| Pareto awareness | Multiple axes (quality×speed, capability×safety, etc.) are actively traded off | Chasing a single metric in isolation |
| Cost/speed as strategic | Efficiency and latency work are treated as first-class enablers of the next leap | Dismissed as "not research" |
| Reverse reasoning | Starts from user/product constraints and works backward | Starts from a technique and searches for a problem |

Meta signals: the discussion updates "what we should be looking at" and leads to higher-leverage next experiments rather than more debate.
