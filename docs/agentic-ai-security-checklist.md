# Agentic AI security checklist

Agents combine uncertain reasoning with authority to act. Security depends less on a clever prompt than on narrow permissions, deterministic enforcement, and observable execution.

## Authority and identity

- [ ] Every action runs as a named workload or user identity.
- [ ] Tools use least privilege, short-lived credentials, and scoped environments.
- [ ] The agent cannot grant itself permissions or bypass policy through another tool.
- [ ] High-impact actions require deterministic approval outside the model.

## Inputs and context

- [ ] External text, retrieved content, files, and tool output are treated as untrusted.
- [ ] Instructions are separated from data and provenance is retained.
- [ ] Sensitive context is minimized before it reaches the model.
- [ ] Memory has retention, access, correction, and deletion controls.

## Tool execution

- [ ] Tool schemas validate type, range, destination, and resource scope.
- [ ] Side effects are previewed, bounded, idempotent where possible, and auditable.
- [ ] Network and filesystem access use explicit allowlists.
- [ ] Rate, spend, recursion, time, and resource limits fail closed.

## Abuse and failure tests

- [ ] Direct and indirect prompt injection are tested across every ingestion path.
- [ ] Cross-user leakage, confused-deputy behavior, and privilege escalation are tested.
- [ ] Destructive, financial, legal, and external communication actions have human gates.
- [ ] Loops, partial completion, tool errors, and unavailable dependencies produce safe outcomes.

## Operations

- [ ] Traces join user intent, model decisions, tool calls, approvals, and results.
- [ ] Operators can pause, revoke, contain, and replay safely.
- [ ] Alerts distinguish policy violations, anomalies, and ordinary model uncertainty.
- [ ] Incident exercises include credential exposure and unauthorized action.

