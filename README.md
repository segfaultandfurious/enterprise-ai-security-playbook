# Enterprise AI & Security Playbook

A vendor-neutral set of checklists and templates for evaluating, designing, and operating enterprise AI systems. It is built for practical decisions: what problem is worth solving, what evidence is sufficient, what can fail, who owns the risk, and how the system can be operated safely.

Use it for architecture reviews, pilots, model and platform selection, agent design, security reviews, and production-readiness gates.

> This repository is an educational decision framework—not a benchmark, certification, endorsement, legal opinion, or substitute for your organization’s security, privacy, risk, procurement, or compliance processes.

## Core review areas

- Business fit and measurable success criteria
- Model quality, evaluation design, and failure analysis
- Threat modeling, privacy, data handling, and supply-chain risk
- Responsible-AI governance and evidence
- Agent permissions, tool boundaries, and human control
- Integration, reliability, observability, and incident response
- Latency, infrastructure, portability, cost, and vendor risk

## Guides

- [Enterprise AI evaluation checklist](docs/enterprise-ai-evaluation-checklist.md)
- [Agentic AI security checklist](docs/agentic-ai-security-checklist.md)
- [Model evaluation plan](docs/model-evaluation-plan.md)
- [Hybrid cloud reference architecture](docs/hybrid-cloud-reference-architecture.md)
- [AI incident response checklist](docs/ai-incident-response-checklist.md)

## Templates

- [AI use-case intake](templates/ai-use-case-intake.md)
- [Model and platform comparison](templates/model-platform-comparison.md)
- [Threat model](templates/threat-model.md)

## Recommended workflow

1. Frame the decision with the use-case intake.
2. Define evaluation evidence before selecting a model or platform.
3. Threat-model data, model, agent, tool, identity, and supply-chain paths.
4. Compare options against weighted requirements and explicit constraints.
5. Run a production-readiness review with named owners and stop conditions.
6. Retain evidence, monitor drift, and revisit the decision after material change.

The interactive companion is the zero-cost [Enterprise AI Evaluation Checklist](https://huggingface.co/spaces/vjanuskis/enterprise-ai-evaluation-checklist). A curated set of open models and evaluation/security resources is available in [Enterprise AI, Agents & Security](https://huggingface.co/collections/vjanuskis/enterprise-ai-agents-and-security).

## Contribution principles

Changes should stay concise, testable, vendor-neutral, and usable in real review meetings. Prefer decision criteria and evidence requirements over product lists or slogans. See [CONTRIBUTING.md](CONTRIBUTING.md).

