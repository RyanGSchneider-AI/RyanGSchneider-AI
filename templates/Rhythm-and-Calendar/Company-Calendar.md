# Company Calendar

> A living record of the recurring cycles, events, and rhythms that shape how the organization's year runs — and the context layer for sequencing and timing any initiative. This document captures both the pattern (what happens in which quarters, where pressure concentrates, where capacity exists) and the specific dates for known events in the current and upcoming year.
>
> **This is not a scheduling tool.** Specific dates for individual tasks and project milestones live in project management systems. This document captures the organizational cadence — the shape of the year that any Business Case or Product Build Record should be evaluated against when timing is being considered.
>
> **Consult this document when:** an initiative is being timed, a launch window is being selected, a resource commitment is being made, or a campaign is being planned. The calendar does not block decisions — it makes the timing context visible so decisions can be made consciously.

---

## Document Control

| Field | Value |
|---|---|
| **Last Updated** | YYYY-MM-DD |
| **Current Fiscal Year** | [e.g., FY2026 — Nov 1, 2025 through Oct 31, 2026] |
| **Updated By** | |
| **Review Cadence** | Annually before fiscal year start; updated as specific dates are confirmed |
| **Primary Owner** | [e.g., COO / Chief of Staff / Operations] |

> **Connected artifacts:**
> - **Business-Case** — timing and resource availability should be evaluated against the Annual Calendar View (Section 7) before approval
> - **Product-Build-Record** — launch windows, freeze periods, and organizational capacity should be noted in Dependencies and Constraints
> - **Organizational-Risk-and-Compliance** — regulatory filing deadlines and audit windows here should match the compliance obligations register there
> - **Strategy-and-Intent** — major strategic milestones and initiative timelines should be consistent with the capacity picture here
> - **People-and-Talent-Strategy** — hiring cycles and performance review windows affect capacity during key calendar periods

---

## 1. How to Use This Document

### 1.1 For Initiative Timing

When a Business Case or Product Build Record is being developed, the following questions should be answered by consulting this document:

| Question | Where to Look |
|---|---|
| Is the proposed launch window during a high-pressure period for any team involved? | Section 7 — Annual Calendar View |
| Does the initiative require CS, Sales, or Marketing capacity during a period when those teams are heavily committed? | Sections 4 and 5 |
| Does the proposed timeline overlap with a product freeze, a major release, or a platform migration? | Section 3 |
| Does the initiative need to be live before a key industry event or customer renewal window? | Sections 2 and 4 |
| Are there regulatory filing deadlines or audit windows that constrain the timeline? | Section 2 and Organizational-Risk-and-Compliance |
| Is the initiative being approved during a budget cycle that might affect funding availability? | Section 2 |

The goal is not to find a reason to delay — it is to ensure the timing decision is made with full awareness of the organizational context.

### 1.2 Calendar Grain

Each section captures two levels:

**The cycle** — what happens, in which part of the year, and why it matters. This is stable year over year with minor variation.

**The specific dates** — confirmed dates for the current fiscal year. Updated as dates are known. If a date is not yet confirmed, note it as TBD with the expected window.

---

## 2. Fiscal and Financial Calendar

> The financial boundaries and internal reporting rhythms that govern how the organization plans, allocates resources, and measures performance. These cycles affect budget availability, approval authority, and the organizational attention available for new initiatives.

### 2.1 Fiscal Year Structure

| Field | Value |
|---|---|
| **Fiscal year start** | [e.g., November 1] |
| **Fiscal year end** | [e.g., October 31] |
| **Fiscal quarters** | [e.g., Q1: Nov–Jan / Q2: Feb–Apr / Q3: May–Jul / Q4: Aug–Oct] |
| **Budget cycle** | [e.g., Budget planning begins in September; approved by board in October for following fiscal year] |
| **Financial close** | [e.g., Monthly close by the 10th of the following month; annual close by November 30] |

**Why this matters for initiative timing:**
[e.g., Initiatives requiring budget approval above $X must be included in the annual budget cycle or require a mid-year budget amendment — which requires board approval and adds 4–6 weeks to the timeline. Initiatives approved in Q4 frequently slip to Q1 due to budget transition and team reset.]

