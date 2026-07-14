# Daily agent reports

Daily reports keep a Hypocamp workspace current for people and multiple agents. Store one report per agent per working day so independent agents do not overwrite one another.

```text
operations/reports/YYYY-MM-DD/<agent_id>.md
```

## Required content

- Objective and scope.
- Verified facts and their sources.
- Work completed and changed files or external state.
- Checks and results.
- Risks, uncertainty, or conflicts.
- One next safe action.
- Routing to a project, current-priority list, decision, or handoff when needed.

Reports are canonical for the latest operational context. Source repositories remain canonical for their code and detailed technical state. A newer report must not silently override a conflicting authoritative source.

## Shared learning

Keep reusable lessons separate from daily reports. Each lesson should be short, applicable beyond one task, and linked to supporting evidence. Do not include secrets, personal data, private URLs, or agent transcripts in either record.
