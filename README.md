# Hypocamp

Hypocamp is an open-source operational context layer for humans and AI agents.

It helps teams and individuals keep projects, goals, decisions, tasks, commitments, and agent handoffs understandable across tools and over time.

## What it provides

- A portable Markdown and Git-based structure.
- Stable identifiers for projects and other records.
- Explicit evidence, freshness, and uncertainty markers.
- A shared protocol for agents to read context, perform scoped work, and leave a verifiable handoff.
- Derived views such as dashboards, graphs, and reports.

## Privacy boundary

This repository contains only the reusable product structure, documentation, templates, and sanitized examples. A real deployment should keep personal records, private project data, credentials, local paths, and operational history outside the public repository.

## Repository structure

```text
docs/
  agent-protocol.md
  architecture.md
  workspace-structure.md
```

Hypocamp is designed to be adapted to a private workspace while keeping the public core reusable for other people and agent ecosystems.
