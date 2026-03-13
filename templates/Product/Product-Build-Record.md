# Product Build Record

> The complete record of a discrete product effort — from problem definition through requirements, cost estimation, execution, and post-launch validation. This document follows the initiative from inception to retrospective and becomes the primary source of historical cost and outcome data for future estimates.
>
> **This document has a lifecycle.** Sections 1–11 are completed before build begins. Section 12 (Test and Validation) is completed during and after build. Sections 13 (Agent Handoff) is populated before handoff. Sections 14–15 are completed during and after execution. A Product Build Record is not complete until Section 15 is filled — the retrospective is not optional.
>
> Human teams may use this document without Section 13. AI-assisted teams should treat Section 13 as required.

---

## Document Control

| Field | Value |
|---|---|
| **Initiative Name** | |
| **Record Type** | Maintenance / Incremental Improvement / Strategic Request / Growth Initiative |
| **Status** | Scoping / Estimating / Approved / In Build / Complete / Cancelled |
| **Author** | |
| **Created** | YYYY-MM-DD |
| **Last Updated** | YYYY-MM-DD |
| **Target Release** | YYYY-MM-DD |
| **Actual Release** | YYYY-MM-DD |
| **Linked Business Case** | [Link or "Not required — see record type guidance below"] |
| **Linked Strategy Goal** | [Reference to Strategy-and-Intent goal this effort serves] |

> **Record Type Definitions:**
> - **Maintenance**: Bug fixes, technical debt, minor enhancements — low complexity, contained scope
> - **Incremental Improvement**: Meaningful enhancements to existing functionality — measurable growth within existing markets
> - **Strategic Request**: Customer-driven feature work — validate broad applicability before committing
> - **Growth Initiative**: New products, new user segments, or new markets — expanding beyond current footprint

> **Section guidance by record type:**
>
> | Section | Maintenance | Incremental | Strategic Request | Growth Initiative |
> |---|---|---|---|---|
> | 1. Problem Statement | 1.2 only | All | All | All |
> | 2. Goals & Metrics | Goals + 1 KPI | All | All | All |
> | 3. Personas | Optional | Optional | Required | Required |
> | 4. Cost Estimate | Required | Required | Required | Required |
> | 5. Functional Requirements | Required | Required | Required | Required |
> | 6. User Stories | Optional | Required | Required | Required |
> | 7. Non-Functional Requirements | Affected areas only | Affected areas only | All | All |
> | 8. Design & UX | Optional | Required | Required | Required |
> | 9. Dependencies & Constraints | Required | Required | Required | Required |
> | 10. Open Questions | Required | Required | Required | Required |
> | 11. Test & Validation | Required | Required | Required | Required |
> | 12. Agent Handoff | Optional | Optional | Optional | Optional |
> | 13. Execution Log | Required | Required | Required | Required |
> | 14. Actuals & Retrospective | Required | Required | Required | Required |

---

## 1. Problem Statement

### 1.1 Context
> What environment is this solution going into? Describe the existing system, workflow, or market context.
> Keep to 2–3 paragraphs. Link to supporting research, data, or prior documents.

[Describe the market, customer, or operational context that makes this problem worth solving.]

### 1.2 Problem Definition

**The problem is:** [One clear sentence.]

**We know this is a problem because:** [Evidence — data, customer feedback, support tickets, research.]

**If we don't solve this:** [Consequence of inaction — lost revenue, churn, compliance risk, etc.]

### 1.3 Opportunity
> What is the size and shape of the opportunity if we solve this well?

[Quantify where possible: affected users, revenue potential, cost savings, risk reduction.]

---

## 2. Goals and Success Metrics

### 2.1 Business Goals

- [ ] Goal 1: [e.g., Reduce customer onboarding time by X%]
- [ ] Goal 2: [e.g., Increase feature adoption among existing accounts by X%]
- [ ] Goal 3: [e.g., Achieve SOC2 / HIPAA / ISO compliance requirement]

### 2.2 User Goals

- [ ] User Goal 1: [e.g., Complete the core workflow in under 3 minutes]
- [ ] User Goal 2: [e.g., Understand current status without contacting support]

### 2.3 Success Metrics (KPIs)

