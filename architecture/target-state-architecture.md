# Target-State Architecture

## Purpose

The target-state architecture defines the Azure foundation Contoso Operations should move toward to support modernized applications, governed data, improved reporting, and production-ready AI workloads.

## High-Level Architecture Flow

```text
Users
  ↓
Microsoft Entra ID
  ↓
Modernized Applications
  ↓
Azure App Service / Azure Container Apps
  ↓
Azure SQL Database + Azure Storage
  ↓
Azure AI Search
  ↓
Azure OpenAI / Azure AI Foundry
  ↓
Azure Monitor + Application Insights
  ↓
Power BI / Executive Reporting
```

## Supporting Controls

The architecture should also include:

- Azure Key Vault
- Managed identities
- Role-based access control
- Microsoft Defender for Cloud
- Azure Policy
- Azure Cost Management
- Backup and recovery planning
- Dev, test, and production environment separation

## Workload Layers

### 1. Identity Layer

Microsoft Entra ID provides centralized authentication and supports RBAC, conditional access, and access reviews.

### 2. Application Layer

Azure App Service or Azure Container Apps hosts modernized internal applications and workflow interfaces.

### 3. Data Layer

Azure SQL Database supports relational data modernization. Azure Storage supports document and file storage for approved content.

### 4. AI Retrieval Layer

Azure AI Search indexes approved documents and data sources to support grounded AI responses.

### 5. AI Application Layer

Azure OpenAI or Azure AI Foundry supports AI-assisted knowledge search, summarization, reporting assistance, and workflow support.

### 6. Observability Layer

Azure Monitor and Application Insights provide visibility into application health, failures, latency, and usage.

### 7. Reporting Layer

Power BI provides executive and operational reporting for modernization progress, AI adoption, cost, and business value.

## Target-State Outcomes

The target architecture should help the customer:

- Reduce manual operational work
- Improve data reliability
- Strengthen identity and access controls
- Improve monitoring and supportability
- Create a governed foundation for AI workloads
- Provide leadership with adoption and outcome visibility
