# Hypocamp

Hypocamp is an open-source operational context layer for humans and AI agents.

> Public design preview. The project license is not selected yet, so do not assume that the repository is currently licensed for reuse.

It helps teams and individuals keep projects, goals, decisions, tasks, commitments, and agent handoffs understandable across tools and over time. Its guiding metaphor is an external context memory: consolidate fragments of work, map their relationships, and preserve the circumstances that make a fact meaningful.

## What it provides

- A portable Markdown and Git-based structure.
- Stable identifiers for projects and other records.
- Explicit evidence, freshness, and uncertainty markers.
- A shared protocol for agents to read context, perform scoped work, and leave a verifiable handoff.
- Derived views such as dashboards, graphs, and reports.

## Project status

Hypocamp is in an early design and documentation phase. The public repository defines the reusable model and agent methodology; a production application, stable schemas, and adapters are still being developed.

## Getting started

### Start with an agent

An agent can start from this repository without knowing a user's personal setup:

1. Clone this repository and read [`AGENTS.md`](AGENTS.md).
2. Follow [`docs/agent-bootstrap.md`](docs/agent-bootstrap.md) to create or identify a separate private workspace.
3. Copy [`starter/`](starter/) into that private workspace.
4. Let the agent register itself, capture the user's first request, and maintain daily reports there.

The public clone is a guide and template. Do not use it to store a user's actual projects, decisions, commitments, or reports.

Read these documents in order:

1. [`docs/architecture.md`](docs/architecture.md) — the model and its boundaries.
2. [`docs/agent-bootstrap.md`](docs/agent-bootstrap.md) — the first-run procedure for an agent.
3. [`docs/workspace-structure.md`](docs/workspace-structure.md) — the recommended workspace layout.
4. [`docs/agent-protocol.md`](docs/agent-protocol.md) — how agents should operate and hand off work.
5. [`docs/agent-registry.md`](docs/agent-registry.md) — a minimal registration model for agents that share a workspace.
6. [`docs/daily-reports.md`](docs/daily-reports.md) — how agents keep operational context current.

To adopt Hypocamp, copy the structure into a private workspace and replace the examples with your own records. Keep personal and operational data out of this public repository.

## Privacy boundary

This repository contains only the reusable product structure, documentation, templates, and sanitized examples. A real deployment should keep personal records, private project data, credentials, local paths, and operational history outside the public repository.

## Repository structure

```text
docs/
  agent-bootstrap.md
  agent-registry.md
  agent-protocol.md
  daily-reports.md
  architecture.md
  workspace-structure.md
starter/
  AGENTS.md
  map.md
  projects/
  operations/
  decisions/
```

Hypocamp is designed to be adapted to a private workspace while keeping the public core reusable for other people and agent ecosystems.

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for the contribution workflow. Proposals that change the data model or agent protocol should include a short decision record and explain compatibility impact.

## Security

See [`SECURITY.md`](SECURITY.md) for reporting security and privacy issues.
