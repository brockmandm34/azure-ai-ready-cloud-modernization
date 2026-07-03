# CAF Secure Alignment

## Purpose

The Secure phase focuses on protecting cloud workloads, data, identity, and infrastructure.

For Contoso Operations, security is foundational because the organization wants to use AI with internal operational data and knowledge sources.

## Security Priorities

| Area | Recommendation |
|---|---|
| Identity | Use Microsoft Entra ID and conditional access policies |
| Access control | Apply RBAC and least privilege |
| Secrets | Store secrets in Azure Key Vault |
| Service authentication | Use managed identities where possible |
| Security posture | Use Microsoft Defender for Cloud |
| Data access | Limit AI access to approved, governed sources |
| Monitoring | Collect security-relevant logs and alerts |
| Review | Establish human review for flagged AI interactions |

## AI Security Considerations

AI workloads require special attention to:

- Sensitive data exposure
- Over-permissioned retrieval
- Prompt injection risk
- Inaccurate or ungrounded outputs
- Inappropriate access to documents
- Lack of audit trail
- Cost abuse or uncontrolled usage

## Recommended Security Controls

The modernization roadmap should include:

- Microsoft Entra ID integration
- RBAC and least privilege
- Key Vault for secrets
- Managed identities
- Defender for Cloud recommendations
- Azure Policy guardrails
- Logging and monitoring
- Data classification
- Access reviews
- Secure AI prompt and response evaluation

## Secure Outcome

The customer should have a secure cloud foundation that supports production AI workloads without exposing sensitive data, unmanaged secrets, or over-permissioned access paths.
