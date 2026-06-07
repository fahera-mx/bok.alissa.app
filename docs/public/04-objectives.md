# Objectives — The Desired State

**Symbol:** ◎
**Question:** _What should reality become?_
**Definition:** An evaluable desired condition over observed reality.

An objective is a statement of intent grounded in measurement. It takes an observable property — something that _can_ be measured — and declares what value, trend, or state that property _should_ achieve. Objectives bridge understanding reality and deciding to change it.

## The Evaluation Spec

Every objective is defined by a structured evaluation formula:

```
subject · observable  condition  target
```

For example:
```
Guest Onboarding · conversion rate  >=  85%
```

| Component | Role | Examples |
|---|---|---|
| **Subject** | Entity, domain, or scope | Guest Onboarding, Sales Team |
| **Observable** | The measurable property (FK to ◉ registry) | conversion rate, monthly revenue |
| **Condition** | How the observable is evaluated | `>=`, `increasing`, `achieved` |
| **Target** | The threshold or state that satisfies the objective | 85%, $50,000, complete |

## Condition Categories

Alissa supports three families of evaluation conditions:

- **Comparison** — Threshold-based: `>`, `>=`, `<`, `<=`, `==`, `!=`
- **Trend** — Direction-based: `increasing`, `decreasing`, `stable`
- **State** — Achievement-based: `achieved`, `maintained`, `eliminated`

## Objective Kinds

Objectives come in two kinds:

- **Strategic objectives** — Linked to Projects, measuring the impact of bounded interventions
- **Operational objectives** — Linked to Processes, measuring SLA compliance, throughput, and cycle time

## The Separation of State and Intervention

This is perhaps Alissa's most important philosophical commitment:

> **An objective defines WHAT reality should become. A project defines WHAT interventions you commit to in order to make that happen.**

The same objective can be served by many projects. A project can serve many objectives. But the objective itself is _never_ an action item — it is a compass heading. This separation prevents the common failure mode where teams confuse activity with progress.
