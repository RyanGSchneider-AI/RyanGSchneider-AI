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
│   └── Cost-and-Benefit-Framework.md ← How the organization estimates effort  [coming soon]
│                                        and impact — informs every Business
│                                        Case; scales from solo founder to
│                                        enterprise
│
├── Market and Customer
│   ├── Brand-and-Narrative.md         ← External brand position, voice, and   [coming soon]
│   │                                     messaging architecture — how the
│   │                                     organization wants to be perceived
│   ├── Competitive-Intelligence.md    ← Market landscape and competitor        [coming soon]
│   │                                     analysis — from formal profiles to
│   │                                     "here's what my users are also using"
│   ├── Customer-Personas.md           ← Research-based archetypes organized by use case
│   └── Reference-Customers-and-Champions.md ← Customers who validate the      [coming soon]
│                                              product, open doors, and advocate
│                                              in the market
│
├── Operations
│   ├── Key-Operational-Processes.md   ← Critical processes, workflows, and    [coming soon]
│   │                                     how work actually gets done
│   └── Organizational-Risk-and-Compliance.md ← Risk inventory, compliance      [coming soon]
│                                               obligations, certifications, and
│                                               regulatory commitments — informs
│                                               how operational processes are
│                                               designed and governed
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
│   ├── PRD-Template.md                ← Requirements, test, and agent handoff
│   ├── Product-Chronicle.md           ← Living product intelligence: design principles, tradeoff rationale, customer understanding, competitive positioning, and internal narrative
│   └── Product-Design-Guide.md        ← Persistent UI/UX standards, interaction patterns, voice and tone, and accessibility commitments — governs all PRDs that touch UI/UX
│
├── Rhythm and Calendar
│   └── Company-Calendar.md            ← Industry events, product releases,     [coming soon]
│                                          compliance dates, internal cadences,
│                                          and organizational milestones
│
├── Sales
│   ├── Go-to-Market.md                ← Channels, sales motion, target segment strategy, and pricing and packaging
│   └── Sales-Playbook.md              ← How deals are run: stages, discovery, objection handling, and competitive positioning in a sales context
│
└── Systems and Data
    ├── Data-Dictionary.md             ← Authoritative definitions of key data   [coming soon]
    │                                     entities, their meaning, and where
    │                                     they live — prevents ambiguity across
    │                                     systems, teams, and AI agents
    ├── Data-Intelligence-Map.md       ← What useful insight lives in each       [coming soon]
    │                                     system, and how data flows and enriches
    │                                     across systems to answer business
    │                                     questions no single system can
    └── Systems-Registry.md            ← All platforms the organization uses,    [coming soon]
                                          with clear designation of which are
                                          Systems of Record for each data domain