### 2.2 Financial Calendar — Current Fiscal Year

| Event | Type | Date / Window | Owner | Notes |
|---|---|---|---|---|
| [e.g., FY budget planning begins] | Internal | [e.g., Sep 1, YYYY] | [CFO] | [e.g., Department heads submit requests by Sep 15] |
| [e.g., Board budget approval] | Internal | [e.g., Oct board meeting — Oct 22, YYYY] | [CFO / CEO] | |
| [e.g., FY start] | Internal | [e.g., Nov 1, YYYY] | | |
| [e.g., Q1 financial close] | Internal | [e.g., Feb 10, YYYY] | [Finance] | [e.g., All Q1 invoices must be submitted by Feb 5] |
| [e.g., Q2 financial close] | Internal | [e.g., May 10, YYYY] | [Finance] | |
| [e.g., Q3 financial close] | Internal | [e.g., Aug 10, YYYY] | [Finance] | |
| [e.g., Annual audit preparation begins] | Internal | [e.g., Sep 1, YYYY] | [Finance / Legal] | [e.g., Finance team capacity significantly reduced during this period] |
| [e.g., Annual audit] | External | [e.g., Oct 1–15, YYYY] | [Finance / Legal] | [e.g., External auditors on-site — Finance unavailable for other initiatives] |
| [e.g., FY end] | Internal | [e.g., Oct 31, YYYY] | | |
| [e.g., Annual tax filing deadline] | Regulatory | [e.g., TBD] | [Finance / External counsel] | |

### 2.3 Board and Investor Reporting Cadence

| Meeting / Report | Frequency | Typical Timing | Owner | Notes |
|---|---|---|---|---|
| [e.g., Board meeting] | [Quarterly] | [e.g., Third week of Feb, May, Aug, Oct] | [CEO / CFO] | [e.g., Board materials due 1 week prior — significant leadership bandwidth consumed] |
| [e.g., Investor update] | [Monthly] | [e.g., First week of each month] | [CEO / CFO] | [e.g., Requires metrics package from Finance] |
| [e.g., Annual investor meeting] | [Annual] | [e.g., November — specific date TBD] | [CEO] | |

**Capacity note:**
[e.g., Board meeting preparation consumes significant CEO, CFO, and leadership bandwidth in the week prior. Avoid scheduling major initiative reviews, approvals, or launches in the same window.]

---

## 3. Product and Release Calendar

> The product team's release philosophy, planned release windows, and periods where the codebase or infrastructure is frozen or under heightened stability requirements. Initiative launch timing should be evaluated against these windows.

### 3.1 Release Cadence Philosophy

**Release model:** [e.g., Continuous delivery with monthly milestone releases / Quarterly major releases / Event-driven releases tied to market moments]

**Release cadence:** [e.g., Minor releases: bi-weekly / Major releases: quarterly / Hotfixes: as needed with expedited review]

**Typical release window:** [e.g., Releases deploy Tuesday–Thursday; no Friday or weekend deploys except for critical hotfixes]

### 3.2 Release Freeze Periods

> Periods when code deployments are restricted or prohibited — typically around high-stakes external events, financial close, or peak usage periods.

| Period | Dates | Scope | Reason | Exceptions |
|---|---|---|---|---|
| [e.g., Holiday freeze] | [e.g., Dec 20 – Jan 3, YYYY] | [e.g., No production deploys] | [e.g., Reduced on-call capacity; high customer usage period] | [e.g., Critical security patches only — requires VP Engineering approval] |
| [e.g., Conference freeze] | [e.g., 1 week prior to and during [Conference name]] | [e.g., No major feature releases] | [e.g., Stability during high-visibility period; Sales and CS focused on event] | [e.g., Hotfixes only] |
| [e.g., Annual audit window] | [e.g., Oct 1–15, YYYY] | [e.g., No infrastructure changes] | [e.g., Auditors require stable environment for evidence collection] | [e.g., None — no exceptions during audit] |

### 3.3 Planned Release Windows — Current Fiscal Year

