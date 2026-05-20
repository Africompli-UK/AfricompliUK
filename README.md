# AfriCompli UK

**AI-powered SRS and ESG compliance for overseas businesses operating in the UK.**

> Compliance Simplified. Growth Amplified.

[![Stage](https://img.shields.io/badge/stage-MVP%20development-gold)](#roadmap)
[![Website](https://img.shields.io/badge/website-africompli.co.uk-1A6B4A)](https://www.africompli.co.uk)
[![Licence](https://img.shields.io/badge/licence-proprietary-lightgrey)](#disclaimer)

---

## What AfriCompli UK Is

AfriCompli UK is the UK's first AI-driven compliance SaaS platform and mobile application purpose-built for **African-founded and overseas businesses** navigating UK sustainability reporting requirements.

As of **1 January 2027**, compliance with the UK Sustainability Reporting Standards (SRS 1 & 2) becomes mandatory. Every regulated business and SME linked to UK-listed entities must make formal sustainability disclosures. For overseas businesses — many of which are agile but under-resourced — this creates a serious barrier.

AfriCompli solves this by combining:

- AI-assisted SRS and ESG applicability assessment
- Automated compliance checklists and evidence workflows
- Colour-coded compliance heat maps and readiness scoring
- Filing-ready report generation (PDF, Excel, XML)
- A mobile law companion (AfriLaw™) for on-the-go legal guidance
- Human consultant review for complex or high-stakes filings

---

## The Problem

| Pain Point | Impact |
|---|---|
| SRS/ESG rules are written in technical legalese | Non-lawyers cannot interpret what applies to them |
| No affordable specialist advisor for overseas founders | Overseas SMEs pay bespoke law firm rates or go without |
| ESG non-compliance blocks green finance access | Founders miss out on green loans, grants, and investor rounds |
| No integrated tool for cross-border reporting | Businesses with dual UK/Africa operations face double complexity |

**Key market data:**
- 78% of African-founded SMEs lack internal compliance capacity *(Tech Nation, 2023)*
- 64% believe this limits their access to funding
- 8 in 10 founders would adopt an automated tool with culturally relevant support
- Up to **2,186 overseas companies** face mandatory SRS reporting by January 2027

---

## Product Flow

A business signs up and completes a short profile. AfriCompli's AI engine then:

```
1. User creates account
         ↓
2. Business profile setup
   (sector, size, jurisdiction, supply chain links)
         ↓
3. Sector, size and jurisdiction questionnaire
         ↓
4. AI compliance applicability assessment
   (direct SRS exposure or indirect supply-chain exposure)
         ↓
5. Personalised SRS and ESG checklist generated
         ↓
6. Evidence upload and document tagging
         ↓
7. Compliance heat map generated
   (Red / Amber / Green across 8 compliance dimensions)
         ↓
8. ESG readiness report generated
         ↓
9. User requests expert consultant review (optional)
         ↓
10. Final report export: PDF, Excel, or XML
```

See the full [User Journey diagram](docs/images/user-journey.svg) and [user-journey.md](docs/user-journey.md).

---

## MVP Scope

The AfriCompli MVP covers the following features:

| Feature | Purpose | Priority |
|---|---|---|
| User registration and login | Secure account creation | High |
| Business profile questionnaire | Capture sector, size, jurisdiction | High |
| Applicability assessment | Determine direct or indirect SRS/ESG exposure | High |
| Compliance checklist generator | Produce user-specific obligation tasks | High |
| Evidence upload and repository | Store supporting documents | High |
| Compliance heat map | Visual Red/Amber/Green readiness display | High |
| ESG readiness report builder | Generate draft PDF/Excel/XML report | High |
| AfriLaw™ mobile integration | Mobile legal prompts, templates, alerts | High |
| Admin portal | Internal team management and review | Medium |
| Subscription billing | Support Starter/Growth/Scale paid plans | Medium |
| Consultant review workflow | Human expert escalation | Medium |

Full details in [docs/mvp-scope.md](docs/mvp-scope.md).

---

## Roadmap

| Phase | Timeline | Key Deliverables |
|---|---|---|
| **Phase 1 — Discovery** | Months 1–2 | Product requirements, compliance rules matrix, wireframes, pilot shortlist |
| **Phase 2 — MVP Build** | Months 3–5 | Authentication, questionnaire, checklist, heat map, evidence upload, report builder |
| **Phase 3 — Pilot** | Months 6–7 | 3–5 pilot clients, feedback report, pricing validation, case studies |
| **Phase 4 — Public Launch** | Months 8–12 | Paid SaaS subscriptions, onboarding, consultancy terms live |
| **Phase 5 — Scale** | Year 2 | API hub, advanced reporting, partner portal, multilingual AfriLaw beta |
| **Phase 6 — International** | Year 3 | Nigeria, Ghana, Kenya localisation; EU CSRD alignment; UAE/Singapore partnerships |

Full roadmap in [docs/roadmap.md](docs/roadmap.md).

---

## Technology Stack

| Layer | Technology |
|---|---|
| Web frontend | React |
| Mobile app | Flutter |
| Backend | Node.js / Python |
| API | REST (GraphQL planned) |
| Database | PostgreSQL |
| Cloud | Microsoft Azure + Google Cloud (UK data residency) |
| AI layer | NLP engine with curated regulatory knowledge base |
| Security | AES-256 encryption, MFA, OAuth 2.0, GDPR-compliant |
| Reporting | PDF, Excel, XML export |

---

## Repository Structure

```
AfricompliUK/
├── README.md                        ← This file
├── docs/
│   ├── product-overview.md          ← What AfriCompli is, in full
│   ├── mvp-scope.md                 ← MVP feature scope and launch criteria
│   ├── user-journey.md              ← Step-by-step user journey
│   ├── roadmap.md                   ← Development and business roadmap
│   ├── governance-and-disclaimer.md ← AI governance, legal disclaimers, GDPR
│   └── images/
│       ├── user-journey.svg         ← Visual user journey flowchart
│       └── logo variants            ← Platform hero screenshot
├── design/
│   ├── screenshots/                 ← MVP screen exports
│   └── wireframes/                  ← AfriLaw and SaaS wireframe exports
└── research/
    └── market-summary.md            ← Market size, drivers, competitor context
```

---

## Contact and Website

**Website:** [www.africompli.co.uk](https://www.africompli.co.uk)  
**CEO:** Ebube Akpamgbo — [ebube@africompli.co.uk](mailto:ebube@africompli.co.uk)  
**CTO:** Jeremiah Anachuna — [jeremiah@africompli.co.uk](mailto:jeremiah@africompli.co.uk)

---

## Disclaimer

AfriCompli UK is currently in **early-stage product development and pilot validation**. Nothing in this repository constitutes a live or production system.

All product documentation, wireframes, and business materials are for product planning and investor review purposes only. They do not constitute legal advice, regulatory guidance, audit assurance, or any form of professional certification.

AfriCompli UK is not yet a regulated entity. Any future platform outputs will carry appropriate legal disclaimers and will not substitute for qualified legal or professional advice.

See [docs/governance-and-disclaimer.md](docs/governance-and-disclaimer.md) for the full AI governance and legal disclaimer policy.
