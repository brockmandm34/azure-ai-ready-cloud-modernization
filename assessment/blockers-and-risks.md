# Blockers and Risks

## Purpose

This document identifies potential blockers that could slow modernization, delay AI adoption, or create operational risk during implementation.

## Key Blockers

| Blocker | Description | Mitigation |
|---|---|---|
| Fragmented data ownership | Data exists across SQL Server, Excel, SharePoint, and file shares with unclear ownership | Define data owners and prioritize high-value sources |
| Limited cloud governance | No consistent tagging, policy, cost, or access model | Establish governance baseline using CAF guidance |
| Manual workflow dependency | Business processes rely on email and spreadsheet handoffs | Modernize priority workflows through phased automation |
| Identity inconsistency | Permissions vary across systems | Standardize access with Microsoft Entra ID and RBAC |
| Lack of monitoring | Current systems have limited centralized observability | Implement Azure Monitor and Application Insights |
| Security concerns around AI | AI access to sensitive data may create compliance concerns | Use approved sources, access controls, logging, and human review |
| Change management risk | Users may resist new tools and workflows | Use phased rollout, training, and stakeholder engagement |

## Technical Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Data quality issues | AI and reporting outputs may be inaccurate | Conduct data profiling and validation |
| Poorly scoped pilot | Pilot may fail to show value | Select a focused use case with measurable outcomes |
| Cost growth | Cloud and AI usage may expand without visibility | Implement cost alerts, tagging, and usage reporting |
| Over-permissioned identities | Security exposure | Apply least privilege and managed identities |
| Missing backup/DR plan | Business continuity risk | Define RTO/RPO and backup strategy |
| Insufficient monitoring | Issues may go undetected | Build operational monitoring into the initial design |

## Business Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Unclear success metrics | Difficult to prove business value | Define adoption, efficiency, cost, and quality metrics |
| Lack of executive alignment | Modernization may lose momentum | Maintain executive briefings and roadmap visibility |
| Competing priorities | Delivery may stall | Prioritize use cases by ROI and feasibility |
| Compliance uncertainty | AI adoption may be delayed | Engage security and governance stakeholders early |

## Risk Summary

The highest-priority risks are data fragmentation, weak governance, inconsistent access controls, and lack of operational monitoring. These should be addressed before scaling production AI workloads.
