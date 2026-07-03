# CAF Ready Alignment

## Purpose

The Ready phase prepares the Azure environment so workloads can be deployed securely, consistently, and with appropriate governance.

For Contoso Operations, this means establishing the foundation required before modernized applications, data services, and AI workloads are deployed.

## Azure Foundation Components

| Component | Recommendation |
|---|---|
| Identity | Use Microsoft Entra ID as the identity provider |
| Access control | Apply role-based access control using least privilege |
| Secrets management | Store secrets and configuration in Azure Key Vault |
| Monitoring | Use Azure Monitor and Application Insights |
| Security posture | Use Microsoft Defender for Cloud |
| Governance | Apply Azure Policy, tagging, and resource organization standards |
| Environment separation | Use separate dev, test, and production environments |
| Cost management | Use budgets, alerts, and cost allocation tags |

## Landing Zone Considerations

The customer should define a landing zone pattern that includes:

- Subscription and resource group organization
- Naming and tagging standards
- Role assignments and access boundaries
- Network and private access requirements
- Logging and monitoring standards
- Security baseline
- Cost management controls
- Deployment and change management process

## AI-Ready Foundation Requirements

Before deploying production AI workloads, the environment should support:

- Approved data sources
- Controlled access to documents and databases
- Secure service-to-service authentication
- Monitoring of AI usage, latency, cost, and failures
- Human review workflow for flagged responses
- Governance over prompts, data access, and model usage

## Readiness Recommendation

Contoso Operations should not begin broad AI deployment until foundational Azure controls are in place. A limited pilot can begin once identity, monitoring, approved data sources, and security controls are defined.
