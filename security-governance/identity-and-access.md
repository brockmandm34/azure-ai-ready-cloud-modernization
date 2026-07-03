# Identity and Access

## Purpose

This document defines the identity and access recommendations for Contoso Operations as it modernizes its environment on Microsoft Azure and prepares for production AI workloads.

## Current Challenge

The current environment has inconsistent access practices across legacy systems, SharePoint, Excel files, shared drives, and manually managed workflows.

This creates risk because users may have excessive access, permissions may not be reviewed consistently, and AI-enabled workloads may retrieve information from sources that are not properly governed.

## Recommended Identity Model

Microsoft Entra ID should be used as the centralized identity provider for users, administrators, applications, and service access.

## Access Control Recommendations

| Area | Recommendation |
|---|---|
| User access | Use Microsoft Entra ID groups for role-based access |
| Administrative access | Limit privileged roles and review regularly |
| Application access | Use managed identities where possible |
| Data access | Restrict access based on least privilege |
| AI access | Limit AI retrieval to approved and permission-aware content |
| Reviews | Conduct periodic access reviews |

## RBAC Principles

The customer should apply the following RBAC principles:

- Grant least privilege access.
- Avoid assigning broad owner permissions.
- Separate administrative, developer, analyst, and business user roles.
- Use groups instead of direct user assignments where possible.
- Review access regularly.
- Document workload owners and access approvers.

## AI Access Considerations

AI-enabled workloads should not have unrestricted access to internal documents, databases, or operational records.

Before AI access is granted, the customer should define:

- Approved data sources
- Data owners
- Access boundaries
- Review process
- Logging requirements
- Human escalation process

## Recommended Outcome

The target identity model should provide secure, auditable, and manageable access across modernized applications, data sources, reporting tools, and AI workloads.
