# Production Readiness Checklist

## Purpose

This checklist defines the minimum readiness criteria before Contoso Operations moves modernized Azure or AI-enabled workloads into production.

## Identity and Access

- [ ] Microsoft Entra ID integration defined
- [ ] RBAC model documented
- [ ] Least privilege access applied
- [ ] Administrative roles reviewed
- [ ] Access owners identified
- [ ] AI-accessible data sources approved
- [ ] Access review cadence defined

## Security

- [ ] Azure Key Vault pattern defined
- [ ] Managed identities used where possible
- [ ] Secrets removed from code and workflow configuration
- [ ] Defender for Cloud enabled
- [ ] Azure Policy baseline defined
- [ ] Security recommendations reviewed
- [ ] Data classification documented

## Monitoring and Operations

- [ ] Azure Monitor configured
- [ ] Application Insights configured where applicable
- [ ] Critical alerts defined
- [ ] Log retention requirements documented
- [ ] Support owner identified
- [ ] Escalation path documented
- [ ] Runbook created
- [ ] Incident response expectations defined

## Reliability

- [ ] Backup and restore strategy documented
- [ ] RTO and RPO expectations defined
- [ ] Availability requirements documented
- [ ] Manual fallback process defined for critical workflows
- [ ] AI fallback process defined where applicable
- [ ] Disaster recovery assumptions reviewed

## Cost Management

- [ ] Budget defined
- [ ] Cost alerts configured
- [ ] Tags applied for owner, environment, workload, and cost center
- [ ] AI usage cost model documented
- [ ] Cost review cadence defined

## AI Governance

- [ ] Approved data sources identified
- [ ] AI use case owner identified
- [ ] Prompt and response review process defined
- [ ] Human escalation workflow documented
- [ ] User feedback collection defined
- [ ] Risk event review process documented
- [ ] AI limitations communicated to pilot users

## Go-Live Criteria

A workload should not move into production until:

- Security controls are reviewed.
- Monitoring and alerting are active.
- Ownership and support model are documented.
- Backup and recovery expectations are defined.
- Cost controls are in place.
- AI governance controls are approved, if applicable.

## Production Readiness Outcome

The checklist helps ensure that modernized and AI-enabled workloads are secure, supportable, observable, cost-aware, and aligned to customer business goals before go-live.
