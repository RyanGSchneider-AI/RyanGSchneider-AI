# Cost and Benefit Framework

> The organization's standard method for estimating the cost and benefit of any initiative — from a one-person task to a multi-year program. Every Business Case references this document. Its purpose is not to make estimation easier; it is to make estimates comparable across initiatives, honest about their assumptions, and useful for prioritization decisions.
>
> **Consistency is the goal, not precision.** A rough estimate built on agreed-upon methods is more useful than a precise estimate built on undisclosed assumptions. When two business cases use the same framework, a decision-maker can compare them. When they don't, comparison is guesswork.

---

## Document Control

| Field | Value |
|---|---|
| **Last Updated** | YYYY-MM-DD |
| **Updated By** | |
| **Review Cadence** | Annually, or when cost structures or business model change materially |
| **Primary Owner** | [e.g., Finance / Head of Product / COO] |

> **Connected artifacts:** Every Business Case references this framework for cost estimation and benefit classification. Funding-and-Business-Model provides the organizational driver context that determines which benefit types carry the most weight in prioritization. Metrics-Framework defines the baseline measurements that make benefit claims defensible.

---

## Part 1: Benefit Framework

> Benefits are the positive outcomes an initiative is expected to produce. This framework recognizes three benefit types — Revenue Growth, Cost Reduction, and Risk Reduction — plus Acceleration, a cross-cutting dimension that applies when an initiative pulls value forward in time rather than (or in addition to) increasing its total amount.
>
> **One initiative may produce benefits across multiple types.** When it does, estimate each type separately and label them clearly. Combining benefit types without labeling obscures the reasoning and makes the estimate impossible to challenge or validate.

---

### Benefit Type 1: Revenue Growth

> An initiative produces a revenue growth benefit when it is expected to increase the total revenue the organization generates — by increasing demand, expanding the customer base, or increasing the price the market will bear.

#### 1.1 Sub-types

Use the sub-type that most accurately describes the mechanism. If multiple apply, estimate each separately.

---

**Sub-type A: Increased Demand from Existing Markets**

The initiative makes the product more valuable, more usable, or more retainable for customers the organization already serves — resulting in more revenue from the existing base.

*Mechanisms:*
- Higher renewal rates or reduced churn (retention improvement)
- Increased usage or consumption within existing accounts (expansion revenue)
- Faster adoption of existing features, reducing time between purchase and realized value
- Improved satisfaction that converts to referrals and organic pipeline

*Estimation approach:*
Anchor to a baseline metric — current churn rate, current expansion rate, current NPS — and estimate the change the initiative is expected to produce. Translate that change into revenue impact using the organization's standard revenue math (see Section 1.4).

*Evidence standard:*
- Customer research identifying specific gaps that drive churn or limit expansion
- Support or CS data showing recurring issues the initiative would resolve
- Win/loss data showing retention losses attributable to the gap this initiative closes

---

**Sub-type B: New Customer Growth — Current Market**

The initiative is expected to grow the number of customers the organization serves within its current target market — by improving conversion, shortening the sales cycle, or reaching a segment of the existing market that was previously inaccessible.

*Mechanisms:*
- Closing a capability gap that appears in sales losses or late-stage deal failures
- Reducing onboarding friction that causes prospects to disengage after signing
- Enabling a new pricing tier or packaging option that opens a segment within the current ICP
- Improving the trial or evaluation experience in a product-led motion

*Estimation approach:*
Anchor to pipeline data — how many deals were lost or delayed due to the gap this initiative closes? What is the average deal value? Apply a conservative conversion estimate to the addressable opportunity.

*Evidence standard:*
- Win/loss analysis showing this gap as a recurring loss reason
- Sales team input on deals where this capability was a stated requirement
- Competitive intelligence showing this gap as a differentiator for specific competitors

---

**Sub-type C: New Customer Growth — Adjacent Markets**

The initiative is expected to extend the organization's reach into market segments it does not currently serve — new verticals, new geographies, new buyer personas, or new use cases that require meaningful product or go-to-market adaptation.

*Mechanisms:*
- A new capability that makes the solution viable for a segment with different requirements
- A compliance certification or integration that unlocks a regulated or gated market
- A packaging or pricing change that makes the product viable for a previously out-of-reach segment
- A channel partnership that provides distribution into a new geography or vertical

