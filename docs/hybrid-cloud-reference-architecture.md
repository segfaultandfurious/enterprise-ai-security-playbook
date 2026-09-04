# Hybrid-cloud reference architecture

## Design intent

Place data and computation according to sensitivity, latency, resilience, sovereignty, and economics. Keep control boundaries explicit and make provider substitution possible where it matters.

## Logical flow

```text
Users / applications
        |
Identity, policy, consent, rate limits
        |
AI gateway and request classification
   |          |             |
Private      Cloud         Human review
models       models        / approval
   |          |
Retrieval, tools, and governed data services
        |
Telemetry, evaluation, audit, and incident response
```

## Control points

- **Identity:** workload identity, user delegation, least privilege, tenant separation.
- **Routing:** policy-based placement by data class, workload, jurisdiction, and availability.
- **Data:** approved sources, encryption, minimization, retention, lineage, deletion, and egress controls.
- **Models:** version registry, provenance, signatures, evaluation evidence, and rollback.
- **Tools:** allowlisted capabilities, typed inputs, scoped credentials, transaction boundaries, and approval gates.
- **Operations:** correlated logs and traces, quality and drift signals, cost allocation, SLOs, and kill switches.

## Resilience and exit

Define degraded modes for provider, network, identity, retrieval, and model failures. Test portability at the interface, data, evaluation, and operational layers; a second model alone is not an exit plan.

