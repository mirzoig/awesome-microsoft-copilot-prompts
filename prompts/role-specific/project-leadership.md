# Copilot for Project Leadership

> Master Microsoft 365 Copilot for leadership and project management roles. Contains [APPROVED] production-safe prompts for Executives, Project Managers, and Cost Control/PMO professionals with role-specific guardrails.

**Category:** Finance & Analytics

**Total Prompts:** 18

---

[← Back to Main Library](../../README.md)

---

### Budget Management

#### 1. [APPROVED] Budget Meeting Preparation

**Use Case:** Enter budget reviews prepared with full context on recent cost discussions and concerns.

**Target Personas:** Cost Controller, Finance Manager, PMO Director

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `cost-control`, `budget`, `meeting-prep`

**Prompt:**

```
I have a budget review meeting for [Project Name] with [stakeholder]. Based on recent correspondence:
- What cost concerns have been raised recently?
- Are there any pending change requests?
- What has been communicated about forecast trends?
- Any commitments or approvals I should be aware of?

Prepare as briefing notes for my preparation.
```

---

### Change Management

#### 1. [APPROVED] Change Order History

**Use Case:** Track informal change order discussions and ensure they are captured in formal systems.

**Target Personas:** Cost Controller, Change Manager, PMO Analyst

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `cost-control`, `change-orders`, `tracking`

**Prompt:**

```
Find all emails and documents related to change orders on [Project Name] from [date range]. For each change order mentioned:
- Change order reference (if stated)
- Brief description of scope change
- Status discussed (pending, approved, rejected)
- Any cost/schedule impact mentioned

I need this to cross-reference against our formal change register.
```

---

### Client Communication

#### 1. [APPROVED] Client Communication Draft - PM

**Use Case:** Draft client communications quickly while ensuring all relevant information is captured and tone is appropriate.

**Target Personas:** Project Manager, Account Manager, Delivery Manager

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `project-management`, `client-comms`, `email-draft`

**Prompt:**

```
Draft a professional email to [Client Contact] providing a [weekly/monthly] update on [Project Name]. Base the content on my recent project correspondence. Include:
- Summary of progress
- Key achievements
- Any items requiring client attention or decision
- Upcoming milestones

Keep tone factual and professional. Mark areas where I need to add specifics or verify accuracy before sending.
```

---

### Cost Reporting

#### 1. [APPROVED] Cost Variance Narrative

**Use Case:** Draft variance explanations based on team discussions. Numbers must always come from official cost systems.

**Target Personas:** Cost Controller, Cost Engineer, PMO Analyst

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `cost-control`, `variance`, `narrative`

**Prompt:**

```
You are assisting a cost controller. Search my emails and Teams messages for discussions about cost variances on [Project Name]. Summarize:
- What variance explanations have been provided
- Which cost codes or areas are mentioned as over/under
- What corrective actions were discussed
- Any forecast concerns raised

This is for drafting the narrative section of the cost report. I will add the actual numbers from our cost system.
```

---

### Decision Support

#### 1. [APPROVED] Decision Context Research

**Use Case:** Gather comprehensive context before making important decisions without scheduling multiple briefing meetings.

**Target Personas:** Executive, Director, VP, Senior Manager

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `executive`, `decision-support`, `research`

**Prompt:**

```
I need to make a decision about [topic]. Search for:
- Previous discussions about this topic
- Options that have been considered
- Recommendations from my team
- Risks and concerns raised

Compile background context for my decision-making.
```

---

### Decision Tracking

#### 1. [APPROVED] Decision Log Research

**Use Case:** Reconstruct decision history from communications when formal records are incomplete or need verification.

**Target Personas:** Project Manager, Program Manager, PMO Analyst

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `project-management`, `decisions`, `audit-trail`

**Prompt:**

```
Search my emails and Teams for decisions made on [Project Name] regarding [topic area, e.g., "design freeze" or "contractor selection"]. For each decision found:
- What was decided
- When (approximately)
- Who was involved
- Any conditions or follow-up actions mentioned

I need this to reconstruct the decision trail. Will verify against formal records.
```

---

### Estimating

#### 1. [EXPERIMENTAL] Benchmarking Data Search

**Use Case:** Find historical cost data for benchmarking new estimates. Requires validation for current applicability.

**Target Personas:** Cost Engineer, Estimator, PMO Analyst

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `cost-control`, `benchmarking`, `experimental`

**Prompt:**

```
Search SharePoint and my files for cost data, estimates, or lessons learned from similar past projects to [current project type]. List:
- Project names/references found
- Types of cost data available
- Any benchmark metrics mentioned

This is research only — data requires validation before use.

⚠️ EXPERIMENTAL: Historical data may be in various formats or contexts. Always validate applicability before using for estimates.
```

---

### Executive Communication

#### 1. [APPROVED] Executive Communication Draft

**Use Case:** Quickly draft executive communications while maintaining appropriate tone and completeness.

**Target Personas:** CEO, Executive, Director, VP

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `executive`, `communication`, `draft`

**Prompt:**

```
Draft a communication to [audience: leadership team/all employees/board] about [topic]. Based on similar communications in my history:
- Use appropriate executive tone
- Be clear and direct
- Include key message points
- Mark areas needing specific details

This is a draft for my review and editing.
```

---

### Executive Preparation

#### 1. [APPROVED] Leadership Meeting Preparation

**Use Case:** Walk into leadership meetings fully prepared with context on all likely discussion topics and pending decisions.

**Target Personas:** CEO, Executive, Director, VP

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `executive`, `meeting-prep`, `leadership`

**Prompt:**

```
You are assisting an executive. I have a [board/leadership/steering committee] meeting tomorrow. Based on my emails and calendar from the past two weeks:
- What are the key topics likely to be discussed?
- What issues have escalated to my attention?
- What decisions am I expected to make?
- Any risks or concerns raised by my team?

Prepare briefing notes for my review. This is for my preparation only.
```

---

### Governance

#### 1. ⚠️ Leadership Copilot Guardrails

**Use Case:** Essential guardrails for leadership roles using Copilot. Understand the boundaries between AI assistance and human accountability.

**Target Personas:** Executive, Project Manager, Cost Controller, PMO Director

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `guardrails`, `governance`, `leadership`

**Prompt:**

```
