# Model evaluation plan

## 1. Decision

State the decision this evaluation supports, the alternatives, the deadline, and who owns the result. Define what would make the team stop or choose a non-AI option.

## 2. Workload

Describe users, tasks, languages, modalities, context length, data sensitivity, tools, expected volume, and latency requirements. Separate frequent cases from rare but costly failures.

## 3. Candidate controls

Record model version, provider, prompting, retrieval, tools, guardrails, decoding settings, infrastructure, and policy configuration. Pin what can be pinned.

## 4. Evaluation set

Include representative production-like cases, adversarial cases, protected or underserved groups where relevant, ambiguous inputs, abstention cases, and operational failures. Document provenance, consent, limitations, leakage risk, and refresh policy.

## 5. Measures

Use measures tied to the decision:

- task correctness and severity-weighted error
- grounding, citation, and unsupported-claim rates
- safety, security, privacy, and policy compliance
- calibration, abstention, and human-review burden
- robustness to phrasing, context, order, and tool failure
- latency percentiles, throughput, availability, and cost per successful task

## 6. Method

Predefine rubrics, sample sizes, pass conditions, judge instructions, inter-rater checks, repeated runs, and escalation for disagreements. Blind reviewers to candidate identity when feasible. Keep automated-judge results separate from human evidence.

## 7. Results and decision

Report distributions and failure examples, not only averages. List unresolved risks, compensating controls, monitoring signals, owner, expiry date, and reassessment triggers.

