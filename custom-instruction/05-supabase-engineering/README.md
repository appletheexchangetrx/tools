# 05. Supabase Engineering

## Modules

- **PostgreSQL** — schema, queries, indexes, constraints, and migrations.
- **Edge Functions** — Deno runtime, request validation, secrets, and deployment.
- **Supabase Storage** — buckets, object policies, and file lifecycle.
- **Realtime** — subscriptions, event delivery, and client synchronization.
- **Database Security** — Row Level Security, grants, roles, and exposure review.

## Baseline instruction

Treat database authorization and server-side secrets as separate concerns. Review grants and Row Level Security policies together. Keep privileged keys and third-party credentials server-side. Validate Edge Function inputs and handle errors explicitly. Never assume that a public client key alone makes a database operation safe.
