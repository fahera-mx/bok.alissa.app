# Concept Map

| Symbol | Concept | Layer | Core Question | Persistence |
|---|---|---|---|---|
| ◉ | Observable | Ground Truth | What CAN be measured? | Permanent registry |
| ⟁ | Theory of Change | Causal Reasoning | What do we BELIEVE influences what? | Reusable model |
| ◎ | Objective | Desired State | What SHOULD reality become? | Cross-project |
| ◆ | Project | Intervention | What do we COMMIT to? | Time-bounded |
| ⬟ | Process | Operational Stewardship | What PERSISTENT PROCESSES sustain value? | Perpetual |
| ⬡ | Entity Type | Business Object | What EXISTS in our domain? | Permanent registry |
| ⬥ | Milestone | Checkpoint | What should be true BY THIS POINT? | Within a project |
| ▣ | Body of Work | Organization | What tasks belong together? | Reusable container |
| ☐ | Task | Execution | What must be done? | Atomic work unit |

## The Traceability Chain

Every task in Alissa can be traced upward through the stack:

```
Task → BOW → Milestone → Project → Objective → Observable
                              ↘ Theory of Change → Observable
```

This chain answers questions that most systems cannot:

- _"Why are we doing this task?"_ → It belongs to a BOW within a milestone of a project aligned to an objective.
- _"What belief justifies this project?"_ → The linked Theory of Change.
- _"How will we know if it worked?"_ → The observable referenced by the objective.
- _"Who is accountable?"_ → The Owner/Reporter/Sponsor chain at every level.

## Request Inboxes: Structured Demand

Work enters the system through **Request Inboxes** — structured intake points where:
- Requesters submit work with structured form data
- Inboxes can auto-route to AI agents for resolution
- Credit attribution determines who pays
- Requests flow through: `pending` → `accepted` / `declined` / `negotiating` / `withdrawn` / `expired`