| Release | Target Window | Type | Key Features / Themes | Status | Notes |
|---|---|---|---|---|---|
| [e.g., v2.4] | [e.g., Q1 — February YYYY] | [e.g., Major] | [e.g., New reporting module, API v2] | [Planned / In build / Shipped] | |
| [e.g., v2.5] | [e.g., Q2 — May YYYY] | [e.g., Major] | [e.g., Mobile experience, partner integrations] | [Planned] | [e.g., Timed to precede [Industry conference]] |
| [e.g., v2.6] | [e.g., Q3 — August YYYY] | [e.g., Major] | [e.g., TBD — roadmap planning Q2] | [TBD] | |
| [e.g., v3.0] | [e.g., Q4 — October YYYY] | [e.g., Major] | [e.g., Platform redesign — strategic release] | [Planning] | [e.g., Target: ready for FY kickoff and renewal season] |

### 3.4 Infrastructure and Platform Events

| Event | Date / Window | Impact | Owner | Notes |
|---|---|---|---|---|
| [e.g., Cloud provider maintenance window] | [e.g., First Sunday of each month, 2–4am] | [e.g., Potential 30-min service interruption] | [Engineering] | [e.g., Customers notified 72 hours in advance] |
| [e.g., Database migration] | [e.g., Q2 YYYY — specific date TBD] | [e.g., Read-only window estimated 4 hours] | [Engineering] | [e.g., Will require release freeze for 2 weeks surrounding migration] |

---

## 4. Industry and Market Calendar

> Recurring external events that shape the market environment — conferences, trade shows, analyst cycles, and customer renewal patterns. These events are not controlled by the organization but create windows of opportunity or pressure that product, sales, and marketing activities should be planned around.

### 4.1 Industry Events

| Event | Type | Typical Timing | YYYY Dates | Location | Organizational Role | Owner | Notes |
|---|---|---|---|---|---|---|---|
| [e.g., Industry conference name] | [Conference / Trade show / Summit] | [e.g., Annually — February] | [e.g., Feb 18–21, YYYY] | [e.g., Las Vegas, NV] | [e.g., Exhibiting — 20x20 booth / Speaking — CEO keynote / Attending only] | [Name] | [e.g., Largest industry gathering — highest lead generation event of year] |
| [e.g., Regional conference name] | [Conference] | [e.g., Annually — May] | [e.g., May 7–9, YYYY] | [e.g., Chicago, IL] | [e.g., Sponsoring — silver level] | [Name] | [e.g., Strong presence in Midwest customer base] |
| [e.g., Partner summit — [Partner name]] | [Partner event] | [e.g., Annually — September] | [e.g., TBD — typically mid-September] | [e.g., TBD] | [e.g., Attending — sales and partnerships team] | [Name] | |
| [e.g., Analyst briefing cycle — [Firm name]] | [Analyst] | [e.g., Semi-annual] | [e.g., March and September] | [e.g., Virtual] | [e.g., Briefing and inquiry sessions] | [Name] | [e.g., Magic Quadrant / Wave evaluation cycle — critical for enterprise sales] |
| [e.g., Customer advisory board] | [Customer event] | [e.g., Annually — Q3] | [e.g., Aug YYYY — date TBD] | [e.g., Company HQ / Virtual] | [e.g., Hosting — 12–15 strategic customers] | [Name] | [e.g., Product roadmap input and reference customer engagement] |

**Event calendar implications:**
[e.g., The February conference is the single highest-priority external event of the year. Product releases intended to be demonstrated at the conference must be stable and in production by February 1 — no exceptions. Sales team is fully committed the week before and week of the conference. CS team coverage plan required for that period.]

### 4.2 Customer Renewal Patterns

> When customers tend to renew — by segment, contract anniversary, or fiscal year alignment. Renewal clusters create predictable CS and Sales pressure that affects capacity for other work.