*Estimation approach:*
Adjacent market estimates carry the highest uncertainty of any revenue claim. Require a market size estimate, a realistic penetration assumption with explicit basis, and a timeline. Flag this as a Growth Initiative in the Business Case — it requires more scrutiny than a retention or conversion improvement claim.

*Evidence standard:*
- Market research or customer interviews confirming demand in the adjacent segment
- Competitive intelligence showing the segment is served by weaker alternatives
- Pilot customer or letter of intent from a representative account in the target segment

---

**Sub-type D: Increased Price**

The initiative is expected to increase the price the market will bear — by adding value that supports a higher price point, enabling a premium tier, or reducing price sensitivity through stronger differentiation.

*Mechanisms:*
- A capability materially more valuable than anything currently in the product — supports a new tier or price increase
- A feature or outcome that shifts the product from a cost center to a revenue center in the customer's mind
- Improved positioning or proof of value that reduces discounting pressure in sales

*Estimation approach:*
Price benefit estimates are among the hardest to defend and should be held to a high evidence standard. Anchor to customer willingness-to-pay research, comparable market pricing, or explicit customer feedback that current pricing is below perceived value.

*Evidence standard:*
- Willingness-to-pay research or conjoint analysis
- Competitive pricing benchmarks showing the organization is underpriced relative to value delivered
- Customer feedback — unsolicited, not prompted — indicating the product is priced below perceived value

---

**Acceleration (Cross-Cutting Dimension)**

Acceleration is not a separate benefit type — it is a dimension that applies to revenue growth claims when the initiative pulls revenue forward in time rather than (or in addition to) increasing its total amount.

An initiative accelerates revenue when it:
- Shortens the sales cycle — deals that took 90 days now close in 60
- Reduces time-to-value — customers realize outcomes sooner, reducing early churn
- Compresses onboarding — revenue that was 60 days away becomes 30 days away

*Why this matters:*
Revenue received sooner is worth more than revenue received later. An initiative that pulls $1M of revenue forward by 6 months has real financial value that a simple revenue growth framing will miss. Express the benefit as "[$X] of revenue accelerated by [Y months]" and note it separately from incremental revenue claims.

*Estimation approach:*
Anchor to current cycle time data and estimate the reduction. Apply the organization's standard revenue math to the accelerated volume. If the organization uses NPV analysis, apply it here.

---

#### 1.2 Revenue Growth Estimation Table

> Complete one row per sub-type that applies. Leave inapplicable sub-types blank.

| Sub-type | Mechanism | Baseline Metric | Estimated Change | Revenue Impact | Time Horizon | Confidence | Basis for Estimate |
|---|---|---|---|---|---|---|---|
| Increased demand — existing market | | | | | | [High / Medium / Low] | |
| New customers — current market | | | | | | [High / Medium / Low] | |
| New customers — adjacent market | | | | | | [High / Medium / Low] | |
| Increased price | | | | | | [High / Medium / Low] | |
| Acceleration | | | | | | [High / Medium / Low] | |

---

#### 1.3 Revenue Math Reference

> The organization's standard formulas for translating metrics into revenue impact. Defined here once; referenced in every Business Case.

| Metric | Formula | Current Baseline | Notes |
|---|---|---|---|
| Churn impact | [Churned customers × ACV] | [Current churn rate: X%] | |
| Expansion revenue | [Accounts expanded × average expansion ACV] | [Current expansion rate: X%] | |
| New logo impact | [New customers × ACV] | [Current ACV: $X] | |
| Sales cycle acceleration | [Deals in flight × ACV × (days accelerated ÷ 365)] | [Current avg cycle: X days] | |

---

### Benefit Type 2: Cost Reduction

> An initiative produces a cost reduction benefit when it is expected to reduce the resources the organization consumes — labor, materials, vendor contracts, or other operational costs.

#### 2.1 The Critical Distinction: Savings vs. Cost Avoidance

> This distinction is required in every cost reduction claim. Both are real benefits, but they have different evidence standards and different credibility in a prioritization conversation.

**One-time savings** — The organization currently spends money on something, and this initiative eliminates or reduces that spend. The cost exists today. It appears in the budget. It is visible and defensible.

*Example: Automating a manual process currently performed by 0.5 FTE. The FTE cost is real, visible, and in the budget. The saving is directly calculable.*

**Cost avoidance** — The organization would have spent money on something if this initiative were not undertaken, but that spend has not yet occurred. The cost is counterfactual — real but invisible.

*Example: Building infrastructure now that prevents a costly re-architecture in 18 months. The future cost is real but not in any current budget.*

