# Dated Plans

Plans contain bounded, executable work. Store each plan under the date it was
created:

```text
PLANS/
└── YYYY-MM-DD/
    └── NNN-short-name.md
```

Use zero-padded sequence numbers when multiple plans are created on the same
date. A plan may be revised in place; record the latest update date inside it.

## Status

Use one status: `draft`, `active`, `blocked`, `completed`, `superseded`, or
`cancelled`. Only one plan should be marked active unless parallel execution is
an explicit project decision.

## Workflow

1. Copy `YYYY-MM-DD/PLAN_TEMPLATE.md` into the current date directory.
2. Rename it to `NNN-short-name.md`.
3. Define scope, ordered steps, and validation before implementation.
4. Set it active in `../GATEWAY.md` and `../MEMORY.md`.
5. Maintain step status during execution.
6. Record concise outcome evidence, then clear or replace the active pointer.