| Metric | Baseline | Target | Measurement Method | Lookback Date |
|---|---|---|---|---|
| [e.g., Onboarding completion rate] | X% | Y% | [e.g., Funnel report] | [e.g., 90 days post-launch] |
| [e.g., Support ticket volume] | X/week | Y/week | [e.g., Helpdesk report] | [e.g., 60 days post-launch] |
| [e.g., Time to complete core flow] | Xs | Ys | [e.g., Session recording] | [e.g., 30 days post-launch] |

> **Note:** Lookback Date is when this metric will be evaluated in Section 14 (Actuals and Retrospective). Set it now, not after launch.

### 2.4 Non-Goals

- [e.g., Multi-language support — English only for v1]
- [e.g., Mobile app — web only for v1]
- [e.g., Bulk import — single-record workflow only in this phase]

---

## 3. Users and Personas
> Reference Customer-Personas.md for full persona detail. Summarize here.

### 3.1 Primary User

**Persona**: [Name / Role — link to full persona if available]
**Key Need**: [What they are trying to accomplish]
**Pain Point**: [What currently frustrates or blocks them]

### 3.2 Secondary Users

| Persona | Role | Interaction with this Feature |
|---|---|---|
| [e.g., Compliance Officer] | Internal | Reviews audit logs generated by this flow |
| [e.g., System Administrator] | Internal | Configures settings that affect this feature |

### 3.3 Out-of-Scope Users

- [e.g., End consumers — this is a B2B tool]
- [e.g., External partners — internal users only for v1]

---

## 4. Cost Estimate

> Estimates are completed before build approval. Actuals are recorded in Section 14.
> All estimates reference the Cost-and-Benefit-Framework for methods and labor rates.

### 4.1 Estimate Stage

**Current estimate stage**: [Select one]
- [ ] **ROM (Rough Order of Magnitude)** — scope not yet defined; range estimate only; appropriate for go/no-go scoping conversations
- [ ] **Three-Point** — scope sufficiently defined to decompose; optimistic / most likely / pessimistic inputs provided
- [ ] **Revised** — estimate updated after scope change or new information; original estimate preserved below

> Use ROM when the initiative is in early exploration and scope is not yet defined enough to decompose. Promote to Three-Point before build approval. If scope changes materially during build, create a revised estimate and preserve the original.

---

### 4.2 Estimate Provenance

> Required for every estimate. States what the estimate is based on so decision-makers understand its reliability.

**Provenance type**: [Select one]
- [ ] **Historical analogy** — based on a comparable completed initiative; similarity assessment completed below
- [ ] **Structured decomposition** — built from individual work items estimated independently; three-point applied per item or phase
- [ ] **Expert judgment** — based on the informed assessment of a qualified team member, with reasoning documented
- [ ] **Assumption** — no prior basis; reflects best judgment with no supporting data — flag clearly in review

**Provenance notes:**
[Describe the basis in one or two sentences. e.g., Structured decomposition — broken into 4 phases; three-point applied per phase by the engineering lead and PM independently, then reconciled. No comparable prior initiative exists in the Cost History Log.]

---

### 4.3 Similarity Assessment
> Complete when provenance type is Historical Analogy. Skip if no comparable initiative exists — note that absence explicitly.

**Most comparable prior initiative:** [Initiative name / link to its Product Build Record]

**What makes it comparable:**
- [e.g., Similar integration pattern — same third-party API category]
- [e.g., Similar team composition — same engineering pair]
- [e.g., Similar scope — equivalent number of user-facing surfaces affected]

**Where this initiative differs:**
- [e.g., Higher data volume requirements — may affect infrastructure cost]
- [e.g., New compliance requirement with no prior precedent in our stack]
- [e.g., Less organizational context — team less familiar with this domain]

**Adjustment to reference class estimate:**
[e.g., Reference initiative came in at 280 hours. Differences above suggest a 20–30% premium — adjusted base for three-point most-likely input: 340 hours.]

> If no comparable initiative exists: *"No comparable initiative exists in the Cost History Log. Estimate is based on [provenance type]. Confidence is [Low / Medium]. This record will serve as a reference class anchor for future similar initiatives."*

---

### 4.4 ROM Estimate
> Complete when estimate stage is ROM. Skip if proceeding directly to Three-Point.

**Scope narrative:**
[Describe what is known about the effort at this stage — enough to bound the estimate.]

**ROM Range:**

| Scenario | Effort Range | Cost Range | Basis |
|---|---|---|---|
| Low end | [e.g., 2–4 weeks] | [$X–$Y] | [e.g., If scope is limited to core flow only] |
| High end | [e.g., 8–12 weeks] | [$X–$Y] | [e.g., If full integration and compliance work is required] |

