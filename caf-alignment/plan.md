# CAF Plan Alignment

## Purpose

The Plan phase translates business strategy into an actionable cloud adoption roadmap.

For Contoso Operations, the plan must sequence modernization activities so the organization can improve operations without disrupting critical business processes.

## Planning Assumptions

- The organization has fragmented data across SQL Server, Excel, SharePoint, and shared drives.
- Business users rely heavily on manual workflows and email-based approvals.
- Leadership wants to adopt AI, but AI workloads should not be scaled before governance and data readiness are addressed.
- Security, monitoring, and cost controls need to be included early.
- The organization should begin with a focused pilot before broad rollout.

## Modernization Workstreams

| Workstream | Purpose |
|---|---|
| Identity and access | Standardize access using Microsoft Entra ID and RBAC |
| Data modernization | Move priority relational data to Azure SQL Database |
| Document modernization | Organize approved documents in governed storage |
| Application modernization | Host modernized apps using Azure App Service or Azure Container Apps |
| Workflow modernization | Replace manual handoffs with Power Platform or Azure-native automation |
| Monitoring | Implement Azure Monitor and Application Insights |
| Security governance | Use Key Vault, Defender for Cloud, and Azure Policy |
| AI pilot | Implement one controlled AI use case using approved data |

## Phased Plan

### Phase 1: Foundation

- Define cloud governance model
- Establish identity and access patterns
- Define tagging and cost management standards
- Configure monitoring and security baseline

### Phase 2: Modernization

- Prioritize high-value legacy workflows
- Modernize core data sources
- Improve reporting and operational visibility
- Replace manual workflow steps where feasible

### Phase 3: AI Readiness

- Identify approved knowledge sources
- Define AI governance and review process
- Build one controlled AI pilot
- Monitor usage, risk, cost, and performance

### Phase 4: Scale

- Expand successful modernization patterns
- Reuse architecture and deployment guidance
- Improve automation and operational support
- Continue cost, security, and performance optimization

## Planning Outcome

The customer should leave the planning phase with a prioritized backlog, phased roadmap, identified risks, and clear ownership for modernization and AI-readiness workstreams.
