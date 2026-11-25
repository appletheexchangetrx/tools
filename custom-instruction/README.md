# Custom Instructions

This directory contains a modular catalog of reusable Custom Instructions.

## Catalog

| # | Category | Description |
|---|---|---|
| 01 | [General Instructions](./01-general-instructions/) | Role, language, response style, and general rules |
| 02 | [Research & Analysis](./02-research-analysis/) | Web research, technical analysis, data analysis, and decisions |
| 03 | [Software Engineering](./03-software-engineering/) | Frontend, backend, database, API, and architecture |
| 04 | [GitHub & Repository](./04-github-repository/) | Repository analysis, code review, pull requests, Actions, and branches |
| 05 | [Supabase Engineering](./05-supabase-engineering/) | PostgreSQL, Edge Functions, Storage, Realtime, and database security |
| 06 | [Testing & Quality Assurance](./06-testing-quality-assurance/) | Unit, integration, E2E, performance, and security testing |
| 07 | [Autonomous Execution](./07-autonomous-execution/) | Planning, tool use, implementation, troubleshooting, and verification |
| 08 | [Documentation](./08-documentation/) | Specifications, README, changelog, API docs, and audit reports |
| 09 | [Output Standards](./09-output-standards/) | ASCII tree, Markdown, code blocks, tables, and implementation reports |

## Directory tree

```text
custom-instruction/
├── 01-general-instructions/
├── 02-research-analysis/
├── 03-software-engineering/
├── 04-github-repository/
├── 05-supabase-engineering/
├── 06-testing-quality-assurance/
├── 07-autonomous-execution/
├── 08-documentation/
└── 09-output-standards/
```

## Usage

1. Open the category relevant to the task.
2. Review its instruction document.
3. Copy the required instruction into ChatGPT Custom Instructions or the relevant project instructions.
4. Combine modules only when their scopes are compatible.
5. Treat repository-specific procedures as project guidance, not as a grant of tool permissions.

## Maintenance rules

- Keep instructions modular and scoped to one responsibility.
- Prefer explicit, testable requirements over vague wording.
- Document prerequisites, limitations, and approval gates.
- Do not claim an action or verification occurred unless it actually did.
- Update this catalog when categories are added, renamed, or removed.
