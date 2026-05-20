# AfriCompli UK — User Journey

This document describes the end-to-end journey a business takes through the AfriCompli platform — from first login to final report export.

The full visual flowchart is available as an SVG: [docs/images/user-journey.svg](images/user-journey.svg)

---

## Overview

AfriCompli converts a business's profile data into a compliance roadmap in under 60 seconds. The journey is designed to be completable without any specialist compliance knowledge.

---

## Step-by-Step Journey

### Step 1 — User Creates Account

The user registers with name, email, company, and role. MFA is offered at setup. The account is linked to a single business workspace.

---

### Step 2 — Business Profile Setup

The user completes a short onboarding form:

| Field | Options |
|---|---|
| Company name | Free text |
| Company type | Private limited, LLP, overseas branch, etc. |
| Country of ownership / control | Dropdown — country of registration or beneficial owner |
| UK establishment | Yes / No |
| Sector | Fintech, logistics, professional services, retail, etc. |
| Number of employees | Numeric |
| Annual turnover | Band selection |
| Supplies to UK-listed company? | Yes / No / Unsure |
| Receives ESG data requests from clients? | Yes / No |
| Operates in another jurisdiction? | Multi-select country list |

---

### Step 3 — Sector, Size, and Jurisdiction Questionnaire

A short follow-on questionnaire refines the applicability assessment:

- Does the business have a public-sector contract?
- Is it listed on any stock exchange?
- Is it a subsidiary of a UK-regulated or listed parent?
- Does it receive ESG or sustainability data requests from banks, investors, or procurement teams?

---

### Step 4 — AI Compliance Applicability Assessment

The AI engine assesses the business's SRS/ESG exposure status:

**Direct Exposure** — The business is, or is likely to be, directly subject to mandatory UK SRS 1 and/or SRS 2 reporting obligations.

**Indirect Exposure** — The business is not directly mandated but faces ESG data requests from its supply chain, lenders, investors, or procurement clients.

**No Current Exposure** — The business does not appear to be directly or indirectly exposed at this time, but monitoring is recommended.

*Example result for a Nigerian-founded fintech with 10 employees supplying a UK-regulated financial client:*

> "You are not currently assessed as directly subject to mandatory UK SRS reporting. However, you may be indirectly exposed through supply-chain ESG data requests from UK-listed clients, banks, investors, or public-sector tender processes."

---

### Step 5 — Personalised SRS and ESG Checklist

The platform generates a prioritised task list specific to the business's exposure type, sector, and size.

**Example checklist (Amber risk, indirect exposure):**

| Priority | Task | Status |
|---|---|---|
| High | Confirm board-level ESG owner | Not Started |
| High | Prepare sustainability policy | In Progress |
| High | Identify climate-related risks | Not Started |
| Medium | Record energy usage data | Not Started |
| Medium | Upload diversity policy | Complete |
| Medium | Map supplier ESG data | In Progress |
| Low | Prepare voluntary ESG statement | Not Started |

The checklist updates in real time as evidence is uploaded and tasks are completed.

---

### Step 6 — Evidence Upload and Document Tagging

The user uploads supporting documents to the evidence repository. The AI system assesses each document and assigns an evidence quality score.

| Category | Example Document | Status |
|---|---|---|
| Governance | Board minutes.pdf | Accepted |
| Climate Risk | (not uploaded) | Missing |
| Energy Usage | electricity-data.xlsx | Under Review |
| Supplier Data | supplier-form.docx | Under Review |
| Diversity and Inclusion | D&I policy.pdf | Accepted |
| Data Protection | privacy-policy.pdf | Accepted |

Missing evidence items are flagged with recommended actions.

---

### Step 7 — Compliance Heat Map

The platform generates a visual heat map across 8 compliance dimensions. Each dimension is scored Red, Amber, or Green with a percentage readiness score and recommended action.

The heat map drives the overall **ESG Readiness Score** (e.g., 42% / Amber) and the **Risk Level** indicator shown on the AfriLaw™ mobile home screen.

---

### Step 8 — ESG Readiness Report Generated

The platform generates a draft ESG Readiness Report including:

- Executive summary of applicability assessment
- Compliance heat map with scores and risk ratings
- Missing evidence items
- Recommended 90-day action plan
- Suggested funding opportunities and green loan eligibility

---

### Step 9 — User Requests Expert Review (Optional)

If the business:
- May be directly subject to mandatory reporting
- Is listed, regulated, or part of a regulated supply chain
- Operates across multiple jurisdictions
- Needs investor-grade or lender-facing outputs

…the user can escalate to a certified AfriCompli consultant for human review, sign-off, and enhanced reporting.

---

### Step 10 — Final Report Export

The user selects output format and report type, then downloads the finalised report.

**Report types:**
- ESG Readiness Summary
- SRS 1 General Disclosure Readiness
- SRS 2 Climate Disclosure Readiness
- Investor Funding Pack
- Supplier ESG Questionnaire Response

**Export formats:** PDF · Excel · XML

---

## AfriLaw™ Mobile Companion

In parallel to the SaaS journey, the user can access AfriLaw™ on mobile at any point:

- **Home screen** — ESG readiness score, risk level, quick actions, upcoming deadlines, template shortcuts
- **AI Chat** — Ask any compliance question in plain English; receive a structured answer with recommended next steps
- **Reminders** — Compliance alerts sorted by High / Medium / Low priority, synced with the SaaS dashboard
- **Template Library** — Download ESG Policy, Climate Risk Register, Supplier ESG Questionnaire, Data Protection Policy, Modern Slavery Statement, and more

AfriLaw™ is **offline-first** — fully functional without a stable internet connection, designed for diaspora founders balancing operations between the UK and overseas.
