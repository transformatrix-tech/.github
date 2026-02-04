# Contributing

Thanks for contributing! This doc explains our standard workflow.

## Branching
- Branch from `main`.
- Branch name pattern: `type/short-description` (e.g. `feature/auth-refresh`, `bug/fix-login-null`).

## Commits
- Use Conventional Commits style: `feat:`, `fix:`, `chore:`, `docs:`, `refactor:`.
- Keep messages short; add a longer body if needed.

## Pull Requests
- Open a PR to `main`.
- Fill the PR template.
- Link related issue(s) with `#<issue-number>`.
- Add the relevant reviewers (automatically requested via CODEOWNERS).

## Tests & CI
- Ensure unit tests and lint pass locally.
- Add tests for new behaviors.
- Don't merge until CI passes and required reviews are completed.

## Issue reporting
- Use the issue templates under `.github/ISSUE_TEMPLATE/`.