> Cost avoidance claims are valid but require an explicit counterfactual statement: *"If we do not do this, we expect to incur [cost] by [date] because [specific reason]."* An unstated counterfactual is not cost avoidance — it is speculation. Label every cost reduction claim as one or the other.

---

#### 2.2 Cost Reduction Sub-types

---

**Sub-type A: Labor and Time**

The initiative reduces the amount of human time required to perform a task, process, or function — by eliminating it, automating it, or making it significantly more efficient.

*Mechanisms:*
- Automation of a manual process currently performed by staff
- Elimination of a redundant step, approval, or handoff in a workflow
- Tool consolidation that reduces time spent context-switching or re-entering data
- Self-serve capability that shifts work from internal staff to the customer or partner

*Estimation approach:*
Measure current time spent on the task. Apply the fully-loaded cost rate for the role performing it (see Section 2.4). Estimate the reduction the initiative produces.
Formula: **Hours saved per period × Fully-loaded hourly rate = Periodic savings**

*Evidence standard:*
- Time study or staff self-report of hours spent on the current process
- Support ticket volume or CS time logs if the claim involves customer-facing effort
- Engineering time logs if the claim involves developer time saved

---

**Sub-type B: Material and Infrastructure Costs**

The initiative reduces spend on physical or digital materials, infrastructure, or third-party services.

*Mechanisms:*
- Migration to a lower-cost infrastructure configuration (cloud optimization, right-sizing)
- Vendor consolidation — replacing multiple tools with one, or eliminating a redundant contract
- Reduction in physical materials consumed by a more efficient process
- Elimination of a vendor made redundant by a new internal capability

*Estimation approach:*
Use actual contract values, invoice data, or infrastructure cost reports as the baseline. Estimate the reduction directly from known costs. Do not extrapolate from industry benchmarks unless actual data is unavailable — and flag it when you do.

*Evidence standard:*
- Current vendor invoices or contract values
- Infrastructure cost reports (cloud provider cost tools, etc.)
- Procurement data on materials consumed

---

**Sub-type C: Contractual and Vendor Reductions**

The initiative creates conditions that allow the organization to renegotiate, exit, or restructure vendor relationships.

*Mechanisms:*
- Building a capability in-house that eliminates a vendor dependency
- Reducing usage of a consumption-based service below a contract tier threshold
- Creating a competitive alternative that provides negotiating leverage at renewal

*Estimation approach:*
Anchor to the current contract value and the expected reduction. If the saving depends on a negotiation outcome that is not yet certain, apply a probability discount to the estimate and state it explicitly.

---

#### 2.3 Cost Reduction Estimation Table

| Sub-type | Mechanism | Current Annual Cost | Estimated Reduction | Annual Saving | Savings or Avoidance | Time Horizon | Confidence | Basis |
|---|---|---|---|---|---|---|---|---|
| Labor and time | | | | | [Savings / Avoidance] | | [High / Medium / Low] | |
| Material / Infrastructure | | | | | [Savings / Avoidance] | | [High / Medium / Low] | |
| Contractual / Vendor | | | | | [Savings / Avoidance] | | [High / Medium / Low] | |

---

#### 2.4 Standard Labor Rate Table

> The organization's agreed-upon fully-loaded cost rates by role category. Defined here so that every Business Case uses the same rates and cost comparisons across initiatives are valid.
>
> **Fully-loaded rate** = base salary + benefits + employer taxes + overhead allocation.
> Update annually or when compensation structures change materially.

| Role Category | Fully-Loaded Annual Cost | Hourly Rate (÷ 2,080 hrs) | Notes |
|---|---|---|---|
| [e.g., Senior Engineer] | [$XXX,000] | [$XXX/hr] | [e.g., Includes benefits, equity at grant value, overhead] |
| [e.g., Mid-level Engineer] | [$XXX,000] | [$XXX/hr] | |
| [e.g., Product Manager] | [$XXX,000] | [$XXX/hr] | |
| [e.g., Designer] | [$XXX,000] | [$XXX/hr] | |
| [e.g., Sales — quota-carrying] | [$XXX,000] | [$XXX/hr] | [e.g., Includes OTE at 100% attainment] |
| [e.g., Customer Success] | [$XXX,000] | [$XXX/hr] | |
| [e.g., Operations / Admin] | [$XXX,000] | [$XXX/hr] | |
| [e.g., Executive / Leadership] | [$XXX,000] | [$XXX/hr] | [e.g., Use for opportunity cost calculations — not build estimates] |

