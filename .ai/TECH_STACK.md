# Technical Stack Template

No language, framework, architecture, vendor, or deployment platform is assumed.
Record exact versions when they become project requirements.

## Architecture Summary

`[Define the system shape and component boundaries here]`

## Runtime and Languages

| Area | Technology | Version | Rationale |
| --- | --- | --- | --- |
| `[Area]` | `[Technology]` | `[Version]` | `[Reason]` |

## Application Components

| Component | Responsibility | Framework or platform | Location |
| --- | --- | --- | --- |
| `[Component]` | `[Responsibility]` | `[Technology]` | `[Path]` |

## Data and Messaging

- Primary datastore: `[Technology or TBD]`
- Cache: `[Technology or NONE]`
- Search: `[Technology or NONE]`
- Queue or event system: `[Technology or NONE]`

## Interfaces and Contracts

- External API style: `[REST / GraphQL / RPC / Events / None / TBD]`
- Internal communication: `[Define here]`
- Contract definitions: `[OpenAPI, schemas, types, or TBD]`

## Dependencies

- Package managers: `[Define here]`
- Dependency policy: `[Approval, pinning, update, and audit rules]`
- Prohibited or constrained dependencies: `[Define here]`

## Development Commands

| Purpose | Command |
| --- | --- |
| Install | `[Command]` |
| Develop | `[Command]` |
| Build | `[Command]` |
| Test | `[Command]` |
| Lint | `[Command]` |
| Format | `[Command]` |
| Type-check | `[Command or N/A]` |

## Testing Strategy

- Unit: `[Framework, scope, and command]`
- Integration: `[Framework, scope, and command]`
- End-to-end: `[Framework, scope, and command]`
- Other quality gates: `[Security, performance, accessibility, or TBD]`

## Environments and Delivery

| Environment | Purpose | Deployment method | Notes |
| --- | --- | --- | --- |
| `[Environment]` | `[Purpose]` | `[Method]` | `[Notes]` |

## Observability and Operations

- Logging: `[Approach]`
- Metrics: `[Approach]`
- Tracing: `[Approach or NONE]`
- Alerting: `[Approach]`

## Security Baseline

- Authentication: `[Approach or N/A]`
- Authorization: `[Approach or N/A]`
- Secret management: `[Approach]`
- Supply-chain controls: `[Approach]`

## Open Decisions

- `[Unresolved technical decision]`