**ROM Confidence:** [Low / Medium]
**Decision this ROM supports:** [e.g., Go/no-go on scoping investment / Board-level budget conversation / Roadmap slot decision]
**Promote to Three-Point by:** YYYY-MM-DD

---

### 4.5 Three-Point Estimate

> Three-point estimation requires three inputs per work item or phase:
> - **O (Optimistic):** Best realistic case — everything goes smoothly, no surprises
> - **M (Most Likely):** Expected case — normal friction, typical unknowns
> - **P (Pessimistic):** Worst realistic case — meaningful complications, not catastrophe
>
> **Weighted estimate = (O + 4M + P) ÷ 6**
> Apply at the phase level for most initiatives. Decompose to work-item level for large or high-risk efforts.

#### Internal Labor

| Phase / Work Item | Role(s) | O (hrs) | M (hrs) | P (hrs) | Weighted Est. (hrs) | Fully-Loaded Cost |
|---|---|---|---|---|---|---|
| [e.g., Discovery and design] | [PM, Designer] | | | | | |
| [e.g., Backend development] | [Senior Eng] | | | | | |
| [e.g., Frontend development] | [Mid Eng] | | | | | |
| [e.g., QA and testing] | [QA, PM] | | | | | |
| [e.g., Deployment and rollout] | [Eng, DevOps] | | | | | |
| [e.g., Ongoing maintenance — annual] | [Eng] | | | | | |
| **Subtotal — Internal Labor** | | | | | | |

> Labor rates from Cost-and-Benefit-Framework Section 2.4.

#### External and Vendor Costs

| Item | Type | O ($) | M ($) | P ($) | Weighted Est. ($) | One-Time or Annual |
|---|---|---|---|---|---|---|
| [e.g., Third-party API license] | SaaS | | | | | Annual |
| [e.g., Implementation services] | Professional services | | | | | One-time |
| [e.g., Infrastructure — incremental] | Infrastructure | | | | | Annual |

#### Uncertainty Buffer

| | Value | Notes |
|---|---|---|
| **Internal labor subtotal** | | |
| **Uncertainty buffer ([X]%)** | | [Applied to internal labor — see Cost-and-Benefit-Framework] |
| **External / vendor costs** | | [Buffer not applied — use three-point range instead] |
| **Opportunity cost** | | [State displaced work or note "not identified"] |
| **Total one-time cost** | | |
| **Total annual ongoing cost** | | |

**Opportunity cost note:**
[e.g., This initiative consumes approximately 320 engineer-hours over 8 weeks, representing roughly 40% of engineering capacity during that period. No specific roadmap initiative has been identified as displaced, but this should be reviewed against the current roadmap before approval.]

---

### 4.6 Estimate Summary

| | Optimistic | Most Likely | Pessimistic | Weighted |
|---|---|---|---|---|
| **Total effort (hrs)** | | | | |
| **Total one-time cost** | | | | |
| **Total annual ongoing cost** | | | | |
| **Estimated timeline** | | | | |

**Estimate confidence:** [High / Medium / Low]
**Primary risk to estimate:** [The single assumption that, if wrong, most changes the estimate.]
**Approved by:** [Name] **Date:** YYYY-MM-DD

---

## 5. Functional Requirements

> Each requirement has a unique ID for traceability through development, testing, and retrospective.
> **Priority**: P0 = Must have (launch blocker) | P1 = Should have | P2 = Nice to have

### 5.1 Feature Area: [e.g., User Authentication]

| ID | Requirement | Priority | Notes |
|---|---|---|---|
| REQ-001 | [e.g., User must be able to log in with email and password] | P0 | |
| REQ-002 | [e.g., System must lock account after 5 failed attempts] | P0 | Security requirement |
| REQ-003 | [e.g., User may optionally enable SSO via corporate IdP] | P1 | Enterprise segment |

### 5.2 Feature Area: [e.g., Report Generation]

| ID | Requirement | Priority | Notes |
|---|---|---|---|
| REQ-010 | [e.g., User must be able to generate a summary report for any date range] | P0 | |
| REQ-011 | [e.g., Reports must generate within 5 seconds for data sets up to 12 months] | P0 | Performance SLA |
| REQ-012 | [e.g., Reports must be exportable as PDF and CSV] | P1 | |

