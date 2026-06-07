# Processes — Operational Stewardship

**Symbol:** ⬟
**Question:** _What persistent processes sustain operational value?_
**Definition:** A Process is a persistent, task-generating workflow that manages entity state transitions through standardized operating procedures and SLA enforcement.

While Projects (◆) model bounded, strategic interventions with clear start and end dates, Processes (⬟) model the **perpetual operational work** that keeps the organization running — guest onboarding, suite maintenance, booking management, and similar BAU (Business As Usual) activities.

## The Key Insight: Unification Through Tasks

Processes do not introduce a parallel execution system. They **generate tasks** — the same tasks used by Projects and Bodies of Work. The Task remains the universal unit of work. What changes is the _source_ of task generation: rather than a human planning a project, the workflow prescribes tasks based on entity state.

## Anatomy of a Process

| Component | Purpose | Example |
|---|---|---|
| **Entity Type** (⬡) | Defines WHAT exists — schema, properties, display template | Guest Booking (guest_name, check_in_date, suite_number) |
| **Entity Instance** | An individual entity in the world | Booking #7 (María López, Jun 15, Suite 4) |
| **Workflow** | Ordered stages with initial/terminal markers | `new → confirmed → checked_in → checked_out` |
| **Transition Definitions** | Rules for moving between states — SLAs, SOPs, ownership | `new → confirmed`: SLA 24h, activities: [Send welcome email] |
| **Gatekeeper Task** (✓) | Auto-generated confirmation task that gates each transition | `✓ Confirm: Booking Confirmed — Booking #7` |
| **Enrollment** | An entity instance flowing through a process | Booking #7 enrolled in "Suite Guest Onboarding" |

## The Gatekeeper Pattern

Every state transition is gated by a special task called the **Gatekeeper**:

1. **Hard-depends** on all SOP tasks for the current state
2. When **validated**, automatically fires the state transition
3. Cancels alternative transition paths (branching workflows)
4. Generates tasks for the next state
5. On reaching a terminal state, marks the enrollment as completed

## Bodies of Work: The Origination Cohort Model

Each process's cadence (weekly/biweekly/monthly/quarterly) determines the BOW period. When an enrollment starts, it is assigned to the current period's BOW, creating natural operational cohorts for performance analysis.

## SLA Enforcement

Transitions can define SLA targets with warning thresholds. The system monitors compliance hourly and posts warning/breach alerts automatically.
