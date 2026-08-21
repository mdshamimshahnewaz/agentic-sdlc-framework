# Database and Data Architecture Template

No database engine, topology, tenancy model, or persistence pattern is assumed.
Document only confirmed decisions.

## Data Architecture

- Persistence approach: `[Relational / Document / Graph / Files / Mixed / None]`
- Primary datastore: `[Technology and version or TBD]`
- Supporting datastores: `[Cache, search, analytics, queue, or NONE]`
- Ownership model: `[How data ownership and boundaries are defined]`

## Isolation and Tenancy

- Tenancy model: `[Single-tenant / Shared schema / Schema per tenant / Database per tenant / Not applicable]`
- Isolation key or boundary: `[Field, schema, database, account, or N/A]`
- Enforcement layers: `[Application / Database / Infrastructure / N/A]`
- Privileged access policy: `[Cross-boundary access rules or N/A]`

## Entity and Storage Map

| Entity or dataset | Storage location | Ownership | Retention |
| --- | --- | --- | --- |
| `[Entity]` | `[Table, collection, bucket, or service]` | `[Owner or boundary]` | `[Policy]` |

## Schema Conventions

- Identifiers: `[Type and generation strategy]`
- Timestamps: `[Fields, timezone, and precision]`
- Naming: `[Confirmed naming convention]`
- Nullability: `[Policy]`
- Soft deletion: `[Policy or N/A]`

## Integrity Rules

- `[Primary, foreign, unique, validation, or consistency constraint]`

## Indexing and Query Patterns

- Critical queries: `[List or link]`
- Index strategy: `[Confirmed approach]`
- Pagination: `[Cursor / Offset / Other / TBD]`
- Performance targets: `[Latency, volume, or throughput]`

## Transactions and Concurrency

- Transaction boundaries: `[Rules]`
- Concurrency strategy: `[Locking, versioning, idempotency, or TBD]`
- Consistency model: `[Strong / Eventual / Mixed / TBD]`

## Migrations and Seed Data

- Migration tool and workflow: `[Define here]`
- Rollback policy: `[Define here]`
- Seed and fixture policy: `[Define here]`

## Security and Privacy

- Sensitive data classes: `[Define here]`
- Encryption requirements: `[At rest, in transit, field-level, or TBD]`
- Audit requirements: `[Define here]`
- Deletion and retention requirements: `[Define here]`

## Backup and Recovery

- Backup strategy: `[Define here]`
- Recovery objectives: `[RPO and RTO or TBD]`
- Restore verification: `[Define here]`

## Open Decisions

- `[Unresolved data architecture decision]`
