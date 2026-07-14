# Agent registry

An agent registry is a small canonical record of agents that can work in a private Hypocamp workspace. It helps people and agents understand who can continue work and which protocol they follow. It does not grant access.

## Registration rule

Before the first write to a workspace, an agent should read the workspace instructions and add or verify one stable `agent_id` entry.

## Minimal fields

| Field | Purpose |
|---|---|
| `agent_id` | Stable, non-secret identifier. |
| `role` | Expected contribution. |
| `scope` | Projects or records the agent may work with. |
| `interface` | Agent surface or runtime. |
| `status` | `active`, `inactive`, or `retired`. |
| `last_verified` | Date the entry was last checked. |

Do not store credentials, personal contact details, private URLs, machine identifiers, or detailed run logs in the registry. Use a handoff record for the outcome of a specific agent run.