> Add feature area sections as needed.

---

## 6. User Stories

> Format: **As a** [persona], **I want to** [action], **so that** [outcome].

---

### Story 1: [Short descriptive title]

**As a** [persona],
**I want to** [action],
**so that** [outcome].

**Acceptance Criteria:**
- [ ] AC-001: Given [context], when [action], then [expected result]
- [ ] AC-002: Given [context], when [action], then [expected result]
- [ ] AC-003: Given [context], when [action], then [expected result]

**Linked Requirements:** REQ-001, REQ-002
**Priority:** P0

---

### Story 2: [Short descriptive title]

**As a** [persona],
**I want to** [action],
**so that** [outcome].

**Acceptance Criteria:**
- [ ] AC-004: Given [context], when [action], then [expected result]
- [ ] AC-005: Given [context], when [action], then [expected result]

**Linked Requirements:** REQ-010, REQ-011
**Priority:** P0

---

> Add stories as needed.

---

## 7. Non-Functional Requirements

> Maintenance and Incremental: complete only sections affected by this change.

### 7.1 Performance
- [ ] [e.g., Page load time must not exceed 2 seconds on a standard broadband connection]
- [ ] [e.g., API must respond within 500ms at P99 under normal load]
- [ ] [e.g., System must support X concurrent users without degradation]

### 7.2 Security and Compliance
- [ ] [e.g., All sensitive data must be encrypted at rest and in transit]
- [ ] [e.g., Feature must comply with applicable requirements — SOC2 / HIPAA / GDPR / ISO 27001]
- [ ] [e.g., User data handling must comply with applicable privacy regulations]

### 7.3 Accessibility
- [ ] [e.g., All interactive elements must meet WCAG 2.1 AA standards]
- [ ] [e.g., Screen reader compatibility required for all user-facing flows]

### 7.4 Reliability and Uptime
- [ ] [e.g., Target uptime: 99.9%]
- [ ] [e.g., Graceful degradation required if a downstream dependency is unavailable]

---

## 8. Design and UX

### 8.1 Design Assets

| Asset | Link | Status |
|---|---|---|
| Wireframes | [Figma link] | Draft |
| Final Designs | [Figma link] | Pending |
| Design System Reference | [Link] | |

### 8.2 UX Principles for This Feature

- [e.g., Minimize steps — target no more than 3 screens to complete core flow]
- [e.g., Error messages must be plain language, never raw error codes]
- [e.g., All destructive actions require a confirmation step]

---

## 9. Dependencies and Constraints

### 9.1 Dependencies

| Dependency | Type | Owner | Status | Risk if Delayed |
|---|---|---|---|---|
| [e.g., Third-party data provider API] | External vendor | [Name] | Confirmed | High |
| [e.g., Auth service upgrade] | Internal team | [Team] | In progress | Medium |
| [e.g., Legal review] | Internal | Legal | Not started | High |

### 9.2 Constraints

- **Timeline**: [e.g., Must ship before Q3 regulatory deadline]
- **Budget**: [e.g., No new vendor contracts — must use existing stack]
- **Technical**: [e.g., Must integrate with legacy system via existing API — no schema changes]
- **Regulatory**: [e.g., Data must remain within specified geographic boundaries]

---

## 10. Open Questions

| # | Question | Owner | Due Date | Resolution |
|---|---|---|---|---|
| 1 | [e.g., Does this feature apply to all account tiers or only paid plans?] | [Name] | YYYY-MM-DD | |
| 2 | [e.g., What is the fallback behavior if the upstream service is unavailable?] | [Name] | YYYY-MM-DD | |
| 3 | [e.g., Are there regional variations in the workflow that need to be accommodated?] | [Name] | YYYY-MM-DD | |

---

## 11. Test and Validation

> Maps every requirement to a test case. Populate the Results column during QA.
> A Product Build Record is not complete until this section is filled.

### 11.1 Test Cases

| Test ID | Linked Requirement | Linked Story / AC | Test Description | Expected Result | Actual Result | Pass / Fail | Tested By | Date |
|---|---|---|---|---|---|---|---|---|
| TC-001 | REQ-001 | AC-001 | [e.g., Log in with valid credentials] | [e.g., User reaches dashboard] | | | | |
| TC-002 | REQ-002 | AC-002 | [e.g., Enter wrong password 5 times] | [e.g., Account locked, notification sent] | | | | |
| TC-003 | REQ-010 | AC-004 | [e.g., Generate report for 6-month range] | [e.g., Report renders within 5 seconds] | | | | |
| TC-004 | REQ-011 | AC-005 | [e.g., Generate report under concurrent load] | [e.g., Response within SLA at P99] | | | | |

