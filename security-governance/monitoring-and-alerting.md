# Monitoring and Alerting

## Purpose

This document defines monitoring and alerting recommendations for Contoso Operations' Azure modernization and AI-ready cloud foundation.

## Monitoring Goals

The monitoring strategy should help the customer:

- Detect application failures
- Track performance and latency
- Monitor database and storage health
- Identify cost anomalies
- Review security posture changes
- Observe AI usage, failures, risk events, and feedback
- Support incident response and continuous improvement

## Recommended Monitoring Services

| Service | Purpose |
|---|---|
| Azure Monitor | Central monitoring platform for Azure resources |
| Application Insights | Application performance monitoring and diagnostics |
| Log Analytics | Query and analyze logs using KQL |
| Defender for Cloud | Security posture and recommendations |
| Cost Management | Budgeting, forecasting, and cost visibility |
| Power BI | Business-facing reporting and executive visibility |

## Recommended Alerts

| Alert | Reason |
|---|---|
| Application availability failure | Detect user-facing outages |
| High response latency | Identify performance degradation |
| High error rate | Detect application or workflow issues |
| Database connection failures | Identify data platform problems |
| Cost anomaly | Prevent uncontrolled cloud or AI spend |
| Security recommendation change | Detect security posture issues |
| AI risk event spike | Trigger review of flagged AI interactions |
| Missing telemetry | Detect logging or monitoring failure |

## AI Monitoring Considerations

AI workloads should include monitoring for:

- Request volume
- User adoption
- Response latency
- Failure rate
- Token or usage cost
- Flagged interactions
- User feedback
- Source grounding quality
- Escalations to human review

## Operational Review Cadence

The customer should review monitoring data on a regular schedule:

| Cadence | Review Area |
|---|---|
| Daily | Critical alerts and system health |
| Weekly | Usage, errors, latency, and cost trends |
| Monthly | Governance, risk events, adoption, and optimization |
| Quarterly | Architecture improvements and roadmap updates |

## Recommended Outcome

The target monitoring model should provide both technical observability and business-facing visibility into modernization progress, workload health, AI usage, cost, and risk.
