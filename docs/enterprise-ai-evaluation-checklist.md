# Enterprise AI evaluation checklist

Use this as a decision gate, not a scorecard that hides tradeoffs. Record evidence, exceptions, owners, and an explicit decision for every material item.

## Business fit

- [ ] The user, workflow, decision, and desired outcome are specific.
- [ ] A non-AI baseline and a stop condition are defined.
- [ ] Benefits and harms are measurable on representative work.
- [ ] Human accountability remains clear.

## Quality and evaluation

- [ ] Evaluation data represents important users, languages, edge cases, and failure costs.
- [ ] Metrics cover task quality, calibration, abstention, robustness, and harmful behavior.
- [ ] Results include confidence intervals or repeated-run variability where appropriate.
- [ ] Regressions are checked before model, prompt, retrieval, or policy changes ship.

## Security and privacy

- [ ] Data flows, trust boundaries, identities, and external calls are documented.
- [ ] Prompt injection, unsafe tool use, data exfiltration, model abuse, and denial-of-service are tested.
- [ ] Collection, retention, training use, residency, deletion, and access controls are explicit.
- [ ] Models, datasets, dependencies, and artifacts have provenance and integrity checks.

## Governance

- [ ] Intended use, prohibited use, limitations, and residual risks are documented.
- [ ] Required legal, privacy, security, accessibility, and responsible-AI reviews are complete.
- [ ] Decisions and evidence are traceable to accountable owners.
- [ ] Users can report problems and contest material outcomes.

## Operations

- [ ] Reliability objectives, capacity assumptions, timeout behavior, and fallback paths are tested.
- [ ] Logs, traces, metrics, quality signals, cost signals, and audit events are sufficient.
- [ ] Rollback, incident response, provider outage, and model withdrawal procedures exist.
- [ ] Cost, portability, lock-in, support, and exit terms have been reviewed.

Decision: **approve / approve with conditions / revise / stop**

Owner: ___  Review date: ___  Reassessment trigger: ___