### 11.2 Edge Cases and Negative Tests

| Test ID | Scenario | Expected Behavior | Actual Result | Pass / Fail |
|---|---|---|---|---|
| TC-E001 | [e.g., Submit form with missing required fields] | [e.g., Inline validation shown, submission blocked] | | |
| TC-E002 | [e.g., Submit the same form twice rapidly] | [e.g., Duplicate submission prevented] | | |
| TC-E003 | [e.g., Network drops mid-submission] | [e.g., Graceful failure, no partial record created] | | |

### 11.3 Validation Sign-Off

| Role | Name | Approval | Date |
|---|---|---|---|
| Product | | | |
| Engineering Lead | | | |
| QA Lead | | | |
| Compliance / Legal (if applicable) | | | |

---

## 12. Agent Handoff Instructions

> Written for AI-assisted development teams or autonomous agents.
> Human teams may skip this section — all requirements are fully stated above.

### 12.1 Objective

In plain language, the goal of this build is: [One sentence — what are we building and what should it do?]

### 12.2 Inputs

- [ ] This Product Build Record (requirements and acceptance criteria)
- [ ] Design assets: [Link]
- [ ] API documentation: [Link]
- [ ] Existing codebase context: [Repo / branch / folder]
- [ ] Test data / sandbox credentials: [Link or location]

### 12.3 Explicit Constraints

- **Do not** modify shared services — integrate via API only
- **Do not** deploy to production — deliver to staging environment only
- **Do not** introduce new external dependencies without approval
- **Do not** store sensitive data outside approved, compliant storage
- [Add constraints specific to this initiative]

### 12.4 Ambiguity Protocol

1. Check the Open Questions log (Section 10) first
2. Default to the most conservative interpretation that satisfies the requirement
3. Flag the ambiguity as a comment in the PR — do not silently choose
4. Do not block on minor unknowns — implement with a clearly marked `TODO`
5. Log any new questions discovered during development in Section 10

### 12.5 Definition of Done

- [ ] All P0 requirements in Section 5 are implemented
- [ ] All P0 acceptance criteria in Section 6 are passing
- [ ] All test cases in Section 11.1 pass
- [ ] No regressions in [existing feature / test suite]
- [ ] Code is documented and follows [style guide / conventions link]
- [ ] Test results are filled into Section 11
- [ ] Any deviations from requirements are documented with rationale
- [ ] PR submitted to [branch] with staging deployment link confirmed

---

## 13. Execution Log

> A running record of anything that happens during the build that affects scope, cost, timeline, or outcome. Updated in real time — not reconstructed after the fact.
>
> **Why this exists:** Mid-build decisions are where estimates diverge from actuals. Without a record of what changed and why, the retrospective cannot produce useful learning, and future estimates cannot account for the patterns that actually drive variance. Brief entries are better than no entries.

| Date | Type | Description | Impact | Decision / Resolution | Owner |
|---|---|---|---|---|---|
| YYYY-MM-DD | [Scope change / Blocker / Decision / Discovery / Team change / External dependency] | [What happened] | [Cost / Timeline / Quality — brief impact statement] | [What was decided and by whom] | [Name] |
| | | | | | |
| | | | | | |

**Execution log entry types:**
- **Scope change** — requirements added, removed, or modified after approval
- **Blocker** — something that stopped or significantly slowed progress
- **Decision** — a meaningful choice made during build that wasn't covered by the requirements
- **Discovery** — something learned during build that was not known at estimate time
- **Team change** — a change in who is working on the initiative
- **External dependency** — a delay or change caused by something outside the team's control

---

## 14. Actuals and Retrospective

> Completed after launch and at defined lookback intervals. This section closes the loop between estimate and reality — and generates the reference class data that improves future estimates.
>
> **The retrospective is not optional.** An organization that estimates but never compares estimates to actuals is not learning. This section is what makes the framework self-improving over time.

### 14.1 Cost Actuals

