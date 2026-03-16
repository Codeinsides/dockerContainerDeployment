# ServiceNow Developer — Accenture

Apply link: https://www.accenture.com/careers/jobdetails?id=servicenow-developer

# ServiceNow Implementation Use Cases

These examples show practical implementation and ongoing management patterns for core ServiceNow modules.

## 1) CSM Case Deflection with Knowledge + Virtual Agent
**Module:** Customer Service Management (CSM), Knowledge Management, Virtual Agent  
**Implementation example:**
- Design a case taxonomy and map intents to knowledge articles.
- Build Virtual Agent topics for top contact drivers (password reset, order status, entitlement checks).
- Configure auto-suggested knowledge in case creation and portal search.

**Management example:**
- Weekly review of unresolved intents and low-confidence bot handoffs.
- Monthly knowledge curation (retire duplicates, improve article quality).
- SLA dashboard for first response and resolution by channel.

**Target KPI:** 20–35% ticket deflection, faster mean time to resolve (MTTR).

## 2) ITSM Incident-to-Problem Automation
**Module:** ITSM Incident, Problem, Change  
**Implementation example:**
- Configure incident categorization with CI/service mapping in CMDB.
- Create flow that opens/updates Problem records from recurring P1/P2 incidents.
- Add change-risk checks and CAB approvals tied to affected services.

**Management example:**
- Review top recurring incidents every sprint and track known error backlog.
- Enforce post-incident review templates and owner accountability.
- Monitor change success rate and rollback ratio.

**Target KPI:** Fewer repeat incidents, improved change success, reduced outage duration.

## 3) HRSD Employee Onboarding Orchestration
**Module:** HR Service Delivery (HRSD), Catalog, Flow Designer  
**Implementation example:**
- Build onboarding catalog items (hardware, accounts, compliance tasks).
- Orchestrate cross-team tasks (HR, IT, Facilities, Security) with due dates.
- Add lifecycle events for pre-hire, day-1, and probation checkpoints.

**Management example:**
- Track task bottlenecks and missed SLAs by fulfillment group.
- Quarterly review of onboarding journey and requester satisfaction.
- Maintain catalog governance and retire unused request items.

**Target KPI:** Shorter time-to-productivity, higher onboarding CSAT, lower manual handoffs.
