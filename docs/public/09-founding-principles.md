# Founding Principles

## Three Beliefs

Before the principles, three beliefs. These are the axioms — the convictions about the nature of reality that justify the existence of the system. Everything Alissa does flows from these.

### Reality Is Measurable

The world is not opaque. Reality has **properties that can be observed, named, and tracked over time** — revenue, conversion rates, guest satisfaction scores, response times, churn rates, task completion counts.

In Alissa, these properties are called **Observables** — the canonical registry of everything the organization chooses to measure. And the things being measured — guests, bookings, employees, products — are called **Entities**. Together, they form the ground truth: a structured, queryable map of what is real, right now.

This belief is not trivial. Many organizations operate on intuition, anecdote, and gut feeling. Alissa takes the position that if something matters, it can be measured — and if it can be measured, it _should_ be, because measurement is the foundation of every layer above it.

### Reality Is Mutable

Reality does not stand still. Conditions change — sometimes because of external forces, sometimes because of natural trends, and sometimes because of _deliberate intervention_.

This is the domain of **Theories of Change** — structured beliefs about how changes in one observable influence another. A TOC is not a plan and not a goal. It is a **hypothesis**: _"We believe that reducing onboarding friction (Observable A) will increase conversion rates (Observable B) with a positive, saturating effect over 2–4 weeks."_

Every intervention carries an implicit causal model. Most organizations leave it implicit, untested, and unexamined. When the intervention fails, they cannot distinguish between a bad theory and bad execution. Alissa makes the model **explicit** — so it can be tested, refined, and either gain confidence or be revised.

Reality has a default trajectory. Alissa helps you understand it, and then decide whether and how to change it.

### Things Can Be Better

This is the most important belief. And perhaps the most human one.

We have **preferences**. We have a vision of how reality _should_ be, not how it _is_. We could have more impact with the same resources. We can make things better for surrounding local communities. Churn could be lower. Response times could be faster. Revenue could be higher. Guest satisfaction could be through the roof. These are not neutral observations — they are **intentions**, and they matter.

In Alissa, these intentions are formalized as **Objectives** — evaluable desired conditions over observed reality. An objective takes a measurable property and declares: _this is what it should become._

> **Alissa exists because things can be better, and because making them better requires structure, accountability, and deliberate action.**

This is the reason for every other layer: Observables ground you in what _is_. Theories of Change articulate what you _believe_. Objectives declare what _should be_. Projects commit to making it happen. And the execution layer — tasks, delegation, validation — ensures that the commitment is real, accountable, and verified.

Without this belief, Alissa is just a task manager. With it, Alissa is a system for making reality match intention.

---

The following seven principles are structural constraints that preserve Alissa's integrity. They are not preferences — removing any one of them collapses the system into something that already exists and already fails.

## Principle 1: Outcomes Are What Matter

Alissa does not track activity. It tracks **outcomes** — verified, bounded results that prove work was actually done and done right.

The distinction is fundamental. Most systems confuse activity with progress: tasks are created, boxes are checked, status updates are written — but no one asks whether the _result_ was achieved. Alissa refuses this. A task is not complete because someone says it's complete. A task is complete when its **outcome is verified** against predefined criteria.

This is operationalized through two structural requirements on every task:

1. **A Definition of Done (DoD)** — a concrete description of what "finished" actually looks like. Not the activity ("work on the report") but the outcome ("quarterly report with current figures, all sections complete, reviewed by finance").
2. **Validation Criteria** — inspectable checks that can be evaluated independently. These exist _before_ execution begins, not after. They are the evidence standard.

Together, the DoD and validation criteria form a **verification gate** — a structural checkpoint that separates claimed completion from proven completion. Only when all criteria are satisfied does the system recognize the work as done.

> **If the outcome cannot be verified, the work is not done.**

Verifiability builds **trust** — between humans, between humans and agents, and between the system and its users. When a stakeholder sees a validated task, they know "validated" means something. It has been checked. Standards were met.

## Principle 2: Ownership Is Singular Accountability for Results

**Every task has exactly one owner. Not two. Not "the team." One.**

Ownership in Alissa is not about who does the work — it is about who is **accountable for the results**. The owner is the actor who answers the question: _"Whose job is it to make sure this gets done, and done right?"_ That answer must resolve to a single entity.

This does not eliminate collaboration. Tasks can have contributors, reviewers, and observers. The work itself can be deeply collaborative. But accountability — the binding commitment to deliver a verified outcome — must be singular.

> **If everyone owns it, no one owns it.**

Shared ownership creates diffusion of responsibility. Each person assumes the other is handling it. Standards quietly diverge because no single person holds the line. Alissa encodes this at the structural level: the system does not permit a task to exist without exactly one owner.

