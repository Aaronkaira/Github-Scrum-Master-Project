# Jira Workflows & Governance Model

## Purpose

This document defines the **standardized Jira workflows** used across multiple Scrum teams to ensure:

* Clear ticket progression
* Strong governance and accountability
* Accurate reporting and KPIs
* Predictable delivery outcomes

The Scrum Master owns enforcement of these workflows and ensures consistent adoption across teams.

---

## Workflow Overview

Two primary workflows are used:

1. **Project Delivery Workflow**
2. **BAU / Operational Workflow**

Both workflows share governance rules but differ in prioritization and SLA expectations.

---

## 1️⃣ Project Delivery Workflow

### Workflow States

**Backlog**

* Ticket created but not yet refined
* May lack estimation or acceptance criteria
* Not eligible for sprint commitment

**Refinement**

* Acceptance criteria reviewed
* Dependencies identified
* Story points estimated
* Ticket validated against Definition of Ready

**Ready for Sprint**

* Meets all DoR criteria
* Prioritized by Product Owner
* Eligible for Sprint Planning

**In Progress**

* Actively being worked on
* Assignee clearly defined
* Work aligned to sprint goals

**In Review / Testing**

* Development complete
* Under QA, validation, or peer review
* Defects addressed or documented

**Done**

* Meets Definition of Done
* Releasable or released
* Jira ticket closed with proper hygiene

---

## 2️⃣ BAU / Operational Workflow

### Workflow States

**Intake**

* BAU request raised
* Initial classification and urgency assessment

**Triage**

* Priority assigned
* Impacted systems identified
* Routed to appropriate team

**Ready**

* Scoped and estimated
* Capacity allocation agreed
* Approved for execution

**In Progress**

* Actively worked on
* SLA tracked if applicable

**Resolved**

* Fix implemented
* Validation completed

**Closed**

* Stakeholder confirmation
* Ticket archived for reporting

---

## Workflow Governance Rules

### Mandatory Transition Rules

* Tickets **cannot move to Ready** without meeting Definition of Ready
* Tickets **cannot move to Done/Closed** without meeting Definition of Done
* All transitions require an assignee

---

### Required Jira Fields

The following fields are mandatory before a ticket may progress:

* Acceptance Criteria
* Story Points (where applicable)
* Priority
* Labels:

  * Team (Alpha / Beta / Gamma)
  * Work Type (Project / BAU)
  * Impacted System
* Dependency flag (Yes / No)

---

### Dependency Management

* Cross-team dependencies must be:

  * Flagged in Jira
  * Linked to related tickets
  * Reviewed during refinement and sprint planning
* Dependency risks escalated by Scrum Master

---

## Scrum Master Governance Responsibilities

The Scrum Master is accountable for:

* Enforcing workflow compliance
* Preventing ticket bypassing
* Identifying bottlenecks and workflow breakdowns
* Ensuring Jira remains a **single source of truth**
* Coaching teams on proper Jira usage

---

## KPI Alignment

These workflows directly support tracking of:

* Sprint velocity
* Cycle time
* Work-in-progress limits
* Delivery predictability
* BAU vs Project capacity allocation

---

## Outcomes

Effective workflow governance results in:

* Cleaner backlogs
* Improved reporting accuracy
* Reduced delivery friction
* Increased leadership confidence in Agile metrics

---