```

---

## Contents

| File | Description | Governed By | Serves |
|---|---|---|---|
| Brand-and-Narrative.md | External brand position, voice, and messaging architecture — how the organization wants to be perceived and talked about | Marketing and Executive leadership | Marketing, Sales, Product, Executive Leadership |
| [Business-Case.md](./product/Business-Case.md) | Rationale for pursuing a product effort — scales from brief internal reasoning to formal executive approval | Product strategy and executive approval | Product, Finance, Executive Leadership |
| Company-Calendar.md | Industry events, product releases, compliance dates, internal cadences, and organizational milestones | Organizational planning and external commitments | All teams |
| Competitive-Intelligence.md | Market landscape and competitor analysis — from formal profiles to informal usage mapping | Market research and ongoing competitive monitoring | Product, Marketing, Sales, Executive Leadership |
| Cost-and-Benefit-Framework.md | How the organization estimates effort and impact — living history of tradeoff characterization that informs every Business Case; scales from solo founder to enterprise | Finance and Product leadership | Product, Finance, Executive Leadership |
| [Customer-Personas.md](./market-and-customer/Customer-Personas.md) | Research-based customer archetypes organized by use case | Research and market understanding | Product, Marketing, Sales |
| Data-Dictionary.md | Authoritative definitions of key data entities, their meaning, and where they live | Engineering and Data leadership | Engineering, Product, Finance, AI agents |
| Data-Intelligence-Map.md | What useful insight lives in each system, and how data flows and enriches across systems to answer business questions no single system can | Engineering, Data, and Product leadership | Product, Sales, Finance, Marketing, AI agents |
| [External-Stakeholders.md](./people-and-relationships/External-Stakeholders.md) | Strategic partners, vendors, and regulatory bodies | Contracts, agreements, terms of service, and compliance obligations | Sales, Legal, Finance, Executive Leadership |
| [Go-to-Market.md](./sales/Go-to-Market.md) | Channels, sales motion, target segment strategy, and pricing and packaging — accommodates any combination of product-led, sales-led, and partner-led motions | Sales and Marketing leadership | Sales, Marketing, Product, Executive Leadership |
| [Institutional-Knowledge.md](./organizational-intelligence/Institutional-Knowledge.md) | Living repository of organizational learning — decisions, lessons, constraints, and process | Collectively owned — fed from retros, reviews, and organizational feedback | All teams, new hires, AI agents |
| [Internal-Stakeholders.md](./people-and-relationships/Internal-Stakeholders.md) | Internal org structure and stakeholder areas of concern | Organizational structure and reporting authority | All internal teams |
| Key-Operational-Processes.md | Critical processes and how work actually gets done | Operations leadership | All teams, new hires, AI agents |
| Metrics-Framework.md | What the organization measures — standardized definitions, financial context, and Goodhart's Law guardrails distinguishing health indicators from targets | Finance, Data, and Product leadership | All teams, Finance, Executive Leadership, AI agents |
| Organizational-Risk-and-Compliance.md | Risk inventory, compliance obligations, certifications, and regulatory commitments — informs how operational processes are designed and governed | Legal, Operations, and Executive leadership | All teams, Legal, Finance, Executive Leadership, AI agents |
| [People-and-Talent-Strategy.md](./people-and-relationships/People-and-Talent-Strategy.md) | How the organization thinks about capability needs, search and onboarding, culture fit, and key person risk — tied directly to strategic goals | HR and Executive leadership | Executive Leadership, Department heads, HR |
| [PRD-Template.md](./product/PRD-Template.md) | AI-ready Product Requirements Document | Product roadmap and initiative priority | Product, Engineering, QA, Compliance |
| [Product-Chronicle.md](./product/Product-Chronicle.md) | Living product intelligence — design principles, tradeoffs, customer understanding, and internal narrative | Product ownership and accumulated organizational learning | Product, Marketing, Sales, Engineering |
| [Product-Design-Guide.md](./product/Product-Design-Guide.md) | Persistent UI/UX standards, interaction patterns, voice and tone, and accessibility commitments | Product and Design leadership | Product, Engineering, Design, QA |
| Reference-Customers-and-Champions.md | Customers who validate the product, open doors, and advocate in the market — classified by strategic role, not just revenue | Executed agreements and terms of service | Sales, Executive Leadership, Product, Marketing |
| [Sales-Playbook.md](./sales/Sales-Playbook.md) | How deals are run — discovery, stakeholder mapping, objection handling, pricing conversations, and competitive positioning | Sales leadership | Sales, Marketing |
| [Strategy-and-Intent.md](./organizational-intelligence/Strategy-and-Intent.md) | Organizational mission, vision, living goals across time horizons, and the strategic assumptions and risks that underpin them | Collectively owned — maintained against current organizational direction | All teams, executive leadership, AI agents |
| Systems-Registry.md | All platforms the organization uses, with clear designation of Systems of Record per data domain | IT and Operations leadership | All teams, Engineering, Finance, AI agents |

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

1. Copy the template into the relevant project or team folder
2. Rename it to reflect the specific use (e.g., `PRD-payments-onboarding.md`)
3. Work top to bottom — resist the urge to skip ahead
4. Treat each document as a living record — update as decisions change,
   questions resolve, and results come in

---

## This Framework is Evolving

Templates are added and refined as they are applied to real work. If you use
one and find a gap, open an issue or submit a PR.
