# Observables — The Ground Truth

**Symbol:** ◉
**Question:** _What can be measured?_
**Definition:** A canonical evaluable property of organizational reality.

An observable is the atomic unit of Alissa's epistemology. It represents something that **exists and can be evaluated** — independent of whether anyone cares about its value, wants to change it, or is working on it. Observables are facts about the world, not aspirations.

## Anatomy of an Observable

Every observable is defined by a precise identity:

| Field | Purpose | Example |
|---|---|---|
| **slug** | Machine-readable unique identifier | `booking_revenue_amount` |
| **name** | Human display label | Booking Revenue Amount |
| **subject** | Entity, domain, or scope it applies to | Booking System |
| **observableType** | Classification of the property | `metric`, `state`, `structural`, `behavioral`, `categorical` |
| **valueType** | Data shape | `number`, `currency`, `percentage`, `duration`, `count`, `boolean`, `category`, `ratio`, `status` |
| **unit** | Measurement unit | MXN, ms, %, days |

## Types of Observables

Alissa recognizes five fundamental types of evaluable properties:

- **Metric** — Quantitative: numbers, rates, amounts, counts. _"How much?"_
- **State** — Discrete condition or phase of a system or entity. _"What mode is it in?"_
- **Structural** — Architectural or relational property. _"How is it organized?"_
- **Behavioral** — Actor or system usage pattern. _"What is being done?"_
- **Categorical** — Classification or grouping property. _"What kind is it?"_

## Primitives and Derivations

Observables exist in two modes:

1. **Primitives** (⬡) — Directly observed from a source system. They have a `source` that documents where the raw data comes from.

2. **Derived** (⬢) — Computed from other observables through formulas, aggregations, conditionals, or mappings. Derived observables explicitly declare their `dependencies`.

This creates a **Dependency DAG** (Directed Acyclic Graph) — a living map of how organizational metrics relate to each other. When you change a primitive, you can trace its impact through every derived metric that depends on it.

## Entity-Linked Observables

Observables can be linked to **Entity Types**, enabling two powerful modes:

- **Instance-level** — Track a specific metric for individual entities (e.g., revenue per booking)
- **Aggregate-level** — Compute population statistics across all instances (SUM, AVG, COUNT, MIN, MAX, MEDIAN)

## The Principle

> **Observables define WHAT can be measured. They do not prescribe what should be true — that is the job of Objectives.**