| Segment | Renewal Pattern | Peak Renewal Window | Capacity Impact | Notes |
|---|---|---|---|---|
| [e.g., Enterprise] | [e.g., Annual — aligned to customer fiscal year] | [e.g., January and July] | [e.g., CS team at 80%+ capacity during peak renewal months] | [e.g., Enterprise contracts average 12 months; majority signed in Q1 and Q3] |
| [e.g., Mid-market] | [e.g., Annual — contract anniversary] | [e.g., Spread throughout year — slight Q2 concentration] | [e.g., Moderate — no single peak] | |
| [e.g., SMB] | [e.g., Monthly] | [e.g., Ongoing] | [e.g., Low per-renewal; high volume] | [e.g., Largely automated — minimal CS touch] |

### 4.3 Regulatory and External Filing Windows

> Regulatory deadlines that appear on the market calendar — not organization-specific obligations (those live in Organizational-Risk-and-Compliance) but industry-wide filing windows and standards update cycles that affect the organization's planning.

| Filing / Event | Governing Body | Typical Window | YYYY Date | Owner | Notes |
|---|---|---|---|---|---|
| [e.g., Annual license renewal — [State]] | [State regulator] | [e.g., Annually — March] | [e.g., Mar 31, YYYY] | [Legal] | [e.g., 90-day application window opens January 1] |
| [e.g., Standards update — [Standards body]] | [Standards body] | [e.g., Annual publication — Q4] | [e.g., TBD] | [Engineering / Compliance] | [e.g., Review required to assess impact on certification scope] |

---

## 5. Sales and Marketing Calendar

> Recurring sales and marketing cycles — campaign rhythms, pipeline review cadences, demand generation programs, and partner engagement patterns. These affect team capacity and create windows where new initiatives land well or poorly.

### 5.1 Sales Cycles and Rhythms

| Rhythm | Frequency | Typical Timing | Owner | Notes |
|---|---|---|---|---|
| [e.g., Sales kickoff] | [Annual] | [e.g., First week of fiscal year — November] | [Sales leadership] | [e.g., Full sales team focused on SKO for 3–5 days — no external meetings] |
| [e.g., Quarterly business review — internal] | [Quarterly] | [e.g., First two weeks of each quarter] | [Sales leadership] | [e.g., Pipeline review and forecast — leadership bandwidth consumed] |
| [e.g., Pipeline review — weekly] | [Weekly] | [e.g., Mondays] | [Sales leadership] | |
| [e.g., End of quarter push] | [Quarterly] | [e.g., Final 2 weeks of each quarter] | [Sales team] | [e.g., Sales team fully focused on closing — avoid new internal asks during this window] |
| [e.g., Commission and compensation review] | [Annual] | [e.g., Q4 — ahead of fiscal year] | [Sales leadership / Finance] | |

### 5.2 Marketing Campaign Calendar

| Campaign / Program | Type | Frequency | Typical Window | YYYY Dates | Owner | Notes |
|---|---|---|---|---|---|---|
| [e.g., Annual product launch campaign] | [Product marketing] | [Annual] | [e.g., Aligned to major release — Q2] | [e.g., May YYYY] | [Marketing] | [e.g., Requires product stable in production 3 weeks prior to campaign launch] |
| [e.g., Conference lead nurture sequence] | [Demand generation] | [Annual] | [e.g., 6 weeks post-conference] | [e.g., Mar–Apr YYYY] | [Marketing] | [e.g., Follows February conference] |
| [e.g., Customer case study program] | [Content] | [Quarterly] | [e.g., One published per quarter] | [e.g., Q1: Feb / Q2: May / Q3: Aug / Q4: Nov] | [Marketing / CS] | [e.g., Requires reference customer coordination — flag in Reference Customers and Champions] |
| [e.g., End-of-year promotion] | [Demand generation] | [Annual] | [e.g., November–December] | [e.g., Nov 1 – Dec 20, YYYY] | [Marketing / Sales] | [e.g., Targets prospects who have budget to spend before calendar year end] |

### 5.3 Partner and Channel Calendar

