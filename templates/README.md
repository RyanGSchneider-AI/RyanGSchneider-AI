# Templates

Reusable frameworks for corporate intelligence and AI-assisted execution.

These templates are designed to be **independently useful across the organization**
— not just for product and engineering teams. Each artifact stands on its own and
serves its primary audience, while connecting to the others when needed.

The goal is a shared intelligence layer that improves decision-making across
Product, Sales, Marketing, Finance, Legal, and Executive leadership — and that
provides the structured context AI-assisted teams and agents need to execute
without ambiguity.

---

## Corporate Intelligence Framework

```
├── Product
│   ├── Product-Chronicle.md         ← Living product intelligence: design   [coming soon]
│   │                                   principles, tradeoff rationale,
│   │                                   customer understanding, competitive
│   │                                   positioning, and internal narrative
│   ├── PRD-Template.md              ← Requirements, test, and agent handoff
│   └── Business-Case.md             ← Rationale for pursuing an effort     [coming soon]
│
├── People and Relationships
│   ├── Internal-Stakeholders.md     ← Internal org structure and stakeholder concerns
│   │   Governed by: Organizational structure and reporting authority
│   │
│   └── External-Stakeholders.md     ← Strategic partners, vendors, and regulatory bodies
│       Governed by: Contracts, agreements, terms of service, and compliance obligations
│
├── Market and Customer
│   ├── Key-Customers.md             ← Named accounts with strategic importance
│   ├── Customer-Personas.md         ← Research-based archetypes organized by use case
│   └── Competitive-Intelligence.md  ← Market landscape, competitor analysis  [coming soon]
│                                       and positioning
│
├── Rhythm and Calendar
│   ├── Company-Calendar.md          ← Industry events, product releases, compliance dates, and organizational milestones [coming soon]
│   └── Operating-Cadences.md        ← Internal organizational rhythms and recurring process cycles                       [coming soon]
│
├── Operations
│   └── Key-Operational-Processes.md ← Critical processes, workflows, and    [coming soon]
│                                       how work actually gets done
│
├── Sales
│   ├── Go-to-Market.md              ← Channels, sales motion, and target     [coming soon]
│   │                                   segment strategy
│   ├── Pricing-and-Packaging.md     ← How products are priced, bundled,      [coming soon]
│   │                                   and positioned commercially
│   └── Sales-Playbook.md            ← How deals are run: stages, discovery,  [coming soon]
│                                       objection handling, and competitive
│                                       positioning in a sales context
│
├── Systems and Data
│   ├── Systems-Registry.md          ← All platforms the organization uses,   [coming soon]
│   │                                   with clear designation of which are
│   │                                   Systems of Record for each data domain
│   ├── Data-Dictionary.md           ← Authoritative definitions of key data  [coming soon]
│   │                                   entities, their meaning, and where
│   │                                   they live — prevents ambiguity across
│   │                                   systems, teams, and AI agents
│   └── Data-Intelligence-Map.md     ← What useful insight lives in each      [coming soon]
│                                       system, and how data flows and enriches
│                                       across systems to answer business
│                                       questions no single system can
│
├── Financial
│   ├── Financial-Reference.md       ← High-level financial context: revenue   [coming soon]
│   │                                   scale, expense materiality thresholds,
│   │                                   and budgeting framework — not a ledger
│   ├── Cost-Estimation-Framework.md ← Company-wide cost modeling standards    [coming soon]
│   └── Revenue-Projection-Framework.md ← Company-wide revenue projection      [coming soon]
│                                        and adjustment methodology
│
└── Organizational Intelligence
    ├── Institutional-Knowledge.md   ← Living repository of decisions, lessons, constraints, and process
    └── Strategic-Context.md         ← Living organizational goals, reasoning, and initiative connections
```

---

## Contents

