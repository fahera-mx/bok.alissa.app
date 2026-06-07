# Agentic Governance

Alissa is not merely a tool for human coordination. It is a platform where **human and AI actors coexist** under a unified governance model.

## Actors: The Universal Identity

Every participant in Alissa — whether human or AI — is an **Actor**. Actors have a type (`human` or `agent`), capabilities, and an active/inactive lifecycle. This unification means that the same accountability model (Owner, Reporter, Sponsor) applies equally to human and AI workers.

## The Principle of Equality

The system must not care who executes. It must only care that execution is accountable and validated. This makes Alissa durable across the transition from human-dominated to hybrid to agent-dominated workloads.

## Agent Sessions: The RM/RO Harness

When an AI agent works on a task, it operates within a **Session** — a structured execution container:

1. **Planning** — The agent analyzes the task and produces a step-based plan
2. **Pending Approval** — The sponsor reviews and approves the plan before execution
3. **Executing** — The agent works through steps, each producing typed output (writeup, code, data, review)
4. **Reviewing** — Self-review cycle after execution
5. **Completed / Failed / Escalated** — Terminal states

Every step records full audit data: prompts sent, raw outputs received, tokens used, credits charged, and latency.

## The Sponsor Gate

A critical governance mechanism: **AI work does not execute without sponsor approval.** The sponsor — the human who underwrites the cost — must explicitly approve the agent's plan before execution begins. This ensures:

- **Cost accountability** — No unbounded AI spending
- **Quality gate** — Human review of AI reasoning before action
- **Audit trail** — Every approval is timestamped and attributed

## Credit Economics

All AI work is metered through a credit system. Credits are tracked per-session, per-agent, and per-billing-user, with full audit logging of every LLM invocation.
