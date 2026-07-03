# CAF Govern Alignment

## Purpose

The Govern phase establishes controls to manage risk, cost, security, and compliance across the cloud environment.

For Contoso Operations, governance is especially important because the organization operates in a regulated environment and wants to adopt AI workloads that may interact with sensitive operational data.

## Governance Priorities

| Priority | Recommendation |
|---|---|
| Resource organization | Define subscription, resource group, and naming standards |
| Access control | Apply RBAC and least privilege |
| Cost management | Use budgets, alerts, and cost allocation tags |
| Policy enforcement | Use Azure Policy for required controls |
| Data governance | Classify data sources and identify approved AI-accessible content |
| Logging | Define what telemetry is collected and retained |
| Compliance | Align controls to internal audit and security requirements |

## AI Governance Controls

AI workloads require additional governance controls, including:

- Approved data source inventory
- Data access review
- Logging and auditability
- Human review process for sensitive responses
- Prompt and response evaluation
- Content safety review
- Cost and usage monitoring
- Ownership model for each AI use case

## Recommended Governance Baseline

The customer should establish:

- Naming and tagging standards
- Required owner tags
- Environment tags for dev, test, and production
- Cost center tags
- RBAC role definitions
- Resource deployment approval process
- Logging and retention standards
- AI data access review process

## Governance Outcome

Governance should enable cloud and AI adoption without creating unnecessary delivery friction. The goal is to provide guardrails that allow teams to move faster while reducing security, cost, and compliance risk.
