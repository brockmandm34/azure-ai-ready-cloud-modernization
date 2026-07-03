# CAF Adopt Alignment

## Purpose

The Adopt phase focuses on migration and modernization of workloads into Azure.

For Contoso Operations, adoption should begin with high-value operational workloads that are currently limited by manual processes, fragmented data, and inconsistent reporting.

## Candidate Workloads for Adoption

| Workload | Current State | Azure Modernization Path |
|---|---|---|
| Operational request tracking | SharePoint lists and email handoffs | Power Platform with Dataverse or Azure-backed app |
| Legacy reporting database | SQL Server and Excel extracts | Azure SQL Database with Power BI reporting |
| Document knowledge base | Shared drives and scattered files | Azure Storage with Azure AI Search |
| Manual approval workflows | Email approvals | Power Automate or Azure Logic Apps |
| Internal knowledge assistant | Not available | Azure AI Search + Azure OpenAI / Azure AI Foundry |
| Monitoring and alerting | Limited | Azure Monitor + Application Insights |

## Adoption Approach

The recommended adoption approach is:

1. Select one business-critical but manageable pilot workflow.
2. Modernize the supporting data source.
3. Implement monitoring and security controls.
4. Validate business value with measurable outcomes.
5. Expand the pattern to related workflows.

## AI Adoption Guidance

AI adoption should be treated as a workload modernization effort, not a standalone experiment.

Before scaling AI, the customer should confirm:

- Data sources are approved and governed.
- Access controls are enforced.
- Outputs are grounded and reviewable.
- Usage and cost are monitored.
- Business owners understand limitations and risks.
- Human escalation paths exist.

## Adoption Outcome

The customer should use the first modernization effort as repeatable IP for future Azure and AI adoption. The goal is not just to deploy one workload, but to create a reusable pattern for modernizing additional workflows.