| Event / Activity | Frequency | Typical Window | YYYY Dates | Owner | Notes |
|---|---|---|---|---|---|
| [e.g., Partner program review] | [Annual] | [e.g., Q4] | [e.g., October YYYY] | [Partnerships] | [e.g., Annual review of partner tier, compensation, and co-marketing commitments] |
| [e.g., Partner enablement training] | [Semi-annual] | [e.g., Q1 and Q3] | [e.g., February and August YYYY] | [Partnerships / Sales] | [e.g., New product features and updated sales materials] |
| [e.g., Co-marketing campaigns] | [Quarterly] | [e.g., One per quarter — coordinated with major partners] | [TBD] | [Marketing / Partnerships] | |

---

## 6. Organizational Calendar

> Internal recurring events that shape team capacity and organizational rhythm — planning cycles, all-hands meetings, performance reviews, and team offsites. These affect the availability of leadership and team capacity for initiative work.

### 6.1 Planning Cycles

| Planning Event | Frequency | Typical Window | YYYY Dates | Owner | Notes |
|---|---|---|---|---|---|
| [e.g., Annual strategic planning] | [Annual] | [e.g., Q4 — 6 weeks before fiscal year end] | [e.g., Sep–Oct YYYY] | [CEO / Leadership team] | [e.g., Leadership team at significantly reduced operational capacity during planning — defer major approvals] |
| [e.g., Quarterly OKR / goal review] | [Quarterly] | [e.g., Final week of each quarter] | [e.g., Jan, Apr, Jul, Oct] | [Leadership team] | |
| [e.g., Product roadmap planning] | [Semi-annual] | [e.g., Q2 and Q4] | [e.g., May and November YYYY] | [Product leadership] | [e.g., Major roadmap inputs due 2 weeks prior from all departments] |
| [e.g., Annual budget planning] | [Annual] | [e.g., Q4] | [e.g., Sep 1 – Oct 22, YYYY] | [CFO / Department heads] | [e.g., See Section 2 for detail] |

### 6.2 All-Hands and Company Events

| Event | Frequency | Typical Timing | YYYY Dates | Owner | Notes |
|---|---|---|---|---|---|
| [e.g., All-hands meeting] | [Monthly] | [e.g., Last Thursday of each month] | [e.g., Recurring] | [CEO / Chief of Staff] | [e.g., Company-wide — no competing meetings scheduled] |
| [e.g., Annual company offsite] | [Annual] | [e.g., Q3 — July or August] | [e.g., Aug 12–14, YYYY] | [People / CEO] | [e.g., Full company — 3 days; engineering sprint planning deferred by 1 week] |
| [e.g., Department offsites] | [Annual] | [e.g., Staggered through Q2 and Q3] | [e.g., TBD by department] | [Department heads] | |

### 6.3 People and HR Calendar

| Event | Frequency | Typical Window | YYYY Dates | Owner | Notes |
|---|---|---|---|---|---|
| [e.g., Performance review cycle] | [Annual] | [e.g., Q4 — ahead of fiscal year] | [e.g., Oct YYYY] | [People / Managers] | [e.g., Manager bandwidth significantly reduced during review period — avoid major project asks] |
| [e.g., Compensation review] | [Annual] | [e.g., Tied to performance review — Q4] | [e.g., Nov YYYY] | [People / Finance] | |
| [e.g., Benefits open enrollment] | [Annual] | [e.g., October] | [e.g., Oct 1–15, YYYY] | [People] | |
| [e.g., Summer hiring freeze] | [Annual — if applicable] | [e.g., July–August] | [e.g., Jul 1 – Aug 15, YYYY] | [People] | [e.g., Reduced recruiting capacity during summer — plan hires for Q2 or Q4 if possible] |

---

## 7. Annual Calendar View

> A consolidated quarter-by-quarter view of the full year — the single reference for evaluating initiative timing. Updated each fiscal year before the year begins; updated in-year as specific dates are confirmed.

### FY[XXXX] — At a Glance

