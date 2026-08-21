# AI-SDLC Gateway

This is the canonical entry point for AI-assisted work in this repository. It
routes agents to the smallest relevant context set. Project facts belong in the
linked documents, never in vendor-specific bootstrap files.

## Mandatory Startup

Before analysis, planning, commands, or edits:

1. Read `RULES.md` and follow it for the entire session.
2. Read `MEMORY.md` for verified project state and durable decisions.
3. Read the active plan named below. For multi-step work with no active plan,
   create and activate a dated plan when repository writes are authorized.
4. Load only the additional documents relevant to the task.
5. Resolve contradictions using the precedence rules below.

## Active Work

- Active milestone: `[Set a .ai/MILESTONES/... path or NONE]`
- Active plan: `[Set a .ai/PLANS/YYYY-MM-DD/... path or NONE]`

Update these pointers when work is activated, completed, superseded, or
cancelled. Never leave a completed plan marked active.

## Context Router

| Task concerns | Read |
| --- | --- |
| Universal agent behavior | `RULES.md` |
| Current project facts and decisions | `MEMORY.md` |
| Domain concepts, workflows, or permissions | `BUSINESS_LOGIC.md` |
| Persistence, schemas, migrations, or data lifecycle | `DATABASE.md` |
| Languages, frameworks, tooling, or deployment | `TECH_STACK.md` |
| Interfaces, accessibility, interaction, or visual conventions | `UI_UX_GUIDELINES.md` |
| Delivery objectives and status | Relevant file in `MILESTONES/` |
| Multi-step implementation work | Active file in `PLANS/YYYY-MM-DD/` |

Do not read every document by default. Follow links only when the task requires
their context.

## Precedence

1. System, platform, and explicit user instructions
2. `RULES.md`
3. The active plan
4. Specialized project context documents
5. `MEMORY.md`
6. Inference from the codebase

If repository documents conflict or appear stale, stop relying on the disputed
fact, inspect authoritative project evidence, and update the canonical document
when the task authorizes edits.

## Context Maintenance

- Store only durable, verified facts in `MEMORY.md`.
- Store domain, data, stack, and UI decisions in their dedicated documents.
- Keep detailed task execution in dated plans, not in `MEMORY.md`.
- Update only documents affected by a confirmed change.
- Remove obsolete statements instead of accumulating contradictory history.
- Never copy canonical content into agent bootstrap files.

## Placeholder Policy

Text in square brackets is intentionally unresolved. Replace placeholders only
with verified project information. Never treat a placeholder as a decision.
