# Workspace structure

The public core is intentionally small. A private deployment may extend it with records and adapters without changing the reusable contract.

```text
workspace/
├── README.md
├── AGENTS.md
├── docs/
│   ├── architecture.md
│   ├── agent-protocol.md
│   └── workspace-structure.md
├── projects/
├── operations/
│   ├── reports/
│   └── lessons.md
├── decisions/
└── skills/
```

Recommended private modules:

- `projects/` — project registry and project-specific context.
- `operations/` — inbox, current focus, daily agent reports, reusable lessons, reviews, and handoffs.
- `decisions/` — durable choices that affect structure or priorities.
- `skills/` — portable procedures for agents.

The public repository should contain templates or sanitized examples for these modules, never a real user's operating history.
