# AfriCompli UK — MVP Scope

This document defines the feature scope, development principles, and launch criteria for the AfriCompli UK Minimum Viable Product (MVP).

---

## Objective

Build and launch the AfriCompli UK MVP SaaS platform and AfriLaw™ beta mobile application within the first development year — then progressively enhance into a scalable, multi-jurisdiction RegTech platform.

The MVP validates three core assumptions:

1. Overseas and African-founded businesses need simplified SRS and ESG compliance guidance.
2. AI-assisted workflows can reduce the time and cost of preparing sustainability disclosure evidence.
3. A hybrid SaaS, mobile, and consultancy model can convert compliance complexity into recurring revenue.

---

## Development Principles

- Build the smallest commercially useful product first
- Validate with real users before scaling
- Prioritise data protection and cybersecurity from the outset
- Use modular architecture for future extension
- Combine AI automation with human review escalation
- Maintain clear version control throughout
- Avoid overengineering before product-market validation

---

## SaaS MVP Feature Scope

| Feature | Description | Priority |
|---|---|---|
| User registration and login | Secure account creation with MFA option | High |
| Business profile questionnaire | Captures sector, employee count, jurisdiction, supply-chain exposure | High |
| SRS/ESG applicability assessment | Determines direct or indirect reporting exposure | High |
| Compliance checklist generator | Converts obligations into practical user tasks | High |
| Evidence upload and repository | Stores supporting documents with tagging | High |
| Compliance heat map | Visual Red/Amber/Green display across 8 compliance areas | High |
| ESG readiness scoring | Quantified readiness percentage with risk rating | High |
| Draft report generation | Produces internal PDF readiness report | High |
| Consultant review workflow | Escalation pathway to human expert | Medium |
| Admin portal | Internal dashboard for AfriCompli team | Medium |
| Subscription billing | Supports Starter, Growth, Scale paid plans | Medium |

---

## AfriLaw™ Beta Feature Scope

| Feature | Description | Priority |
|---|---|---|
| Mobile login | Secure account access | High |
| AI Q&A | Plain-English compliance guidance on SRS/ESG questions | High |
| Checklist view | Mobile access to SaaS-generated checklist | High |
| Template library | Access to ESG policy, supplier questionnaire, data protection templates | Medium |
| Deadline reminders | Push notifications for key filing and evidence tasks | Medium |
| Consultant booking | In-app request for expert human support | Medium |

---

## Compliance Heat Map — 8 Dimensions

The heat map scores the business across these areas:

| Dimension | What Is Assessed |
|---|---|
| Governance and Board Oversight | ESG responsibility assigned at board level |
| Sustainability Strategy | Formal sustainability policy adopted |
| Climate Risk Identification | Climate risk register and scenario analysis exists |
| Energy and Carbon Data | Energy usage records collected and standardised |
| Social Impact and Workforce | Diversity policy and workforce metrics in place |
| Supplier ESG Data | Supplier sustainability questionnaire issued |
| Data Protection and Cybersecurity | Privacy controls and breach response plan |
| Funding Readiness | ESG evidence sufficient for green finance applications |

---

## Evidence Repository — Document Categories

| Category | Example Documents |
|---|---|
| Governance | Board minutes, ESG responsibility note |
| Climate Risk | Climate risk register, scenario assessment |
| Energy Usage | Utility data, emissions calculations |
| Supplier Data | Supplier ESG questionnaire responses |
| Diversity and Inclusion | D&I policy, workforce metrics |
| Data Protection | Privacy policy, breach response plan |
| Sustainability Strategy | Sustainability statement, policy document |
| Funding Evidence | Investor ESG pack, green loan documentation |

---

## Report Types

The report builder generates the following output types:

- ESG Readiness Summary
- SRS 1 General Disclosure Readiness
- SRS 2 Climate Disclosure Readiness
- Investor Funding Pack
- Supplier ESG Questionnaire Response

Export formats: **PDF · Excel · XML**

---

## Technology Stack

| Layer | Technology |
|---|---|
| Web frontend | React |
| Mobile app | Flutter |
| Backend | Node.js / Python |
| API | REST API (GraphQL planned for Phase 5) |
| Database | PostgreSQL |
| Document storage | Encrypted cloud object storage |
| AI layer | NLP orchestration, curated regulatory knowledge base |
| Cloud infrastructure | Microsoft Azure and/or Google Cloud (UK data residency) |
| Authentication | OAuth 2.0, MFA for privileged accounts |
| Reporting | PDF, Excel, structured data export |

---

## AI Design Approach

The AI layer is a **controlled compliance assistant** — not an unrestricted legal advice engine. It combines:

- Curated regulatory content (SRS 1 & 2, FCA rules, Companies Act, IFRS SDS)
- Structured rules engine with semantic obligation mapping
- Retrieval-based responses linked to source regulations
- Human-reviewed templates
- Confidence scoring
- Escalation to consultant review for complex or high-risk matters

All outputs carry clear disclaimers distinguishing compliance readiness guidance from legal advice, audit certification, or regulatory filing.

---

## Launch Criteria

AfriCompli will not proceed to full public launch until:

- Core MVP features are functional end-to-end
- Pilot users can complete onboarding and generate reports without assistance
- Critical bugs are resolved and security review is completed
- Privacy notice and subscription terms are published
- Payment system is tested
- Customer support workflow is active
- AI disclaimer and governance controls are implemented
- Basic penetration testing or external security review is complete
- Data Processing Agreement is in place

---

## Pilot Success Criteria (12-Week Pilot)

| Metric | Target |
|---|---|
| Pilot companies onboarded | 3–5 |
| Questionnaire completion rate | 70%+ |
| Checklist usefulness score | 8/10 average |
| Report usefulness score | 8/10 average |
| Users willing to continue post-pilot | 50%+ |
| Users willing to pay at least £99/month | 50%+ |
| Signed paid subscription or conditional commitment | At least 1 |
| Testimonial or anonymised case study | At least 1 |
