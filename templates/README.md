# Templates

Reusable frameworks for corporate intelligence and AI-assisted execution.

These templates are designed to be **independently useful across the organization**
— not just for product and engineering teams. Each artifact stands on its own and
serves its primary audience, while connecting to the others when needed.

The goal is a shared intelligence layer that improves decision-making across
Product, Sales, Marketing, Finance, Legal, and Executive leadership — and that
provides the structured context AI-assisted teams and agents need to execute
without ambiguity.

### Serving as a Framework for Organizational Memory

Organizations lose memory in predictable ways — through personnel changes where knowledge walks out the door, through growth that outpaces documentation, and through M&A, where entire leadership layers are replaced and the context behind decisions disappears with them. This framework is a deliberate defense against that loss.

Organizational memory lives in three places: **People**, **Process**, and **Culture**. People leave, taking accumulated judgment with them. Culture is emergent — it cannot be defined or mandated, only reflected in the decisions and behaviors the organization accumulates over time. Process is the most recoverable leg, but only when the *why* behind each process is captured alongside the *what* — and only when that capture is treated as ongoing work, not a one-time exercise.

AI tools make it possible to capture and synthesize organizational memory in ways that weren't previously practical. Artifacts that once required dedicated effort to produce can now be captured as a natural part of existing workflows — and the same tools can actively apply that memory, helping teams and agents make decisions that are grounded in what the organization has already learned.

By capturing not just *what* was decided but *why* — not just *how* work gets done but *how the how came about* — these artifacts preserve the organizational context that makes new team members, new leadership, and AI agents effective faster, and give the organization a fighting chance of understanding why it has been successful.

---

## Corporate Intelligence Framework

```
├── Financial
│   ├── Cost-and-Benefit-Framework.md ← Standard benefit and cost estimation methods — ensures every Business Case is comparable
│   └── Funding-and-Business-Model.md ← Capitalization, business model, and organizational drivers
│
├── Market and Customer
│   ├── Brand-and-Narrative.md         ← Narrative architecture, voice, messaging hierarchy, and how the organization tells its story consistently
│   ├── Competitive-Intelligence.md    ← Direct competitors, substitute solutions, status quo alternatives, and competitive signal log
│   ├── Customer-Personas.md           ← Research-based archetypes organized by use case
│   └── Reference-Customers-and-Champions.md ← Strategic accounts, individual champions, relationship health, and reference activity
│
├── Operations
│   ├── Key-Operational-Processes.md   ← Recurring process inventory, full process records, and change impact guidance
│   └── Organizational-Risk-and-Compliance.md ← Risk inventory, compliance obligations, certifications, and event log
│
├── Organizational Intelligence
│   ├── Institutional-Knowledge.md     ← Living repository of decisions, lessons, constraints, and process
│   ├── Metrics-Framework.md           ← What the organization measures —       [coming soon]
│   │                                     standardized definitions, financial
│   │                                     context, and Goodhart's Law guardrails
│   │                                     distinguishing health indicators from
│   │                                     targets
│   └── Strategy-and-Intent.md           ← Living organizational goals, reasoning, and initiative connections
│
├── People and Relationships
│   ├── External-Stakeholders.md       ← Strategic partners, vendors, and regulatory bodies
│   │   Governed by: Contracts, agreements, terms of service, and compliance obligations
│   │
│   ├── Internal-Stakeholders.md       ← Internal org structure and stakeholder concerns
│   │   Governed by: Organizational structure and reporting authority
│   │
│   └── People-and-Talent-Strategy.md  ← How the organization thinks about hiring, capability gaps, succession, and the skills needed to execute strategy
│
├── Product
│   ├── Business-Case.md               ← Rationale for pursuing an effort
│   ├── Product-Build-Record.md        ← Full initiative lifecycle — estimate, build, actuals, retrospective
│   ├── Product-Chronicle.md           ← Living product intelligence: design principles, tradeoff rationale, customer understanding, competitive positioning, and internal narrative
│   └── Product-Design-Guide.md        ← Persistent UI/UX standards, interaction patterns, voice and tone, and accessibility commitments — governs all PRDs that touch UI/UX
│
├── Rhythm and Calendar
│   └── Company-Calendar.md            ← Annual cycles, events, release windows, and capacity context for initiative timing
│
├── Sales
│   ├── Go-to-Market.md                ← Channels, sales motion, target segment strategy, and pricing and packaging
│   └── Sales-Playbook.md              ← How deals are run: stages, discovery, objection handling, and competitive positioning in a sales context
│
└── Systems and Data
    └── Systems-and-Data.md            ← Systems registry, System of Record map, data dictionary, data intelligence map, and access register — unified around the system as organizing spine
```

---

## Contents

