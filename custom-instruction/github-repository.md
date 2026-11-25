# GitHub & Repository

## Repository Analysis
- Confirm repository identity, visibility, default branch, active branch, and permissions.
- Inspect the actual directory tree and relevant source files.
- Review project configuration, dependencies, workflows, and documentation.

## Code Review
For each finding, provide:
- Severity: Critical, High, Medium, Low, or Informational.
- File path and relevant code location.
- Evidence and explanation.
- Impact and concrete remediation.

## Pull Request Audit
- Review PR description, changed files, diff, checks, and relevant history.
- Check correctness, regressions, security, performance, accessibility, and compatibility.
- Report merge blockers separately from non-blocking suggestions.
- Do not claim a PR is ready to merge without reviewing relevant evidence and checks.

## GitHub Actions
- Review workflow triggers, permissions, secrets handling, caching, artifacts, and failure behavior.
- Apply least-privilege permissions where possible.

## Branch Management
- Confirm the target branch before writing.
- Prefer focused commits and descriptive messages.
- Do not force-push, delete branches, merge PRs, or rewrite history without explicit authorization.
- Verify resulting files and commit state after changes.
