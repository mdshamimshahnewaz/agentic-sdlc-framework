# Business Logic Template

No domain architecture is assumed. Replace placeholders with verified project
requirements and delete sections that do not apply.

## Domain Overview

`[Define the problem domain and business outcome here]`

## Actors and Roles

| Actor or role | Responsibilities | Permissions or boundaries |
| --- | --- | --- |
| `[Actor]` | `[Responsibilities]` | `[Boundaries]` |

## Domain Concepts

| Concept | Meaning | Key relationships |
| --- | --- | --- |
| `[Concept]` | `[Definition]` | `[Relationships]` |

## Business Invariants

- `[Rule that must always remain true]`

## Core Workflows

### `[Workflow Name]`

- Trigger: `[What starts the workflow]`
- Preconditions: `[Required state]`
- Main flow: `[Ordered business steps]`
- Result: `[Expected outcome]`
- Failure or exception paths: `[Known alternatives]`

## State Transitions

| Entity or process | From | Event | To | Guard conditions |
| --- | --- | --- | --- | --- |
| `[Subject]` | `[State]` | `[Event]` | `[State]` | `[Conditions]` |

## Authorization Rules

- `[Who may perform which business action and under what conditions]`

## Calculations and Policies

- `[Formula, rounding rule, threshold, schedule, or policy]`

## Edge Cases

- `[Boundary condition and expected behavior]`

## Integrations and Events

- `[External interaction, emitted event, consumed event, or contract]`

## Glossary

| Term | Project-specific meaning |
| --- | --- |
| `[Term]` | `[Meaning]` |

## Open Questions

- `[Unresolved domain question]`
