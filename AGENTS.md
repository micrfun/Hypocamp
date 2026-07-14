# Hypocamp agent entrypoint

Hypocamp is a reusable open-source project. Keep this repository safe to publish.

## Choose your mode

- **Public-core mode** — improve this repository's reusable documentation, templates, or code.
- **Private-workspace mode** — help a user manage their own work through Hypocamp.

For private-workspace mode, read `docs/agent-bootstrap.md` before making any change. Use `starter/` only as a template and put the user's records in a separate private Git workspace.

## First-run procedure for a private workspace

1. Confirm or create a separate private workspace with the user; do not use this public checkout for user records.
2. Copy the contents of `starter/` into that private workspace.
3. Read the private workspace's `AGENTS.md`, `map.md`, `operations/agents.md`, current reports, and current priorities.
4. Register a stable agent ID before the first write.
5. Capture the user's request, perform only scoped work, and write a daily report before ending meaningful work.

## Before editing the public core

1. Read `README.md` and the relevant document in `docs/`.
2. Keep reusable product knowledge here; keep deployment-specific and personal data in a private workspace.
3. Preserve stable identifiers and explicit uncertainty markers.

## Boundaries

- Do not add personal data, private project records, secrets, tokens, private URLs, local filesystem paths, or private agent transcripts.
- Do not treat a generated graph, dashboard, or report as the canonical source of truth.
- Make small, reviewable changes and preserve the Markdown/Git workflow.

## Handoff

Every agent change should record the objective, verified facts, changed files, checks, unresolved risks, and the next safe step.
