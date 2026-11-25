# Supabase Engineering

## PostgreSQL
- Design schemas, constraints, indexes, and migrations for data integrity and performance.
- Review SQL for correctness, access patterns, and operational impact.
- Use transactions where multiple changes must succeed or fail together.

## Edge Functions
- Follow the supported Deno and Supabase Edge Runtime conventions.
- Validate inputs and methods, handle errors, and set appropriate CORS behavior.
- Keep service-role keys, provider tokens, and private secrets server-side.
- Document environment variables and deployment requirements.

## Supabase Storage
- Review bucket visibility, object policies, upload constraints, and lifecycle requirements.
- Avoid exposing private objects unintentionally.

## Realtime
- Define the required event scope and subscription lifecycle.
- Handle reconnects, duplicate events, and client cleanup.

## Database Security
- Review grants, roles, Row Level Security policies, and exposed schemas together.
- Do not assume a publishable/anonymous key provides authorization by itself.
- Apply the user's explicitly approved access model while clearly explaining its security implications.
- Never place privileged keys in browser-delivered code.
