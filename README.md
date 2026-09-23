# Enterprise AI Enablement Playbook

A public-safe collection of practical patterns for moving enterprise AI from experimentation into governed, useful adoption.

The playbook is designed for business and technology teams that need to identify worthwhile use cases, prepare trusted knowledge, introduce human review, support users, and measure whether an AI-assisted workflow is ready to scale.

## Enterprise AI Enablement Pattern

```mermaid
flowchart LR
    A["Business priorities<br/>and use cases"] --> B["Trusted knowledge<br/>and data"]
    B --> C["Secure enterprise<br/>environment"]
    C --> D["AI-assisted workflows<br/>and internal tools"]
    D --> E["Human review<br/>and operational integration"]
    E --> F["Adoption, measurement<br/>and continuous improvement"]
    G["Governance | Access | Risk review | Evaluation | Cost awareness | Monitoring"]
    G -.-> A
    G -.-> B
    G -.-> C
    G -.-> D
    G -.-> E
    G -.-> F
```

The sequence is deliberate. Technology selection follows the business problem, information quality, risk boundary, and operating model rather than leading them.

## Public Portfolio Artefacts

- [AI Use Case Intake and Prioritisation](docs/AI_USE_CASE_INTAKE_AND_PRIORITISATION.md) - a reusable intake and decision template.
- [Enterprise AI Enablement Pattern](docs/ENTERPRISE_AI_ENABLEMENT_PATTERN.md) - a business-language architecture and operating model.
- [Pilot to Adoption Playbook](docs/PILOT_TO_ADOPTION_PLAYBOOK.md) - a controlled path from discovery to scale-up.
- [Fictional Service Operations Case](docs/FICTIONAL_SERVICE_OPERATIONS_CASE.md) - a worked example for an internal knowledge assistant.
- [Public Scope](PUBLIC_SCOPE.md) - the safety and evidence boundary for this repository.

## Real internal case studies

Dated, sanitised accounts from my independent business project, separate from the generic templates and fictional service-operations example:

- [Verification handoff](case-studies/verification-handoff.md) — completed supervised delivery, 23 September 2026.
- [Context recovery](case-studies/context-recovery.md) — accepted bounded proof, 23 September 2026.

Each case distinguishes my direction from agent implementation, and technical results from business outcomes. Read the [case-study evidence boundary](case-studies/README.md).

## How To Use This Repository

1. Start with the intake template and define a real business problem.
2. Assess knowledge readiness, access, risk, and ownership.
3. Design the smallest useful pilot with explicit human review.
4. Agree success measures before implementation.
5. Review evidence, user feedback, operational fit, and cost before scaling.

## Public-Scope Statement

The templates and fictional scenarios illustrate methods; they do not document actual delivery. The separately labelled real internal case studies describe dated, sanitised events in the author's independent business project. They identify human and agent contributions, observed results and limitations. They do not represent employer systems, commercial client engagements or enterprise-scale production deployments. Confidential information, private source code, logs, credentials, internal prompts and proprietary architecture are excluded.



