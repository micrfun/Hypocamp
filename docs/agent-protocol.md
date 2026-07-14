# Agent protocol

Every agent follows this loop:

```text
read current state
→ register or verify registration
→ identify sources and uncertainty
→ perform only scoped work
→ record evidence and changes
→ run relevant checks
→ create a handoff
```

## Minimum handoff

- Objective and scope.
- Verified facts and their sources.
- Files or external state changed.
- Checks run and their results.
- Unresolved risks or blockers.
- Exact next safe action.

Agents must not silently change goals, priorities, project stages, access rules, or durable decisions. Such changes require explicit approval or an auditable record.

See [`agent-registry.md`](agent-registry.md) for the minimum registration model.