| File | Description | Governed By | Serves |
|---|---|---|---|
| [Brand-and-Narrative.md](./Market-and-Customer/Brand-and-Narrative.md) | Narrative architecture, voice principles, messaging hierarchy, and core story — ensures consistent communication across every context and audience | Marketing and Executive leadership | Marketing, Sales, Product, Executive Leadership, AI agents |
| [Business-Case.md](./Product/Business-Case.md) | Rationale for pursuing a product effort — scales from brief internal reasoning to formal executive approval | Product strategy and executive approval | Product, Finance, Executive Leadership |
| [Company-Calendar.md](./Rhythm-and-Calendar/Company-Calendar.md) | Annual fiscal, product, sales, industry, and organizational cycles — with specific known dates — providing the timing context for any Business Case or Product Build Record | Operations and Executive leadership | All teams, Product, Sales, Finance |
| [Competitive-Intelligence.md](./Market-and-Customer/Competitive-Intelligence.md) | Direct competitor profiles, substitute solution analysis, status quo alternatives, win/loss patterns, and a continuous competitive signal log | Product, Marketing, and Sales leadership | Product, Sales, Marketing, Executive Leadership |
| [Cost-and-Benefit-Framework.md](./Financial/Cost-and-Benefit-Framework.md) | Standard methods for estimating revenue growth, cost reduction, and risk reduction benefits — and for estimating initiative costs consistently across all Business Cases | Finance and Product leadership | Product, Finance, Executive Leadership |
| [Customer-Personas.md](./Market-and-Customer/Customer-Personas.md) | Research-based customer archetypes organized by use case | Research and market understanding | Product, Marketing, Sales |
| [External-Stakeholders.md](./People-and-Relationships/External-Stakeholders.md) | Strategic partners, vendors, and regulatory bodies | Contracts, agreements, terms of service, and compliance obligations | Sales, Legal, Finance, Executive Leadership |
| [Funding-and-Business-Model.md](./Financial/Funding-and-Business-Model.md) | How the organization is capitalized, how it creates and captures value, and what it is currently optimizing for — essential context for strategy, product, and financial decisions | Finance and Executive leadership | Executive Leadership, Board, Finance, Product |
| [Go-to-Market.md](./Sales/Go-to-Market.md) | Channels, sales motion, target segment strategy, and pricing and packaging — accommodates any combination of product-led, sales-led, and partner-led motions | Sales and Marketing leadership | Sales, Marketing, Product, Executive Leadership |
| [Institutional-Knowledge.md](./Organizational-Intelligence/Institutional-Knowledge.md) | Living repository of organizational learning — decisions, lessons, constraints, and process | Collectively owned — fed from retros, reviews, and organizational feedback | All teams, new hires, AI agents |
| [Internal-Stakeholders.md](./People-and-Relationships/Internal-Stakeholders.md) | Internal org structure and stakeholder areas of concern | Organizational structure and reporting authority | All internal teams |
| [Key-Operational-Processes.md](./Operations/Key-Operational-Processes.md) | Inventory and records of every recurring process the organization depends on — including ownership, failure modes, system dependencies, and a structured guide for evaluating how any change will interact with existing processes | Operations and Executive leadership | All teams, Product, Finance, new hires, AI agents |
| Metrics-Framework.md | What the organization measures — standardized definitions, financial context, and Goodhart's Law guardrails distinguishing health indicators from targets | Finance, Data, and Product leadership | All teams, Finance, Executive Leadership, AI agents |
| [Organizational-Risk-and-Compliance.md](./Operations/Organizational-Risk-and-Compliance.md) | Risk inventory with probability and impact records, compliance obligations register, certification and audit history, and a running event log — the source of risk data for Cost-and-Benefit-Framework benefit claims | Legal, Operations, and Executive leadership | All teams, Legal, Finance, Executive Leadership, AI agents |
| [People-and-Talent-Strategy.md](./People-and-Relationships/People-and-Talent-Strategy.md) | How the organization thinks about capability needs, search and onboarding, culture fit, and key person risk — tied directly to strategic goals | HR and Executive leadership | Executive Leadership, Department heads, HR |
| [Product-Build-Record.md](./Product/Product-Build-Record.md) | Complete record of a discrete product effort at a specific validation stage (Prototype → Pilot → Beta → A/B → GA) — multiple records may serve a single Business Case, each passing findings forward to the next | Product ownership across the full initiative lifecycle | Product, Engineering, QA, Finance, Executive Leadership |
| [Product-Chronicle.md](./Product/Product-Chronicle.md) | Living product intelligence — design principles, tradeoffs, customer understanding, and internal narrative | Product ownership and accumulated organizational learning | Product, Marketing, Sales, Engineering |
| [Product-Design-Guide.md](./Product/Product-Design-Guide.md) | Persistent UI/UX standards, interaction patterns, voice and tone, and accessibility commitments | Product and Design leadership | Product, Engineering, Design, QA |
| [Reference-Customers-and-Champions.md](./Market-and-Customer/Reference-Customers-and-Champions.md) | Strategic accounts and individual champions — classified by role, tracked for health, and used actively in sales and marketing | Customer Success and Sales leadership | Sales, Executive Leadership, Product, Marketing |
| [Sales-Playbook.md](./Sales/Sales-Playbook.md) | How deals are run — discovery, stakeholder mapping, objection handling, pricing conversations, and competitive positioning | Sales leadership | Sales, Marketing |
| [Strategy-and-Intent.md](./Organizational-Intelligence/Strategy-and-Intent.md) | Organizational mission, vision, living goals across time horizons, and the strategic assumptions and risks that underpin them | Collectively owned — maintained against current organizational direction | All teams, executive leadership, AI agents |
| [Systems-and-Data.md](./Systems-and-Data/Systems-and-Data.md) | Systems registry, System of Record map, data dictionary (entity definitions and aliases), data intelligence map (what each system can answer and what combinations unlock), and access and security register — unified in one document | IT, Engineering, and Data leadership | All teams, Engineering, Product, Finance, AI agents |


