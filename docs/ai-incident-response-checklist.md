# AI incident response checklist

## Prepare

- [ ] Name incident, security, privacy, model-risk, legal, communications, and service owners.
- [ ] Preserve model, prompt, retrieval, policy, tool, dependency, and deployment versions.
- [ ] Ensure logs connect user intent, identities, data access, model output, tool calls, approvals, and effects.
- [ ] Predefine kill switches, provider escalation, credential revocation, rollback, and user-notification paths.

## Detect and triage

- [ ] Classify impact: harmful output, data exposure, unauthorized action, integrity loss, abuse, outage, cost anomaly, or compliance concern.
- [ ] Identify affected users, tenants, models, data, tools, regions, and time window.
- [ ] Separate suspected model behavior from application, retrieval, policy, identity, or supply-chain failure.
- [ ] Protect evidence and avoid copying sensitive prompts or outputs into unapproved systems.

## Contain and recover

- [ ] Pause affected capabilities or route to a safe degraded mode.
- [ ] Revoke exposed credentials and narrow permissions.
- [ ] Remove compromised context, retrieval sources, artifacts, or dependencies.
- [ ] Validate fixes against the incident case and a broader regression set.
- [ ] Restore gradually with enhanced monitoring and accountable approval.

## Learn

- [ ] Document timeline, contributing conditions, control gaps, decisions, and residual risk.
- [ ] Update evaluations, threat models, runbooks, training, and vendor requirements.
- [ ] Track corrective actions to owners and dates.
- [ ] Define the signal or change that triggers another review.