> **Contractor and vendor rates:** Use actual contract rates when known. When unknown, apply a [X]% premium over the equivalent internal role rate to reflect the absence of institutional knowledge and the cost of coordination overhead.

---

### Benefit Type 3: Risk Reduction

> An initiative produces a risk reduction benefit when it decreases the expected cost of a risk event — either by reducing the probability that the event occurs, or by reducing the impact if it does occur. Both are valid. Estimate them separately when both apply.

#### 3.1 The Two Mechanisms

**Probability reduction** — The initiative makes a bad event less likely to happen.

*Examples:*
- A security control that reduces the likelihood of a data breach
- A redundancy system that reduces the likelihood of a service outage
- A compliance program that reduces the likelihood of a regulatory violation

**Impact reduction** — The initiative reduces the cost of a bad event if it occurs — without necessarily making it less likely.

*Examples:*
- A disaster recovery system that reduces outage duration from days to hours
- Insurance or contractual indemnification that caps financial exposure
- A customer communication protocol that limits churn following a service incident

> Reducing the likelihood of a $1M event by 50% and reducing the impact of a certain event from $1M to $500K have the same expected value — but they are completely different interventions requiring different evidence and different solutions. Identifying which mechanism an initiative uses is the first step in making the estimate defensible.

---

#### 3.2 Expected Value Framework

Risk reduction benefit is expressed as the reduction in expected value of loss.

> **Expected value of a risk event = Probability of occurrence × Cost if it occurs**
>
> **Risk reduction benefit = Pre-initiative expected value − Post-initiative expected value**

*Example — probability reduction:*
A compliance gap has an estimated 15% annual probability of triggering a regulatory fine averaging $500,000.
Pre-initiative expected loss = 15% × $500,000 = **$75,000/year**
The initiative reduces the probability to 3%.
Post-initiative expected loss = 3% × $500,000 = **$15,000/year**
**Risk reduction benefit = $60,000/year**

*Example — impact reduction:*
A service outage occurs roughly once per year (100% probability) and costs an average of $150,000 in recovery, customer credits, and staff time.
The initiative reduces average outage cost to $30,000 by enabling faster recovery.
**Risk reduction benefit = $120,000/year**

---

#### 3.3 Probability Estimation Standards

> Every risk reduction claim requires a probability estimate. An estimate without a stated basis is not analysis — it is a guess presented as analysis. The basis must be documented.

| Basis Type | Description | Credibility |
|---|---|---|
| **Historical data** | Based on the organization's own incident history | Highest |
| **Industry benchmark** | Based on published rates from a credible external source — regulatory body, insurer, analyst firm | High |
| **Expert judgment** | Based on the informed assessment of a qualified internal or external expert, with reasoning documented | Medium |
| **Analogous situation** | Based on a similar risk in a comparable context, with the analogy explicitly stated | Medium |
| **Assumption** | No external basis — reflects the team's best judgment with no supporting data | Low — must be flagged clearly |

> **Requirement:** Every probability estimate in a Business Case must identify which basis type was used and provide the supporting reference or reasoning. "We think this is unlikely" does not meet the standard.

---

#### 3.4 Risk Reduction Estimation Table

| Risk Event | Risk Category | Mechanism | Pre-Initiative Probability | Pre-Initiative Impact | Pre-Initiative Expected Value | Post-Initiative Probability | Post-Initiative Impact | Post-Initiative Expected Value | Annual Benefit | Probability Basis | Confidence |
|---|---|---|---|---|---|---|---|---|---|---|---|
| [e.g., Regulatory fine — compliance gap] | [Compliance] | [Probability reduction] | [15%] | [$500K] | [$75K/yr] | [3%] | [$500K] | [$15K/yr] | [$60K/yr] | [Industry benchmark — source] | [Medium] |
| [e.g., Extended outage — no failover] | [Operational] | [Impact reduction] | [20%] | [$200K] | [$40K/yr] | [20%] | [$40K] | [$8K/yr] | [$32K/yr] | [Historical — avg 1 per 5 yrs] | [High] |

---

#### 3.5 Risk Categories

> Use these categories consistently across all Business Cases to enable comparison and portfolio-level risk analysis.