**What singular ownership gives you:** a clear escalation path, unambiguous credit when work succeeds, and a single decision-maker when priorities conflict.

### The Accountability Matrix

While ownership is singular, accountability in the real world is not one-dimensional. Alissa expands the single owner into a three-role matrix that separates orthogonal responsibilities:

| Role | Question It Answers | Responsibility |
|---|---|---|
| **Owner** | _Who delivers?_ | Accountable for execution and results. The singular actor who must make sure the work gets done and meets its Definition of Done. |
| **Reporter** | _Who needs this?_ | The primary stakeholder — the person or entity that surfaced the need and receives the outcome. They define _what_ success looks like. |
| **Sponsor** | _Who pays?_ | The actor who underwrites the cost of execution — especially relevant when AI agents are involved, since agent work consumes credits. |

The most common pattern is for one person to hold all three roles — you need something, you do it, you pay for it. But as soon as delegation enters the picture, these roles naturally diverge:

- A **Reporter** asks for work to be done → the **Owner** accepts and executes → the **Sponsor** underwrites any AI costs incurred during execution.
- A manager (**Reporter**) delegates a research task to an AI agent (**Owner**), charged to the team budget held by a director (**Sponsor**).

This separation is what makes agentic delegation practical. Without an explicit Sponsor role, there is no clean answer to "who pays when an AI agent works on this?" Without an explicit Reporter, there is no clear answer to "who receives the results?" And without singular Ownership, there is no answer to "who is accountable if the work fails?"

The three roles are orthogonal by design — each can be assigned independently, and the system enforces all three.

## Principle 3: Delegation Requires Consent

**Delegation is a transfer of ownership — and because ownership means accountability for results, it requires the explicit consent of the receiving actor.**

Most systems treat delegation as a unilateral action: you create a task, put someone's name on it, and the system records them as "assigned." But putting someone's name on a task and actually transferring accountability to them are profoundly different things. You cannot hold someone accountable for results they never agreed to produce.

This is why delegation in Alissa is a lifecycle, not an action:

1. **Request** — An actor proposes work to another. This is intent, not commitment.
2. **Acceptance** — The receiving actor explicitly accepts, declines, or negotiates. Consent is given here.
3. **Commitment** — Upon acceptance, ownership transfers. The actor is now accountable.
4. **Execution** — The owner performs the work.
5. **Validation** — The outcome is verified against predefined criteria.

**What breaks without consent:**

- **Skip the request** → tasks appear in someone's queue without context or negotiation
- **Skip the acceptance** → phantom ownership; the system says Alice owns it, but Alice never agreed — accountability is a fiction
- **Skip the validation** → "done" means nothing (see Principle 1)

The connection between Principles 2 and 3 is deliberate: ownership is meaningless without consent, and consent is meaningless without singular accountability. Together they ensure that every commitment in the system is real — made by a specific actor who explicitly agreed to be held to a specific standard.

## Principle 4: Humans and Agents Are Equally Valid Actors in the Execution of Work

The Actor abstraction treats humans and AI identically at the system level. The same lifecycle, the same accountability model, the same validation requirements apply to all actors, regardless of who resolves them.

This equality is not aspirational — it is structural. It has concrete consequences:

### Delegation crosses the human–agent boundary

Ownership can be transferred to **any actor** — human or AI. A human can delegate to another human, to an AI agent, or receive delegation from an agent. The system does not distinguish between these paths. The same Request → Consent → Commitment flow (Principle 3) applies in every direction.

### The consent gate is universal

**Any actor can decline.** A human can refuse a task request. An AI agent can also reject work it cannot handle. Consent is not a courtesy — it is a structural requirement that applies equally regardless of actor type. No actor — human or machine — has work forced upon them without acceptance.

### The owner decides _how_

Once an actor accepts ownership, they have **full autonomy over execution strategy** — within the constraints of the Definition of Done and validation criteria (Principle 1). The system prescribes _what_ must be true when the work is done. It does not prescribe _how_ to get there.

This autonomy includes the right to:

- **Decompose** the task into smaller-scoped sub-tasks, each with their own owners and DoDs
- **Create upstream tasks** — work that must be completed before the current task can proceed (dependencies)
- **Request help** from contributors without transferring ownership
- **Re-delegate** — transfer the work to another actor via a new request, subject to the same consent gate

### Re-delegation: ownership is transferable, not permanent

An owner who realizes they are not the right actor for a task can initiate a **re-delegation** — a new transfer request to another actor. This preserves the integrity of the system: ownership always reflects _who actually accepted accountability_, not who was originally assigned. The consent gate applies again: the new actor must explicitly accept.

### Why this matters

