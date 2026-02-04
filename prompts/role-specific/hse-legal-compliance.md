# Copilot for HSE, Legal & Compliance

> Master Microsoft 365 Copilot for HSE, legal, and IT compliance roles. Contains [APPROVED] production-safe prompts for HSE/Quality, Legal/Contracts, and IT/Cloud professionals with strict safety guardrails.

**Category:** Security & Compliance

**Total Prompts:** 20

---

[← Back to Main Library](../../README.md)

---

### Architecture

#### 1. [EXPERIMENTAL] Architecture Decision Research

**Use Case:** Research architecture decisions from discussions. Always verify current state with architecture team.

**Target Personas:** Solutions Architect, IT Manager, Technical Lead

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `it`, `architecture`, `experimental`

**Prompt:**

```
Search internal documents and emails for discussions about [technology decision, e.g., "container orchestration" or "API gateway selection"]. Compile:
- Options considered
- Pros/cons discussed
- Decisions made and rationale
- Any revisits or regrets mentioned

This is research for architecture documentation.

⚠️ EXPERIMENTAL: Technical decisions may have evolved. Verify current state with the architecture team.
```

---

### Change Management

#### 1. [APPROVED] CAB Meeting Preparation

**Use Case:** Prepare for CAB meetings with context on pending changes and concerns.

**Target Personas:** IT Manager, Change Manager, CAB Member

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `it`, `cab`, `change-management`

**Prompt:**

```
I have a Change Advisory Board meeting. Based on recent emails and Teams:
- What changes are pending approval?
- What concerns have been raised about upcoming changes?
- Any failed changes being discussed?
- Risk assessments mentioned?

Prepare briefing notes for my preparation.
```

---

#### 2. [APPROVED] Change Request Preparation

**Use Case:** Research previous change implementations to prepare comprehensive change requests.

**Target Personas:** IT Manager, Change Manager, Systems Administrator

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `it`, `change-management`, `preparation`

**Prompt:**

```
I'm preparing a change request for [change description]. Search for:
- Similar changes previously implemented
- Any risks or issues that were raised
- Approvals that were required
- Rollback procedures mentioned

Help me prepare a thorough change request by gathering precedents.
```

---

### Claims Management

#### 1. [APPROVED] Claim Timeline Summary

**Use Case:** Organize claim timeline from correspondence. Legal analysis requires qualified legal review.

**Target Personas:** Claims Manager, Legal Counsel, Commercial Manager

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `legal`, `claims`, `timeline`

**Prompt:**

```
Search emails and documents related to [Claim Reference] and compile a chronological summary:
- When the claim was first notified
- Key communications and their dates
- Responses received
- Current status discussed

This is for case file organization — requires legal review for formal use.
```

---

### Contract Negotiation

#### 1. [APPROVED] Negotiation History Research

**Use Case:** Research contract negotiation history for preparation. Legal analysis requires qualified legal review.

**Target Personas:** Contracts Manager, Legal Counsel, Commercial Manager

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `legal`, `contracts`, `negotiation`

**Prompt:**

```
You are assisting a contracts professional. Search my emails for the negotiation history of [Contract Reference/Name]. Compile:
- Key issues raised by each party
- Positions and counter-positions
- Compromises reached
- Outstanding items at last discussion

This is research for my preparation — not legal analysis.
```

---

### Contract Standards

#### 1. [EXPERIMENTAL] Contract Pattern Research

**Use Case:** Research contract patterns across deals. Legal applicability requires formal legal review.

**Target Personas:** Legal Counsel, Contracts Manager, General Counsel

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `legal`, `patterns`, `experimental`

**Prompt:**

```
Search our contracts database in SharePoint for patterns in how [clause type] is handled across different client types or jurisdictions. Note:
- Variations observed
- Common language patterns
- Any issues flagged in reviews

This is research for internal guidance — requires legal validation.

⚠️ EXPERIMENTAL: Contract patterns may have contextual reasons not visible in summaries. Always consult legal.
```

---

### Critical Guardrails

#### 1. ⛔ HSE CRITICAL GUARDRAILS - READ FIRST

**Use Case:** CRITICAL: Read this before any HSE use of Copilot. Print and post in HSE offices and site facilities.

**Target Personas:** HSE Manager, Safety Officer, Quality Manager, Site Manager, Project Manager

**Tags:** `copilot`, `microsoft-365`, `enterprise`, `hse`, `safety`, `guardrails`, `critical`

**Prompt:**

```