| File | Description | Governed By | Serves |
|---|---|---|---|
| Product-Chronicle.md | Living product intelligence — design principles, tradeoffs, customer understanding, and internal narrative | Product ownership and accumulated organizational learning | Product, Marketing, Sales, Engineering |
| [PRD-Template.md](./PRD-Template.md) | AI-ready Product Requirements Document | Product roadmap and initiative priority | Product, Engineering, QA, Compliance |
| Business-Case.md | Rationale for pursuing a product effort | Product strategy and executive approval | Product, Finance, Executive Leadership |
| [Internal-Stakeholders.md](./Internal-Stakeholders.md) | Internal org structure and stakeholder areas of concern | Organizational structure and reporting authority | All internal teams |
| [External-Stakeholders.md](./External-Stakeholders.md) | Strategic partners, vendors, and regulatory bodies | Contracts, agreements, terms of service, and compliance obligations | Sales, Legal, Finance, Executive Leadership |
| [Key-Customers.md](./Key-Customers.md) | Named accounts classified by revenue tier and strategic importance | Executed agreements and terms of service | Sales, Executive Leadership, Product, Finance |
| [Customer-Personas.md](./Customer-Personas.md) | Research-based customer archetypes organized by use case | Research and market understanding | Product, Marketing, Sales |
| Competitive-Intelligence.md | Market landscape, competitor profiles, and positioning analysis | Market research and ongoing competitive monitoring | Product, Marketing, Sales, Executive Leadership |
| Company-Calendar.md | Industry events, product releases, compliance dates, and organizational milestones | Organizational planning and external commitments | All teams |
| Operating-Cadences.md | Internal organizational rhythms and recurring process cycles | Organizational structure and operational discipline | All teams, Finance, Executive Leadership |
| Key-Operational-Processes.md | Critical processes and how work actually gets done | Operations leadership | All teams, new hires, AI agents |
| Go-to-Market.md | Channels, sales motion, and target segment strategy | Sales and Marketing leadership | Sales, Marketing, Product, Executive Leadership |
| Pricing-and-Packaging.md | How products are priced, bundled, and positioned commercially | Product and Finance leadership | Sales, Product, Finance, Executive Leadership |
| Sales-Playbook.md | How deals are run — stages, discovery, objection handling, and competitive positioning | Sales leadership | Sales, Marketing |
| Systems-Registry.md | All platforms the organization uses, with clear designation of Systems of Record per data domain | IT and Operations leadership | All teams, Engineering, Finance, AI agents |
| Data-Dictionary.md | Authoritative definitions of key data entities, their meaning, and where they live | Engineering and Data leadership | Engineering, Product, Finance, AI agents |
| Data-Intelligence-Map.md | What useful insight lives in each system, and how data flows and enriches across systems to answer business questions no single system can | Engineering, Data, and Product leadership | Product, Sales, Finance, Marketing, AI agents |
| Financial-Reference.md | High-level financial context — revenue scale, materiality thresholds, and budgeting framework | Finance leadership | Executive Leadership, Product, Finance, Department heads |
| Cost-Estimation-Framework.md | Company-wide standards for estimating initiative costs | Finance and Product leadership | Product, Finance, Executive Leadership |
| Revenue-Projection-Framework.md | Company-wide methodology for projecting and adjusting revenue forecasts | Finance and Product leadership | Finance, Product, Executive Leadership |
| [Institutional-Knowledge.md](./Institutional-Knowledge.md) | Living repository of organizational learning — decisions, lessons, constraints, and process | Collectively owned — fed from retros, reviews, and organizational feedback | All teams, new hires, AI agents |
| [Strategic-Context.md](./Strategic-Context.md) | Organizational mission, vision, and living goals across time horizons | Collectively owned — maintained against current organizational direction | All teams, executive leadership, AI agents |

---

## Design Philosophy

These templates are built around three principles:

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

**AI-ready** — every template is structured for both human readers and
AI-assisted teams or autonomous agents. The discipline that makes a good
AI handoff makes a good human handoff too.

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