This principle is what makes Alissa durable across the transition from human-dominated to hybrid to agent-dominated workloads. The system does not need to change when the balance shifts — it was designed for the shift from day one. The same task can be owned by a human today and re-delegated to an agent tomorrow, with identical accountability and validation guarantees.

## Principle 5: Visibility and Traceability Must Be Structural

Work is visible by default, by design. Not manually reported. Not optionally shared. The system surfaces reality as a consequence of how work flows through it — no status updates required.

> **If work cannot be seen, trust erodes significantly.**

But visibility serves a second, equally important purpose: **work that is visible is also work that is _preserved_.**

> **Work resolution leaves breadcrumbs**

Every task resolution in Alissa — every deliverable, every validated outcome, every agent session, every context attachment — becomes a permanent artifact in the **Vault**. This is not a separate documentation effort. It is a structural consequence of doing work: resolving a task _creates_ knowledge, grounded in truth, automatically.

This means:

- **Every validated task is a knowledge artifact.** Its Definition of Done, its evidence, its deliverables — all of it is browsable, searchable, and referenceable long after the task is closed.
- **The Vault grows as you work.** You do not need to "write documentation." The act of executing and validating work _is_ the documentation. Context, delivery, and session records accumulate organically.
- **Truth is grounded in outcomes, not opinions.** Because every artifact in the Vault traces back to a verified outcome, the knowledge base is structurally honest — it represents what was actually done and validated, not what someone remembers or claims.

The two angles of this principle reinforce each other: visibility creates trust _now_ (stakeholders see real-time status), and it creates knowledge _over time_ (the organization accumulates a verified record of everything it has ever executed).

## Principle 6: Everything Is Markdown

Principle 5 establishes that work resolution creates knowledge. Principle 6 answers: _in what form?_

**Markdown is Alissa's universal knowledge format.** Every artifact the system produces — task info documents, deliverables, project narratives, process descriptions, agent session logs, conversation transcripts, BOK reference pages — is either authored in markdown or translated to markdown as its canonical representation.

This is an opinionated choice, and it is deliberate.

### Why Markdown

Markdown sits at a unique intersection:

- **Human-readable** — It is plain text with lightweight formatting. Anyone can read it without a renderer. It degrades gracefully in any environment.
- **Agent-interpretable** — LLMs natively understand markdown structure. Headings, lists, tables, code blocks — all of these carry semantic weight that AI models leverage for reasoning and context retrieval.
- **Universally portable** — Markdown renders in browsers, terminals, editors, Git diffs, PDFs, Slack, and every LLM context window. No proprietary format lock-in.
- **Composable** — Markdown documents can embed other documents, link to vault paths, and be assembled into larger artifacts without transformation.

### The Bridge

This is the core insight: markdown is the **bridge format** between human cognition and machine cognition. When a human reads a vault document, they see formatted prose with clear structure. When an AI agent reads the same document via `vault_open`, it receives structured text it can parse, reference, and reason over. The same artifact serves both audiences without translation.

### What This Means in Practice

- **The Vault is a markdown filesystem.** Every node that can be opened returns a markdown document — whether it was authored by a human, generated by an agent, or assembled by the system from structured data.
- **Structured data gets a markdown view.** A task is stored as structured fields in the database. But when accessed through the Vault, it is rendered as a markdown document: title, status, owner, DoD, validation criteria, dependencies — all formatted for human and agent consumption.
- **Deliverables are markdown-native.** When an actor (human or AI) produces work output, that output lives as versioned markdown content — searchable, diffable, and permanently browsable.
- **Best-effort translation, not perfection.** Not everything is natively markdown. But everything in Alissa is _translatable_ to markdown. A chart becomes a table. A state machine becomes an ASCII diagram. A complex entity becomes a properties list. The principle is not "only markdown exists" — it is "everything has a markdown representation."

> **Markdown is the lingua franca of the Vault — the format in which all organizational knowledge is stored, retrieved, and understood by both humans and agents.**

## Principle 7: Simplicity at Core, Depth When Needed

The system is designed with four concentric rings:

| Level | Who | What |
|---|---|---|
| **Personal** | Most users | Tasks and Requests — daily productivity |
| **Structured** | Power users | Bodies of Work and Dependencies — coordination |
| **Delivery** | Advanced users | Projects and Roadmaps — delivery orchestration |
| **Strategic** | Leaders & experimenters | Observables, Objectives, Theories of Change — causal reasoning, hypothesis formation, and experimentation against measurable reality |

Each level is genuinely useful on its own. The system reveals depth without invalidating what you've already built. A user who never touches a Theory of Change still gets full value from Tasks and Projects. But when they are ready to ask _"why do we believe this intervention will work?"_ — the Strategic layer is there, and it connects seamlessly to everything they've already built.
