# ServiceNow ITSM Incident-to-Problem Automation

## Executive Summary
This repository contains a senior-level implementation blueprint for a production ServiceNow program.

## Problem Solved
Recurring P1/P2 incidents were managed reactively with weak correlation to Problem and Change workflows, causing repeated outages.

## Primary User Story
> As a Service Operations Manager, I want recurring incidents to automatically trigger problem investigations and risk-aware change governance so that we reduce repeat failures.

## Implementation Scope
- Platform architecture and domain boundaries
- Data model and governance controls
- Operational runbooks and KPI instrumentation
- API surface for integration and reporting

## Solution Overview
Automated incident clustering, problem candidate creation, known error updates, and change risk scoring with CAB policy gates.

## Senior-Level Delivery Elements
- Architecture Decision Record (ADR) and tradeoffs
- Delivery roadmap with phased rollout
- Risks, controls, and non-functional requirements (NFRs)
- Test strategy and release governance
- Lessons learned and continuous improvement backlog

## KPIs
- Repeat incidents -25%
- Change success rate >= 92%
- Rollback rate < 5%
- P1 resolution time -20%

## Repository Structure
- `docs/architecture.md` – architecture, quality attributes, and tradeoffs
- `docs/user-stories.md` – epic and story decomposition with acceptance criteria
- `docs/problem-solved.md` – problem framing, impact, and measurable outcomes
- `docs/lessons-learned.md` – retrospectives and implementation learnings
- `api/openapi.yaml` – integration contract for operational telemetry
- `src/` – implementation placeholders/scripts
- `tests/` – validation placeholders

## Getting Started
1. Read `docs/problem-solved.md` for business context.
2. Review `docs/architecture.md` for module design and controls.
3. Validate API contract in `api/openapi.yaml`.
4. Execute quality gates before production rollout.
