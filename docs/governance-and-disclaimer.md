# AfriCompli UK — Governance and Disclaimer

This document covers AfriCompli UK's AI governance policy, legal disclaimer, data protection approach, and cybersecurity principles.

---

## Legal Disclaimer

AfriCompli UK is currently in early-stage product development and pilot validation. Nothing in this repository or on the AfriCompli platform constitutes a live or production system.

All product documentation, wireframes, business materials, and sample outputs in this repository are for **product planning and investor review purposes only**. They do not constitute:

- Legal advice
- Regulatory guidance
- Audit assurance
- Accounting or tax advice
- Financial advice
- Regulatory certification or filing

AfriCompli UK is **not yet a regulated entity**. Future platform outputs will carry appropriate disclaimers. Users of any future live platform should obtain qualified legal, accounting, or professional advice for statutory disclosures, regulated filings, or investor-facing documents that require professional sign-off.

---

## AI Governance Policy

### What AfriCompli AI Does

The AfriCompli AI layer is a **controlled compliance assistant** designed to help businesses understand their SRS and ESG obligations. It is not an autonomous legal advice engine.

| AI Use Case | Description |
|---|---|
| Obligation mapping | Maps UK regulatory obligations (SRS 1 & 2, FCA rules, Companies Act, ISSB standards) to the user's specific business profile |
| Checklist generation | Converts regulatory obligations into practical, prioritised tasks |
| ESG explanation | Explains compliance requirements in plain English |
| Evidence gap detection | Identifies missing documentation against expected evidence categories |
| Heat map scoring | Scores readiness across 8 compliance dimensions |
| Draft report generation | Produces an internal ESG readiness report for planning purposes |

### What AfriCompli AI Does Not Do

| Not Permitted | Reason |
|---|---|
| Provide final legal opinions | Requires qualified legal professional judgment |
| Issue statutory certifications | Requires regulated audit or assurance engagement |
| Make autonomous legal or financial decisions | Human oversight required |
| Submit regulatory filings without approval | User and consultant sign-off required |

---

## Human Oversight

Human review is built into the platform as a safeguard, not an afterthought. Consultant escalation is triggered where:

- The business may be directly subject to mandatory SRS reporting
- The business is listed, regulated, or part of a regulated supply chain
- The business operates across multiple jurisdictions with complex cross-border obligations
- User answers are inconsistent or incomplete
- The AI confidence score falls below the internal threshold
- The output may be used for investor, lender, regulator, or procurement purposes

All AI-generated reports are clearly labelled as system-generated, user-edited, consultant-reviewed, or finalised.

---

## Accuracy and Quality Controls

| Control | Mechanism |
|---|---|
| Curated content | AI is trained on structured, human-reviewed regulatory content only |
| Rules engine | Structured obligation mapping separate from language model inference |
| Validation | Sample companies used to test updated logic before release |
| Version control | Each update records the source regulation, change date, and affected modules |
| User feedback | User corrections and feedback are reviewed and used to improve outputs |

---

## Fairness

AfriCompli monitors its AI outputs to avoid producing results that systematically disadvantage users based on:

- Ethnicity or nationality
- First language
- Geographic location within the UK
- Business size
- Founder background

This is a standing commitment in our AI governance framework and will be subject to periodic review as the platform develops.

---

## Transparency

AfriCompli platform reports will clearly indicate:

- Whether an output was system-generated, user-edited, or consultant-reviewed
- The version of the compliance rules matrix used
- The date the assessment was generated
- The source regulations on which each obligation is based

---

## Data Protection Approach

### Our Commitments

AfriCompli UK adopts a **privacy-by-design and security-by-design** approach from product development through to commercial deployment.

We will not launch publicly until the following controls are in place:

- TLS encryption for all data in transit
- Encryption at rest for databases and file storage
- Multi-factor authentication for administrators and consultants
- Role-based access controls with workspace separation between clients
- Audit logging for all sensitive actions
- Secure password hashing
- Secure file upload scanning
- Backup and recovery processes
- Incident response procedure
- Privacy notice and customer terms published
- Data Processing Agreement (DPA) in place with all processors
- Basic penetration testing or external security review completed

### Data We Handle

| Data Category | Examples |
|---|---|
| Account data | Name, email, role, login credentials |
| Business profile data | Sector, employee count, jurisdiction, supply-chain relationships |
| Compliance data | ESG questionnaire responses, readiness scores, checklists |
| Evidence documents | Policies, board minutes, energy data, supplier forms |
| Payment data | Subscription tier, billing contact |
| Technical data | IP address, device type, access logs |

### GDPR Principles

| Principle | AfriCompli Control |
|---|---|
| Lawfulness, fairness, transparency | Privacy notice, customer terms, clear disclosures |
| Purpose limitation | Data used only for platform delivery, reporting, and billing |
| Data minimisation | Questionnaire limited to compliance-relevant fields only |
| Accuracy | Users can update profiles and evidence at any time |
| Storage limitation | Retention schedule applied to all data categories |
| Integrity and confidentiality | Encryption, MFA, access controls, logging |
| Accountability | Policies, DPIA, DPA, audit logs, supplier due diligence |

AfriCompli does not sell personal data.

---

## Cybersecurity

| Control Area | Measures |
|---|---|
| Technical | TLS, encryption at rest, MFA, role-based access, secure password hashing, audit logs, API rate limiting, input validation |
| Organisational | Staff confidentiality obligations, least-privilege access, security training, incident response plan, supplier due diligence |
| Testing | Penetration testing every six months once live; vulnerability scanning before launch |
| Incident response | Containment, assessment, breach notification within 72 hours where required, remediation, and lessons-learned review |

---

## Regulatory Monitoring and Update Process

AfriCompli monitors the following sources continuously for regulatory changes that affect platform outputs:

- UK Government and BEIS publications
- Financial Conduct Authority (FCA) guidance
- Financial Reporting Council (FRC)
- Companies House
- ISSB and IFRS Foundation
- EU CSRD updates (for future expansion)

When a change is identified:

1. The change is assessed for impact on applicability rules, reporting content, evidence requirements, or deadlines
2. Legal interpretation is produced in plain-English internal guidance
3. The compliance rules matrix, questionnaires, scoring logic, and templates are updated
4. Updates are version-controlled with source, date, and affected module recorded
5. Affected clients are notified via dashboard alerts, AfriLaw™ push notifications, or email
6. Updated logic is tested against sample companies before release
