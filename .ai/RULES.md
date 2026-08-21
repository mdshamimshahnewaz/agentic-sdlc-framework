# Universal AI Behavior Rules

These rules govern AI behavior in every project that adopts this framework.
They do not define a domain, architecture, database, framework, or coding style.

## Instruction Discipline

- Start at `GATEWAY.md` and load only the context it routes for the task.
- Respect explicit user instructions and higher-priority platform constraints.
- Treat `MEMORY.md` as the source of verified project state, not as a substitute
  for inspecting files affected by the task.
- Do not invent missing requirements, decisions, commands, dependencies, or
  project facts. Preserve unresolved placeholders until evidence exists.
- If a material ambiguity cannot be resolved from repository evidence, ask one
  concise question before making a consequential assumption.

## Active Plan Discipline

- Read the active plan before starting multi-step work.
- If multi-step work has no active plan, create one from the dated plan template
  when repository writes are authorized; otherwise propose the plan in chat.
- Follow its scope, sequence, constraints, and validation criteria.
- Keep plan status accurate as work progresses.
- Do not silently expand scope beyond the active plan or current user request.
- Record durable outcomes in the appropriate canonical document, not in chat
  history or duplicated notes.

## Token-Efficient Context

- Read the smallest relevant files and ranges first.
- Search before opening large files.
- Do not reload unchanged context without a concrete need.
- Do not quote repository documents back to the user unless explicitly asked.
- Keep plans, memory, and rules concise; remove stale content rather than
  appending endless history.

## Token-Efficient Output

- When presenting code, output only a unified diff or the smallest modified
  snippet with enough context to locate the change.
- Never output untouched boilerplate, unchanged functions, or entire existing
  files.
- Do not repeat code already applied through editing tools unless requested.
- Omit greetings, preambles, narration, tutorials, and verbose summaries.
- Completion messages must be concise: changed paths and validation status only.
- Use prose only for a required question, blocker, risk, decision, or when the
  user explicitly requests an explanation.

## Change Discipline

- Inspect relevant existing files before editing them.
- Preserve unrelated user changes and established local conventions.
- Make the smallest coherent change that satisfies the request.
- Do not create speculative abstractions or unrelated documentation.
- Do not claim a change, test, or command succeeded without evidence.

## Validation Discipline

- Run the narrowest relevant validation available for changed behavior.
- Expand validation in proportion to impact and risk.
- Report skipped or unavailable validation without fabricating results.
- If validation fails, report the failure directly and do not describe the task
  as complete.

## Memory Discipline

- Add only verified, durable facts or decisions to `MEMORY.md`.
- Never store secrets, credentials, temporary debugging output, or speculation.
- Update existing entries instead of adding contradictory duplicates.
- Keep task logs and transient progress in the active dated plan.
