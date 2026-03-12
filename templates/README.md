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
├── Financial
│   ├── Cost-and-Benefit-Framework.md ← How the organization estimates effort  [coming soon]
│   │                                    and impact — informs every Business
│   │                                    Case; scales from solo founder to
│   │                                    enterprise
│   └── Financial-Reference.md        ← High-level financial context: revenue  [coming soon]
│                                        scale, expense materiality thresholds,
│                                        and budgeting framework — not a ledger
│
├── Market and Customer
│   ├── Competitive-Intelligence.md   ← Market landscape and competitor        [coming soon]
│   │                                    analysis — from formal profiles to
│   │                                    "here's what my users are also using"
│   ├── Customer-Personas.md          ← Research-based archetypes organized by use case
│   └── Key-Customers.md              ← Named accounts with strategic importance
│
├── Operations
│   └── Key-Operational-Processes.md  ← Critical processes, workflows, and    [coming soon]
│                                        how work actually gets done
│
├── Organizational Intelligence
│   ├── Institutional-Knowledge.md    ← Living repository of decisions, lessons, constraints, and process
│   ├── Metrics-Framework.md          ← What the organization measures, standardized  [coming soon]
│   │                                    definitions, and which metrics should never
│   │                                    become targets (Goodhart's Law guardrails)
│   └── Strategic-Context.md          ← Living organizational goals, reasoning, and initiative connections
│
├── People and Relationships
│   ├── External-Stakeholders.md      ← Strategic partners, vendors, and regulatory bodies
│   │   Governed by: Contracts, agreements, terms of service, and compliance obligations
│   │
│   └── Internal-Stakeholders.md      ← Internal org structure and stakeholder concerns
│       Governed by: Organizational structure and reporting authority
│
├── Product
│   ├── Business-Case.md              ← Rationale for pursuing an effort       [coming soon]
│   ├── PRD-Template.md               ← Requirements, test, and agent handoff
│   ├── Product-Chronicle.md          ← Living product intelligence: design principles, tradeoff rationale, customer understanding, competitive positioning, and internal narrative
│   └── Product-Design-Guide.md       ← Persistent UI/UX standards, interaction  [coming soon]
│                                        patterns, voice and tone, and accessibility
│                                        commitments — governs all PRDs that touch UI/UX
│
├── Rhythm and Calendar
│   └── Company-Calendar.md           ← Industry events, product releases,     [coming soon]
│                                        compliance dates, internal cadences,
│                                        and organizational milestones
│
├── Sales
│   ├── Go-to-Market.md               ← Channels, sales motion, target segment  [coming soon]
│   │                                    strategy, and pricing and packaging
│   └── Sales-Playbook.md             ← How deals are run: stages, discovery,   [coming soon]
│                                        objection handling, and competitive
│                                        positioning in a sales context
│
└── Systems and Data
    ├── Data-Dictionary.md            ← Authoritative definitions of key data   [coming soon]
    │                                    entities, their meaning, and where
    │                                    they live — prevents ambiguity across
    │                                    systems, teams, and AI agents
    ├── Data-Intelligence-Map.md      ← What useful insight lives in each       [coming soon]
    │                                    system, and how data flows and enriches
    │                                    across systems to answer business
    │                                    questions no single system can
    └── Systems-Registry.md           ← All platforms the organization uses,    [coming soon]
                                         with clear designation of which are
                                         Systems of Record for each data domain
```

---

## Contents

| File | Description | Governed By | Serves |
|---|---|---|---|
| Business-Case.md | Rationale for pursuing a product effort | Product strategy and executive approval | Product, Finance, Executive Leadership |
| Company-Calendar.md | Industry events, product releases, compliance dates, internal cadences, and organizational milestones | Organizational planning and external commitments | All teams |
| Competitive-Intelligence.md | Market landscape and competitor analysis — from formal profiles to informal usage mapping | Market research and ongoing competitive monitoring | Product, Marketing, Sales, Executive Leadership |
| Cost-and-Benefit-Framework.md | How the organization estimates effort and impact — living history of tradeoff characterization that informs every Business Case; scales from solo founder to enterprise | Finance and Product leadership | Product, Finance, Executive Leadership |
| [Customer-Personas.md](./Customer-Personas.md) | Research-based customer archetypes organized by use case | Research and market understanding | Product, Marketing, Sales |
| Data-Dictionary.md | Authoritative definitions of key data entities, their meaning, and where they live | Engineering and Data leadership | Engineering, Product, Finance, AI agents |
| Data-Intelligence-Map.md | What useful insight lives in each system, and how data flows and enriches across systems to answer business questions no single system can | Engineering, Data, and Product leadership | Product, Sales, Finance, Marketing, AI agents |
| [External-Stakeholders.md](./External-Stakeholders.md) | Strategic partners, vendors, and regulatory bodies | Contracts, agreements, terms of service, and compliance obligations | Sales, Legal, Finance, Executive Leadership |
| Financial-Reference.md | High-level financial context — revenue scale, materiality thresholds, and budgeting framework | Finance leadership | Executive Leadership, Product, Finance, Department heads |
| Go-to-Market.md | Channels, sales motion, target segment strategy, and pricing and packaging | Sales and Marketing leadership | Sales, Marketing, Product, Executive Leadership |
| [Institutional-Knowledge.md](./Institutional-Knowledge.md) | Living repository of organizational learning — decisions, lessons, constraints, and process | Collectively owned — fed from retros, reviews, and organizational feedback | All teams, new hires, AI agents |
| [Internal-Stakeholders.md](./Internal-Stakeholders.md) | Internal org structure and stakeholder areas of concern | Organizational structure and reporting authority | All internal teams |
| Key-Operational-Processes.md | Critical processes and how work actually gets done | Operations leadership | All teams, new hires, AI agents |
| [Key-Customers.md](./Key-Customers.md) | Named accounts classified by revenue tier and strategic importance | Executed agreements and terms of service | Sales, Executive Leadership, Product, Finance |
| Metrics-Framework.md | Standardized company-wide metrics, what can be measured, and Goodhart's Law guardrails distinguishing health indicators from targets | Finance, Data, and Product leadership | All teams, Finance, Executive Leadership, AI agents |
| [PRD-Template.md](./PRD-Template.md) | AI-ready Product Requirements Document | Product roadmap and initiative priority | Product, Engineering, QA, Compliance |
| [Product-Chronicle.md](./product/Product-Chronicle.md) | Living product intelligence — design principles, tradeoffs, customer understanding, and internal narrative | Product ownership and accumulated organizational learning | Product, Marketing, Sales, Engineering |
| Product-Design-Guide.md | Persistent UI/UX standards, interaction patterns, voice and tone, and accessibility commitments | Product and Design leadership | Product, Engineering, Design, QA |
| Sales-Playbook.md | How deals are run — stages, discovery, objection handling, and competitive positioning | Sales leadership | Sales, Marketing |
| [Strategic-Context.md](./Strategic-Context.md) | Organizational mission, vision, and living goals across time horizons | Collectively owned — maintained against current organizational direction | All teams, executive leadership, AI agents |
| Systems-Registry.md | All platforms the organization uses, with clear designation of Systems of Record per data domain | IT and Operations leadership | All teams, Engineering, Finance, AI agents |

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
