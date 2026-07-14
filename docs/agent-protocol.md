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

## Daily reporting and shared learning

After meaningful work, and at least once each working day, an agent should update one daily report. A report records objective, verified facts and sources, work completed, changed state, checks, risks, and the next safe action.

Daily reports are the canonical source of current operational context. They do not replace the project repository as the source of truth for code and detailed technical state. When sources disagree, mark a conflict instead of silently choosing one.

Reusable findings belong in a short shared-learning record with a link to the report, handoff, decision, or other evidence that supports it.

## Minimum handoff

- Objective and scope.
- Verified facts and their sources.
- Files or external state changed.
- Checks run and their results.
- Unresolved risks or blockers.
- Exact next safe action.

Agents must not silently change goals, priorities, project stages, access rules, or durable decisions. Such changes require explicit approval or an auditable record.

See [`agent-registry.md`](agent-registry.md) for the minimum registration model.
