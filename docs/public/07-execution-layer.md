# The Execution Layer

The Epistemic Stack provides the _why_ and _what_. The Execution Layer provides the _how_. This is where projects decompose into concrete, assignable, trackable work.

## Milestones: Time-Bounded Checkpoints

A **Milestone** is a time-bounded evaluable checkpoint representing an expected condition of progress within a coordinated intervention. It answers: _"What should reality look like by this point?"_

Milestones wrap **Bodies of Work** (BOWs) with:
- Time constraints (start date, end date, hard/soft)
- Validation criteria (manual or automated checks)
- Expected conditions (a plain-language description of the checkpoint)
- Sequential dependencies (a milestone can start after another completes)

## Bodies of Work (BOW): The Organizational Container

A **Body of Work** is a titled, goal-oriented container that groups related tasks. It is the primary unit of work organization.

- BOWs have an **owner** and optional **collaborators**
- Tasks can be added individually or with their **lineage** (upstream/downstream dependencies)
- BOWs track aggregate metrics: total tasks, validated, in progress, blocked, and percent complete

## Tasks: The Executable Unit

A **Task** is the atomic unit of executable work — where commitment meets action.

### Task Identity

Every task requires:
- **Title** — What is this work?
- **Definition of Done** — The condition that must be true for completion
- **Validation Criteria** — Specific, checkable criteria that operationalize the DoD

### Task Lifecycle

```
draft → committed → in_progress → blocked → pending_validation → validated
                                                                      ↘ cancelled
```

| Status | Meaning |
|---|---|
| **Draft** | Identified but not yet committed to |
| **Committed** | Accepted and scheduled for execution |
| **In Progress** | Active execution underway |
| **Blocked** | Halted due to an external dependency |
| **Pending Validation** | Work complete; awaiting review |
| **Validated** | All criteria satisfied; work is done |
| **Cancelled** | Abandoned (with documented reason) |

### The Accountability Grid

| Role | Purpose |
|---|---|
| **Owner** (Delivery Owner) | Accountable for execution and delivery |
| **Reporter** (Stakeholder) | Surfaced the need; receives outcome |
| **Sponsor** | Underwrites cost (especially AI-delegated work) |
| **Contributors / Observers / Reviewers** | Collaborators, watchers, and approval gates |

### Dependencies

Tasks can declare:
- **Soft dependencies** (`dependsOn`) — Informational; this task should ideally wait
- **Hard dependencies** (`hardDependsOn`) — Blocking; this task _cannot_ proceed

### Evidence and Deliverables

Tasks accumulate evidence through an append-only log:
- **Evidence** — Supporting artifacts (links, files, write-ups)
- **Deliverables** — Output artifacts with versioned markdown content
- **Decisions** — Structured choices (single/multiple-choice) that capture what was chosen and why; blocking decisions must be resolved before validation
- **Session records** — Agent execution audit trails
