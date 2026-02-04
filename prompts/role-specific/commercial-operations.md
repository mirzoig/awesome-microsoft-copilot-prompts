# Copilot for Commercial Operations

> Master Microsoft 365 Copilot for commercial and operations roles. Contains [APPROVED] production-safe prompts for Procurement, Document Control, and Planning/Scheduling professionals with role-specific guardrails.

**Category:** Operations & Support

**Total Prompts:** 18

---

[← Back to Main Library](../../README.md)

---

### Baseline Management

#### 1. [APPROVED] Baseline History Search

**Use Case:** Reconstruct baseline change history from communications. Always verify against scheduling software.

**Target Personas:** Planner, Scheduler, Project Controls Manager

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `planning`, `baseline`, `history`

**Prompt:**

```
Find references in emails and SharePoint to schedule baseline changes on [Project Name]. List:
- When baselines were discussed
- Reasons for rebaseline mentioned
- Approvals or rejections noted

I need this to reconstruct baseline history. Will verify against P6 baselines.
```

---

### Bid Management

#### 1. [APPROVED] Bid Clarification Draft

**Use Case:** Quickly draft bid clarification requests while maintaining professional procurement communication standards.

**Target Personas:** Procurement Manager, Buyer, Contracts Specialist

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `procurement`, `bid`, `clarification`

**Prompt:**

```
Draft a professional email to [Vendor Name] requesting clarification on their bid for [RFQ Reference]. Based on my notes and previous correspondence, address these points:
- [List specific clarification points]

Keep tone professional and neutral. I will review and add specific technical questions before sending.
```

---

### Contract Management

#### 1. [APPROVED] Contract History Search

**Use Case:** Gather comprehensive contract history before renewal negotiations.

**Target Personas:** Procurement Manager, Contracts Manager, Category Manager

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `procurement`, `contract`, `renewal`

**Prompt:**

```
Search for emails and documents related to our contract with [Vendor Name] including:
- Original contract discussions
- Any amendments or change orders
- Performance issues mentioned
- Claims or disputes

I need this to prepare for contract renewal discussions.
```

---

### Delay Analysis

#### 1. [APPROVED] Delay Analysis Research

**Use Case:** Gather delay discussion history to support formal delay analysis documentation.

**Target Personas:** Planner, Claims Analyst, Project Controls

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `planning`, `delay`, `analysis`

**Prompt:**

```
Search project correspondence for discussions about delays to [milestone/activity]. Compile:
- When the delay was first reported
- Causes mentioned by different parties
- Recovery proposals discussed
- Any schedule impact assessments referenced

This is research for delay analysis documentation — requires formal analysis.
```

---

### Distribution Control

#### 1. [APPROVED] Distribution List Verification

**Use Case:** Verify document distribution from email records. Always reconcile with formal distribution records.

**Target Personas:** Document Controller, Records Manager, Project Administrator

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `document-control`, `distribution`, `verification`

**Prompt:**

```
Search for emails where [Document Number or Type] was distributed or transmitted. List:
- Recipients included
- Dates sent
- Any bounce-backs or errors mentioned
- Acknowledgment receipts discussed

I need to verify against our distribution matrix.
```

---

### Document Management

#### 1. [APPROVED] Transmittal Status Search

**Use Case:** Track transmittal discussions across email threads. Always verify against EDMS for official status.

**Target Personas:** Document Controller, Technical Assistant, Project Administrator

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `document-control`, `transmittal`, `tracking`

**Prompt:**

```
You are assisting a document controller. Search my emails for correspondence about transmittal [Transmittal Number/Reference] including:
- Client comments or responses
- Internal review comments
- Status updates
- Any rejections or resubmission requests

Summarize the history for my records.
```

---

#### 2. [APPROVED] Outstanding Documents Follow-up

**Use Case:** Identify overdue documents and their causes from email discussions. Use to drive document status meetings.

**Target Personas:** Document Controller, Project Administrator, Engineering Administrator

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `document-control`, `overdue`, `follow-up`

**Prompt:**

```
Search my emails from the past 2 weeks for discussions about overdue documents or late deliverables for [Project Name]. List:
- Documents mentioned as late
- Reasons given for delays
- Commitments made for delivery dates
- Who is responsible (as mentioned)

I need this to prepare for the document status meeting.
```

---

### Governance

#### 1. ⚠️ Commercial Operations Copilot Guardrails

**Use Case:** Essential guardrails for commercial and operations roles using Copilot. Understand system boundaries and human accountability.

**Target Personas:** Procurement Manager, Document Controller, Planner, Scheduler

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `guardrails`, `governance`, `operations`

**Prompt:**

```