| Cost Item | Estimated (Weighted) | Actual | Variance | Variance % | Notes |
|---|---|---|---|---|---|
| Internal labor — build | | | | | |
| Internal labor — maintenance (first year) | | | | | |
| External / vendor | | | | | |
| Infrastructure | | | | | |
| **Total** | | | | | |

**Timeline actuals:**

| | Estimated | Actual | Variance |
|---|---|---|---|
| Build start date | | | |
| Launch date | | | |
| Total elapsed calendar time | | | |

---

### 14.2 Variance Analysis

> Required when any cost or timeline variance exceeds 20%. Brief is fine — the goal is a usable signal for future estimates, not a post-mortem report.

**Primary driver of cost variance:**
[What was the single biggest reason actual cost differed from estimate? e.g., Discovery during build revealed an undocumented dependency in the legacy auth system — added 40 hours of unplanned engineering work.]

**Primary driver of timeline variance:**
[e.g., External vendor API documentation was incomplete — 2-week delay waiting for clarification and updated specs.]

**Was the estimate provenance appropriate for this initiative?**
[e.g., Structured decomposition was appropriate. The variance was not a method problem — it was a discovery problem. The estimate would have been more accurate with a spike to investigate the legacy system before committing.]

**What would have improved this estimate?**
[e.g., A 1–2 day technical discovery sprint before three-point estimation. The unknowns in the legacy system were knowable — we chose not to investigate before estimating.]

---

### 14.3 Benefit Realization

> Measured at the lookback dates defined in Section 2.3. Copy the metrics table from Section 2.3 and fill in actuals.

**Lookback date:** YYYY-MM-DD  **Days post-launch:** [X]

| Metric | Baseline | Target | Actual | vs. Target | Notes |
|---|---|---|---|---|---|
| [From Section 2.3] | | | | [On track / Below / Exceeded] | |
| | | | | | |

**Benefit realization summary:**
[2–3 sentences on whether the initiative delivered its intended benefits. Honest assessment — not a press release. e.g., Onboarding completion rate improved from 61% to 74% against a target of 75% — essentially on target. Support ticket volume for this workflow declined 40%, exceeding the 25% target. Time-to-complete did not improve materially — the bottleneck turned out to be downstream of the flow we modified.]

**Will this initiative require a follow-on effort?**
- [ ] Yes — [describe what is needed and why]
- [ ] No
- [ ] Unknown — reassess at next lookback

---

### 14.4 Reference Class Record

> This section is the initiative's contribution to the organization's cost history. Future initiatives will reference it via the Similarity Assessment in Section 4.3.

**Initiative summary for reference class use:**

| Field | Value |
|---|---|
| **Initiative type** | [e.g., New integration — third-party API / UI feature — new surface / Backend refactor / Compliance work] |
| **Team composition** | [e.g., 1 senior eng, 1 mid eng, 0.5 PM, 0.25 designer] |
| **Total actual effort (hours)** | |
| **Total actual cost** | |
| **Calendar duration** | |
| **Estimate provenance used** | [Historical analogy / Structured decomposition / Expert judgment / Assumption] |
| **Estimate accuracy** | [e.g., Came in at 112% of weighted estimate — 12% over] |
| **Primary variance driver** | [One sentence — the most useful thing to know for a future similar estimate] |
| **Comparable to** | [Describe in plain language what future initiative would be similar enough to use this as a reference: e.g., Any initiative involving integration with a third-party API where the vendor's documentation cannot be validated before estimation] |

---

### 14.5 Retrospective Notes

> Anything worth preserving for the organization or for future teams working in this area. Feed significant learnings into Institutional-Knowledge.md.

**What worked well:**
- [e.g., Breaking the build into two phases with a checkpoint allowed us to course-correct after the legacy system discovery]
- [e.g., The three-point estimate surfaced the pessimistic case early — leadership was not surprised by the overrun]

**What didn't work:**
- [e.g., Open questions were not resolved before build began — two of them caused scope changes mid-build]
- [e.g., The execution log was not maintained in real time — reconstructed from memory, which reduced its accuracy]

**What to do differently next time:**
- [e.g., Require a technical discovery spike for any initiative touching systems with undocumented legacy behavior]
- [e.g., Assign explicit execution log ownership at kickoff — not a shared responsibility]

**Logged to Institutional-Knowledge.md:** [ ] Yes — [link or reference] [ ] Not yet

---

*Product Build Record — [Initiative Name] — Status: [Current Status]*
