# Cloud Readiness Assessment

## Purpose

This assessment evaluates Contoso Operations' readiness to modernize legacy applications, data sources, reporting workflows, and operational processes on Microsoft Azure.

The assessment focuses on the foundational capabilities needed before production AI workloads can be deployed securely and reliably.

## Readiness Categories

| Category | Current State | Readiness Level | Recommendation |
|---|---|---|---|
| Identity and Access | Inconsistent access practices across systems | Medium | Standardize on Microsoft Entra ID, RBAC, and managed identities |
| Data Platform | Data spread across SQL Server, Excel, SharePoint, and file shares | Low | Modernize core data sources into Azure SQL Database and governed storage |
| Application Hosting | Legacy/internal apps with limited scalability | Low | Evaluate Azure App Service or Azure Container Apps for modern hosting |
| Monitoring | Limited centralized monitoring and alerting | Low | Implement Azure Monitor and Application Insights |
| Security Posture | Secrets and permissions not consistently governed | Low | Use Azure Key Vault, Defender for Cloud, and Azure Policy |
| Governance | Limited cloud operating model | Low | Establish CAF-aligned governance, tagging, policy, and cost controls |
| AI Readiness | Interest in AI but no production-ready foundation | Low | Prepare data, identity, monitoring, and governance before scaling AI workloads |

## Key Findings

### 1. Data fragmentation creates AI risk

Data is spread across multiple systems, which makes it difficult to ensure that AI responses are grounded in approved, current, and governed sources.

### 2. Manual workflows limit scalability

Processes that depend on email and spreadsheets are difficult to monitor, audit, and automate at scale.

### 3. Monitoring needs to be centralized

Before introducing production AI workloads, the organization needs consistent observability across applications, data services, and AI-enabled workflows.

### 4. Security controls need modernization

The environment should move toward managed identities, centralized secrets management, role-based access, and security posture monitoring.

### 5. Governance must be established before scale

AI adoption should not proceed without clear policies for access, cost management, logging, data retention, and operational ownership.

## Readiness Summary

Contoso Operations is not yet ready for production-scale AI adoption. The organization should first establish a secure and governed Azure foundation, modernize core data and application platforms, and define an operational model for monitoring, support, and cost control.
