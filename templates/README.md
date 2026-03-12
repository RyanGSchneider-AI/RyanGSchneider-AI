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
├── Product Development
│   └── PRD-Template.md              ← Requirements, test, and agent handoff
│
├── People & Relationships
│   ├── Internal-Stakeholders.md     ← Internal org structure and stakeholder concerns
│   │   Governed by: Organizational structure and reporting authority
│   │
│   └── External-Stakeholders.md     ← Strategic partners, vendors, and regulatory bodies
│       Governed by: Contracts, agreements, terms of service, and compliance obligations
│
├── Market & Customer
│   ├── Key-Customers.md             ← Named accounts with strategic importance
│   ├── Customer-Personas.md         ← Research-based archetypes organized by use case
│   └── Competitive Intelligence      ← coming soon
│
├── Institutional Knowledge
│   └── Institutional-Knowledge.md   ← Living repository of decisions, lessons, constraints, and process
│
└── Strategic Context
    └── Strategic-Context.md         ← Living organizational goals, reasoning, and initiative connections
```

---

## Contents

| File | Description | Governed By | Serves |
|---|---|---|---|
| [PRD-Template.md](./PRD-Template.md) | AI-ready Product Requirements Document | Product roadmap and initiative priority | Product, Engineering, QA, Compliance |
| [Internal-Stakeholders.md](./Internal-Stakeholders.md) | Internal org structure and stakeholder areas of concern | Organizational structure and reporting authority | All internal teams |
| [External-Stakeholders.md](./External-Stakeholders.md) | Strategic partners, vendors, and regulatory bodies | Contracts, agreements, terms of service, and compliance obligations | Sales, Legal, Finance, Executive Leadership |
| [Key-Customers.md](./Key-Customers.md) | Named accounts classified by revenue tier and strategic importance | Executed agreements and terms of service | Sales, Executive Leadership, Product, Finance |
| [Customer-Personas.md](./Customer-Personas.md) | Research-based customer archetypes organized by use case | Research and market understanding | Product, Marketing, Sales |
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
every document.

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
5. Link to related artifacts in Section 0 (Connected Artifacts) as they are created

---

## This Framework is Evolving

Templates are added and refined as they are applied to real work. If you use
one and find a gap, open an issue or submit a PR.
