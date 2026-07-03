# CAF Manage Alignment

## Purpose

The Manage phase defines how cloud workloads are monitored, operated, supported, and continuously improved.

For Contoso Operations, management capabilities must be established before the organization scales production AI workloads.

## Operational Management Areas

| Area | Recommendation |
|---|---|
| Monitoring | Use Azure Monitor and Application Insights |
| Alerting | Define alerts for availability, performance, failures, and cost anomalies |
| Incident response | Establish ownership and escalation paths |
| Change management | Define deployment and approval process |
| Cost management | Monitor usage and budget impact |
| Reliability | Define backup, restore, and recovery expectations |
| AI operations | Monitor AI usage, latency, failure rates, and risk events |

## Recommended Alerts

The customer should define alerts for:

- Application availability
- High failure rate
- High response latency
- Database connection failures
- Cost anomalies
- Security posture changes
- Repeated AI safety or risk events
- Missing telemetry from critical workloads

## Support Model

Each production workload should have:

- Business owner
- Technical owner
- Support contact
- Monitoring dashboard
- Escalation path
- Recovery plan
- Cost owner
- Documentation owner

## Manage Outcome

The customer should be able to operate modernized workloads with clear visibility, ownership, and response processes. For AI workloads, management must include both technical observability and business-facing adoption reporting.