| | Q1 [Months] | Q2 [Months] | Q3 [Months] | Q4 [Months] |
|---|---|---|---|---|
| **Financial** | [e.g., Q1 close / Board meeting] | [e.g., Q2 close / Board meeting] | [e.g., Q3 close / Board meeting] | [e.g., Audit / Budget planning / FY end] |
| **Product** | [e.g., v2.4 release / Conference freeze] | [e.g., v2.5 release] | [e.g., v2.6 release / Company offsite] | [e.g., v3.0 release / Holiday freeze] |
| **Industry events** | [e.g., [Conference name] — Feb] | [e.g., [Conference name] — May] | [e.g., Customer advisory board] | [e.g., Partner summit] |
| **Sales and marketing** | [e.g., SKO / End-of-quarter push / Lead nurture] | [e.g., Product launch campaign / End-of-quarter push] | [e.g., End-of-quarter push] | [e.g., End-of-year promotion / Partner review] |
| **Renewals** | [e.g., Enterprise renewal peak] | | [e.g., Enterprise renewal peak] | |
| **Organizational** | [e.g., OKR review / Roadmap planning] | [e.g., OKR review / Department offsites] | [e.g., OKR review / Company offsite / Performance reviews begin] | [e.g., Strategic planning / Budget / Performance reviews / Compensation] |
| **Compliance** | [e.g., License renewal deadline — Mar] | | [e.g., SOC 2 audit preparation begins] | [e.g., SOC 2 audit / Annual filing] |
| **Capacity notes** | [e.g., CS at peak renewal capacity Jan; Sales fully committed Feb conference week] | [e.g., End-of-quarter push last 2 weeks] | [e.g., Full company offsite Aug — plan around it] | [e.g., Leadership at reduced capacity Sep–Oct during planning and audit] |

### Capacity Pressure Summary

> A plain-language summary of the periods in the year where organizational capacity is most constrained. Consult before committing to a launch window or major resource ask.

| Period | Teams Affected | Pressure Level | Notes |
|---|---|---|---|
| [e.g., February — conference week] | [Sales, CS, Marketing, Executive] | [High] | [e.g., Entire go-to-market team at conference; no internal capacity for launches or major reviews] |
| [e.g., January] | [CS] | [High] | [e.g., Enterprise renewal peak — CS at capacity] |
| [e.g., End of each quarter — final 2 weeks] | [Sales] | [Medium] | [e.g., Sales fully focused on closing; avoid new internal asks] |
| [e.g., September–October] | [Leadership, Finance, Legal] | [High] | [e.g., Strategic planning + budget + audit simultaneously — leadership bandwidth at annual low] |
| [e.g., August] | [All] | [Medium] | [e.g., Company offsite + summer PTO — reduced capacity across all teams] |

---

## 8. Calendar Governance

> How this document is maintained and who is responsible for keeping it current.

### 8.1 Annual Update Process

| Step | Timing | Owner | Action |
|---|---|---|---|
| Draft next fiscal year calendar | [e.g., 8 weeks before fiscal year start] | [Primary owner] | Carry forward recurring cycles; clear specific dates from prior year; add known dates for coming year |
| Department input collection | [e.g., 6 weeks before fiscal year start] | [Primary owner] | Each department head confirms their key dates, events, and capacity constraints |
| Leadership review | [e.g., 4 weeks before fiscal year start] | [Leadership team] | Review consolidated calendar for conflicts and capacity gaps |
| Publish and communicate | [e.g., Fiscal year start] | [Primary owner] | Distribute to all teams; link from intranet or team wiki |

### 8.2 In-Year Updates

This document should be updated when:
- A specific event date is confirmed that was previously TBD
- A new industry event, partner event, or organizational event is added to the year
- A planned release window shifts materially
- A freeze period is added or extended
- A significant capacity constraint emerges that was not anticipated at year start

**In-year update owner:** [Name / Role]
**How to flag a needed update:** [e.g., Slack channel / Email / Direct to owner]

### 8.3 Open Questions

| # | Question | Owner | Due Date | Resolution |
|---|---|---|---|---|
| 1 | [e.g., Are there industry events we should be tracking that are not currently on the calendar?] | [Name] | YYYY-MM-DD | |
| 2 | [e.g., Are all compliance deadlines from Organizational-Risk-and-Compliance reflected here?] | [Name] | YYYY-MM-DD | |
| 3 | [e.g., Has the capacity pressure summary been reviewed by each department head for accuracy?] | [Name] | YYYY-MM-DD | |
