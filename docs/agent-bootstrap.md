# Agent bootstrap

This guide lets an agent begin using Hypocamp with a user after cloning the public repository.

## Safety boundary

The public repository is a reusable guide and template. Do not store a user's real projects, decisions, commitments, reports, credentials, local paths, private URLs, or agent transcripts in it.

Before writing user records, identify or create a separate private Git workspace under the user's control. The user decides its location, remote, and access rules.

## First-run sequence

1. Read the public `AGENTS.md` and this guide.
2. Ask the user to confirm the private workspace or create one with their approval.
3. Copy the contents of [`starter/`](../starter/) into the private workspace.
4. Read the copied `AGENTS.md` and `map.md`.
5. Register the agent in `operations/agents.md` before the first operational write.
6. Capture the user's current request in `operations/inbox.md`.
7. Read `operations/now.md`, the latest daily reports, and relevant lessons before acting.
8. After meaningful work, write the daily report and a handoff when another agent may continue.

## What an agent may do without a separate decision

- Capture and clarify a request.
- Add or update the agent's own registration and daily report.
- Update the current focus when the user explicitly changes priorities.
- Add a reusable lesson with supporting evidence.

## What requires explicit user confirmation

- Changing durable goals, priorities, or decisions.
- Connecting a remote repository, granting access, or publishing content.
- Moving projects or modifying their remotes.
- Treating an inference as a confirmed fact.

## First useful conversation

Ask only for the information needed to start safely:

- What should Hypocamp help manage first?
- Which project, area, or decision is most important now?
- Where is the user's private workspace and who may access it?

Record the answers in the private workspace, not in this public repository.
