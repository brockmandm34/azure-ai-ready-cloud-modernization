# Well-Architected Review: Security

## Purpose

This review evaluates the security considerations for Contoso Operations' Azure modernization and AI-ready cloud foundation.

Security focuses on protecting identity, data, applications, infrastructure, and AI-enabled workflows.

## Current Security Concerns

| Concern | Impact |
|---|---|
| Inconsistent access practices | Users may have more access than needed |
| Secrets may be stored in configuration files or workflows | Increased risk of credential exposure |
| Manual workflows lack consistent audit trails | Reduced visibility into sensitive approvals |
| Data sources are not clearly classified | AI workloads may access unapproved content |
| Limited centralized security monitoring | Security issues may go undetected |
| No AI-specific governance model | Increased risk of inappropriate access or output |

## Security Recommendations

| Area | Recommendation |
|---|---|
| Identity | Use Microsoft Entra ID as the centralized identity provider |
| Access control | Apply RBAC and least privilege |
| Secrets | Store secrets in Azure Key Vault |
| Service authentication | Use managed identities where possible |
| Security posture | Use Microsoft Defender for Cloud |
| Policy | Apply Azure Policy guardrails |
| Data protection | Classify data and limit AI access to approved sources |
| Monitoring | Log authentication, access, application, and AI usage events |

## AI Security Considerations

AI workloads require controls for:

- Data leakage
- Prompt injection
- Over-permissioned retrieval
- Hallucinated or ungrounded responses
- Sensitive document exposure
- Lack of audit trail
- Uncontrolled cost or abuse

## Recommended Security Controls

The architecture should include:

- Microsoft Entra ID authentication
- RBAC for users and administrators
- Managed identities for Azure services
- Azure Key Vault for secrets
- Defender for Cloud recommendations
- Azure Monitor and diagnostic logging
- Approved data source inventory
- Human review workflow for sensitive AI outputs
- AI usage and risk telemetry

## Security Design Principle

AI workloads should not receive broad access to internal data by default. Access should be limited to approved, governed, and permission-aware sources.

## Security Outcome

The target architecture should provide a secure foundation for modernized applications and AI workloads while reducing unmanaged credentials, excessive access, and unmonitored data exposure.