| Category | Description | Examples |
|---|---|---|
| **Compliance and regulatory** | Risk of violation, fine, sanction, or enforcement action | Data privacy breach, missed filing, unlicensed activity |
| **Operational** | Risk of disruption to core business operations | System outage, key person departure, supply chain failure |
| **Reputational** | Risk of damage to brand, customer trust, or market position | Public incident, product failure, negative press |
| **Financial** | Risk of direct financial loss not covered by other categories | Fraud, contract dispute, unexpected liability |
| **Strategic** | Risk of a market or competitive shift that erodes organizational position | Competitor capability leap, market contraction, technology displacement |
| **Security** | Risk of unauthorized access, data loss, or system compromise | Breach, ransomware, insider threat |

---

## Part 2: Cost Estimation Framework

> The cost of an initiative is what the organization gives up to pursue it — including direct expenditure, internal resource consumption, and opportunity cost. Every Business Case estimates cost using the methods defined here.
>
> **Costs are not just what is spent. They include what is not done.** An initiative that consumes two engineers for six months has an opportunity cost equal to whatever those engineers would otherwise have built. That cost is real even when it does not appear on an invoice.

---

### Cost Type 1: Internal Labor

> The cost of internal staff time dedicated to the initiative — design, development, testing, project management, stakeholder review, and ongoing maintenance.

**Estimation method:**
1. Identify every role that will contribute meaningful time to the initiative
2. Estimate the effort in hours or weeks per role
3. Apply the fully-loaded hourly rate from Section 2.4
4. Sum across all roles for total internal labor cost

**Effort estimation standard:**

> The organization uses the following method for estimating effort. Select one, define it here, and apply it consistently across all Business Cases.

- [ ] **T-shirt sizing** — S / M / L / XL effort ranges, defined as:
  - S: [e.g., 1–2 weeks, 1–2 people]
  - M: [e.g., 1–2 months, 2–4 people]
  - L: [e.g., 3–6 months, 4–8 people]
  - XL: [e.g., 6+ months, 8+ people]

- [ ] **Story points / sprints** — Estimated in points; 1 sprint = [X] weeks; team velocity = [Y] points/sprint

- [ ] **Day-based estimation** — Engineering days estimated by the team closest to the work; apply [X]% buffer for unknowns

- [ ] **Analogous estimation** — Compared to a prior initiative of similar scope; deviation from analogy must be documented

**Uncertainty buffer:**
All internal labor estimates include a **[X]%** uncertainty buffer applied at the total, not per task. Padding individual tasks obscures real uncertainty — one honest buffer at the summary level is more useful and more honest.

---

### Cost Type 2: External and Vendor Costs

> The cost of third-party services, software, contractors, consultants, or vendors required to execute the initiative.

| Category | Description | Estimation Method |
|---|---|---|
| **Software / SaaS** | New licenses, platform fees, or increased tier costs | Use actual vendor quotes where possible; use list price with negotiation discount applied if not |
| **Contractors / Consultants** | External labor augmenting internal capacity | Use actual contract rates; apply standard rate table premium if rate is unknown |
| **Professional services** | Implementation support, integration work, or training delivery from an external firm | Use SOW value; if SOW not yet available, use a comparable prior engagement as the basis |
| **Infrastructure** | Cloud compute, storage, or networking costs directly attributable to the initiative | Use infrastructure team estimate or cloud provider cost calculator |
| **Legal / Compliance** | External counsel, certification fees, or audit costs | Use prior engagement rates or counsel estimate |

---

### Cost Type 3: Opportunity Cost

> The value of the work that will not be done because resources are committed to this initiative. Opportunity cost is real even when it does not appear in any budget.

**When to include an explicit opportunity cost estimate:**
- The initiative consumes a meaningful share of a constrained resource (e.g., >20% of engineering capacity for more than one sprint)
- The alternative use of those resources is known and has an estimated benefit value
- The initiative is being evaluated against another initiative competing for the same resources

**Estimation method:**
If a specific alternative initiative is displaced, use its estimated benefit as the opportunity cost of this one.

If no specific alternative is identified, state explicitly: *"[X] engineer-weeks committed to this initiative represents opportunity cost against the product roadmap. No specific displaced initiative has been identified at this time."*

> Do not fabricate a specific opportunity cost where one does not exist. Acknowledging the cost without quantifying it is more honest and more useful than a number with no basis.

---

### Cost Type 4: Ongoing and Maintenance Costs

> The cost of sustaining the initiative after it ships — ongoing labor, vendor fees, infrastructure, and periodic updates.