---

## Design Philosophy

These templates are built around four principles:

**Independently useful** — each artifact is valuable on its own, to its primary
audience, without requiring the full framework to be in place. An artifact should
never be blocked by the absence of another. If related artifacts exist, use them.
If they don't, move forward independently.

**Connectable** — artifacts inform each other at the point of use, not through
hardcoded references within each file. The README is the map. Connections are made
in context — in a PRD, a Business Case, a meeting — not maintained as lists inside
every document. Relationships between artifacts are flexible and situational: a
Business Case can spawn multiple PRDs, a PRD may support multiple Business Cases,
and a Maintenance PRD may have no Business Case at all. No relationship is assumed
— all are possible.

**Memory-preserving** — every artifact is designed to capture not just *what* was
decided or built, but *why*. The reasoning behind a decision is as important as the
decision itself — often more so, because it is what gets lost first. An organization
that knows what it decided but not why will relitigate the same questions every time
personnel changes. An organization that captures the why builds judgment that survives
turnover, scales through growth, and recovers from the disruption of M&A. Each artifact
in this framework is a deposit into that organizational memory — individually useful,
and collectively a record of how the organization thinks.

**AI-ready** — every template is structured for both human readers and
AI-assisted teams or autonomous agents. The discipline that makes a good
AI handoff makes a good human handoff too. An AI agent operating from this
framework has the context to act with intent — not just instructions, but the
reasoning and organizational memory behind them.

---

## How to Use These Templates

### Artifact Types
These artifacts fall into two categories:

**Living frameworks** — maintained continuously as a single source of truth for the organization or product. Most artifacts in this framework are this type. They are never "complete" — they are updated as the organization learns, decisions are made, and context changes. Start with whatever sections are most immediately useful and fill in the rest over time.

**Per-effort documents** — created fresh for each discrete initiative. Two artifacts work this way:
- **Product-Build-Record** — one per development effort
- **Business-Case** — one per initiative contemplated

When creating a per-effort document, copy the template, rename it to reflect the specific effort (e.g., `PRD-user-onboarding-2026.md`, `Business-Case-mobile-app.md`), and work through the relevant sections.

### Flexibility, Not Rigor
No artifact needs to be complete before it is useful. Start with what you know. A partially populated Chronicle is more valuable than no Chronicle. A rough Business Case with honest estimates is more valuable than no Business Case.

The framework does not require a specific sequence. Use whichever artifact is most relevant to the work at hand. An artifact that stands alone is still doing its job.

### How Artifacts Stay Current
Artifacts are updated in two ways:

**In the background** — as work happens, decisions are made, and things are learned, the relevant artifacts should be updated to reflect the new state. A product decision that changes a design principle belongs in the Chronicle. A closed deal that produces a new reference customer belongs in Reference Customers and Champions. This is the default: updates flow naturally from activity.

**Explicitly** — any artifact can be deliberately updated to inform or trigger a review of related artifacts. If the Customer Lens in the Chronicle changes significantly, it should prompt a review of the Design Principles. If Strategy-and-Intent shifts, People-and-Talent-Strategy should be reviewed against it. These connections are made at the point of use — not hardcoded in the artifacts themselves.

### Standalone vs. Connected
Each artifact is independently useful. An organization that only has a PRD and a Business Case is still better off than one with neither. Each artifact added to the framework increases the intelligence available to the people and agents working within it.

The framework becomes compoundingly more powerful as more artifacts are populated and connected. A PRD that can reference a populated Product Chronicle, Design Guide, Customer Personas, and Competitive Intelligence is a fundamentally different document than one written in isolation — and an AI agent working from a fully populated framework operates with organizational context that would otherwise take months to absorb.

---

## This Framework is Evolving

Templates are added and refined as they are applied to real work. If you use
one and find a gap, open an issue or submit a PR.
