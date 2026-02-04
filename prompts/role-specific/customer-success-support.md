# Copilot for Customer Success & Support

> Master Microsoft 365 Copilot for customer success and support roles. Contains [APPROVED] production-safe prompts for CSMs, Support Leads, and Account Managers with role-specific guardrails.

**Category:** Operations & Support

**Total Prompts:** 16

---

[← Back to Main Library](../../README.md)

---

### Account Health

#### 1. [APPROVED] Customer Health Summary

**Use Case:** Gather qualitative account context from communications. Use CS platform for health metrics.

**Target Personas:** Customer Success Manager, Account Manager, Client Partner

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `customer-success`, `account-health`, `review`

**Prompt:**

```
You are assisting a customer success manager. Search my emails and Teams for all recent interactions with [Customer Name]. Summarize:
- Recent conversations and their tone
- Issues or concerns raised
- Feature requests or feedback
- Usage or adoption discussions
- Upcoming renewal mentions
- Escalations or risks identified

This is for my account review. Health scores come from our CS platform.
```

---

### Account Planning

#### 1. [APPROVED] Relationship Mapping

**Use Case:** Map account relationships from communication patterns.

**Target Personas:** Account Manager, Customer Success Manager, Strategic Account Manager

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `account-management`, `relationship`, `mapping`

**Prompt:**

```
You are assisting an account manager. Search for all contacts and interactions with [Account Name]. Create a relationship map showing:
- Key contacts and their roles
- Interaction frequency
- Topics they engage on
- Champions vs. detractors (based on tone)
- Organizational changes mentioned
- Reporting relationships discussed

This is for account planning.
```

---

### Account Transitions

#### 1. [APPROVED] Handoff Documentation

**Use Case:** Create account handoff documentation from relationship history.

**Target Personas:** Account Manager, Customer Success Manager, Client Partner

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `account-management`, `handoff`, `transition`

**Prompt:**

```
I am transitioning [Account Name] to a new account manager. Compile a handoff document including:
- Key contacts and relationship status
- Ongoing initiatives
- Open issues or concerns
- Upcoming milestones (renewals, QBRs)
- Historical context (wins, challenges)
- My recommendations

Format as comprehensive handoff brief.
```

---

### Business Reviews

#### 1. [APPROVED] QBR Preparation

**Use Case:** Prepare QBR content from relationship context. Add platform metrics separately.

**Target Personas:** Customer Success Manager, Account Manager, Customer Success Director

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `customer-success`, `qbr`, `preparation`

**Prompt:**

```
I have a Quarterly Business Review with [Customer Name]. Search for:
- Value delivered this quarter (mentions of success, ROI, wins)
- Challenges or issues that occurred
- Support tickets discussed
- Product feedback provided
- Goals for next quarter mentioned
- Expansion or upsell conversations

Compile as QBR prep notes. I will add usage data from our systems.
```

---

### Contract Management

#### 1. [APPROVED] Contract Discussion Summary

**Use Case:** Gather contract negotiation context. Legal review required for actual terms.

**Target Personas:** Account Manager, Customer Success Manager, Commercial Manager

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `account-management`, `contract`, `negotiation`

**Prompt:**

```
Search for discussions about contract terms with [Account Name]. Summarize:
- Terms being negotiated
- Concerns raised by either party
- Pricing discussions
- SLA discussions
- Legal points raised
- Timeline pressures mentioned

This is background for contract negotiation. Actual terms require legal review.
```

---

### Customer Communication

#### 1. [APPROVED] Customer Communication Draft

**Use Case:** Draft customer support communications for review.

**Target Personas:** Support Lead, Support Specialist, Technical Support Engineer

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `support`, `communication`, `customer`

**Prompt:**

```
Draft an update email to [Customer Name] about their support case [Case Reference]. Include:
- Acknowledgment of the issue
- Current status
- Next steps being taken
- Expected resolution timeline
- Apology if appropriate

Keep tone professional and empathetic. I will review before sending.
```

---

### Escalation Management

#### 1. [APPROVED] Escalation Context Summary

**Use Case:** Gather escalation context from communications for resolution meetings.

**Target Personas:** Support Lead, Support Manager, Technical Support Engineer

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `support`, `escalation`, `context`

**Prompt:**

```
You are assisting a support lead. Search for all communications about the escalation from [Customer Name] regarding [Issue]. Compile:
- Timeline of the issue
- Troubleshooting steps discussed
- Customer impact mentioned
- Internal discussions and decisions
- Current status
- Committed resolution timeline

I need this for the escalation review meeting.
```

---

### Expansion

#### 1. [APPROVED] Expansion Opportunity Research

**Use Case:** Identify expansion signals from customer communications.

**Target Personas:** Customer Success Manager, Account Manager, Account Executive

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `customer-success`, `expansion`, `upsell`

**Prompt:**

```
Search for signals of expansion opportunity with [Customer Name]:
- New use cases mentioned
- Additional departments discussed
- Pain points that our other products solve
- Budget cycle mentions
- Growth indicators
- Champion referrals to other teams

Compile as expansion opportunity brief.
```

---

### Governance

#### 1. ⚠️ Customer Success & Support Copilot Guardrails

**Use Case:** Essential guardrails for customer success and support professionals using Copilot.

**Target Personas:** Customer Success Manager, Support Lead, Account Manager

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `guardrails`, `governance`, `customer-success`, `support`

**Prompt:**

```