> **This is the most commonly omitted cost in business cases.** An initiative that costs $200K to build and $80K/year to maintain has a fundamentally different total cost profile than one that costs $200K to build and $5K/year to maintain. Omitting maintenance costs systematically biases the organization toward building things it cannot afford to sustain.

| Cost Item | Annual Cost | Notes |
|---|---|---|
| [e.g., Engineering maintenance — 0.25 FTE ongoing] | [$XX,000/yr] | [e.g., Bug fixes, dependency updates, minor enhancements] |
| [e.g., Vendor license — ongoing SaaS fee] | [$XX,000/yr] | |
| [e.g., Infrastructure — incremental hosting cost] | [$XX,000/yr] | |
| [e.g., Compliance — periodic audit or certification renewal] | [$XX,000/yr] | |

---

### Cost Summary Table

> Consolidate all cost types here for use in the Business Case.

| Cost Type | One-Time Cost | Annual Ongoing Cost | Notes |
|---|---|---|---|
| Internal labor — build | | — | [e.g., Roles, weeks, method used] |
| Internal labor — maintenance | — | | [e.g., FTE estimate, role] |
| External / vendor | | | [e.g., SOW, license, services] |
| Infrastructure | | | |
| Opportunity cost | | — | [e.g., Roadmap displacement — describe] |
| Uncertainty buffer ([X]%) | | | [Applied to internal labor total] |
| **Total** | | | |

---

## Part 3: Benefit-Cost Summary

> The consolidated view used in every Business Case. Benefits and costs on the same page, built from the same methods, so the tradeoff is visible and the comparison is valid.

| | Year 1 | Year 2 | Year 3 | Notes |
|---|---|---|---|---|
| **Revenue growth benefit** | | | | |
| **Cost reduction benefit** | | | | |
| **Risk reduction benefit** | | | | |
| **Total estimated benefit** | | | | |
| **Total one-time cost** | | | | [Amortized here if applicable] |
| **Total annual ongoing cost** | | | | |
| **Net benefit** | | | | |
| **Cumulative net benefit** | | | | |
| **Break-even point** | | | | [Month / quarter when cumulative benefit exceeds total cost] |

**Confidence summary:**

| Benefit / Cost Item | Confidence | Primary Risk to Estimate |
|---|---|---|
| [Revenue growth claim] | [High / Medium / Low] | [e.g., Churn reduction depends on adoption rate not yet validated] |
| [Cost reduction claim] | [High / Medium / Low] | [e.g., Labor savings assume process is fully automated — partial automation reduces the estimate] |
| [Risk reduction claim] | [High / Medium / Low] | [e.g., Probability estimate is assumption-based — no historical data available] |
| [Build cost estimate] | [High / Medium / Low] | [e.g., T-shirt sized L — uncertainty buffer applied] |

---

## Part 4: Framework Governance

> How this framework is maintained, who is responsible, and how disputes about estimates are resolved.

### Calibration

> Over time, Business Cases should be reviewed against actual outcomes. Estimates that consistently over- or under-perform signal a calibration problem in the framework — not just in individual cases.

| Review Trigger | Action |
|---|---|
| Initiative completes | Compare estimated vs. actual cost; compare estimated vs. realized benefit at 6 and 12 months |
| Estimate variance >30% from actual | Document the gap and reason in Institutional-Knowledge.md; review relevant framework assumption |
| Annual framework review | Update labor rate table; review effort estimation method; review standard uncertainty buffer |

### Dispute Resolution

> When stakeholders disagree about an estimate, the dispute is about the assumption — not the number. Surface the assumption, not the number.

1. Identify which specific assumption drives the disagreement
2. Determine what evidence would resolve it — and whether that evidence is obtainable before the decision must be made
3. If evidence is not obtainable in time, document the disagreement and the range of reasonable estimates, and let the decision-maker choose with full visibility into the uncertainty
4. Do not average competing estimates to manufacture false agreement

### Open Questions

| # | Question | Owner | Due Date | Resolution |
|---|---|---|---|---|
| 1 | [e.g., What uncertainty buffer percentage does the organization want to standardize on?] | [Name] | YYYY-MM-DD | |
| 2 | [e.g., Which effort estimation method — t-shirt sizing, story points, or day-based — will be the standard?] | [Name] | YYYY-MM-DD | |
| 3 | [e.g., How frequently will actual vs. estimated outcomes be reviewed, and who owns that process?] | [Name] | YYYY-MM-DD | |
