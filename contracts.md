# G&K Consultancy — Contract Templates

## Overview of Necessary Agreements
1. **Master Services Agreement (MSA)** – Governs all engagements (payment, IP, liability, governing law, etc.).  
2. **Statement of Work (SOW)** – Project-specific attachment (scope, timeline, deliverables, fee).  
3. **Mutual Non-Disclosure Agreement (MNDA)** – Protects confidential information exchanged before and during the project.  
4. **Source-Code Licensing & Retained-Rights Addendum** *(optional)* – Lets G&K keep a reference copy / reuse generic components while granting the client full ownership of bespoke code.  

> *A lawyer should review and adapt for Hawaii-specific tax language, regulated-industry terms, etc.*

---

# 1 Master Services Agreement (MSA)

### Template – 3-Month Fixed-Price Engagement  
*(replace bracketed placeholders as needed)*

**This Master Services Agreement** (“Agreement”) is made effective as of **[EFFECTIVE_DATE]** (“Effective Date”) by and between:

* **G&K Software Consultancy LLC**, a Texas limited-liability company with its principal place of business in Houston, Texas (“Consultant”), and  
* **[CLIENT_NAME]**, a [STATE] [ENTITY TYPE] with its principal place of business at [CLIENT_ADDRESS] (“Client”).

---

### 1  Scope of Services
- Consultant will provide the software-development and related professional services described in each mutually-executed Statement of Work (“SOW”).  
- Each SOW is governed by, and incorporated into, this Agreement.

### 2  Term & Termination
1. **Term** – This Agreement begins on the Effective Date and continues for three (3) months, unless extended or terminated earlier in writing.  
2. **Termination for Convenience** – Either party may terminate an SOW or this Agreement with fourteen (14) days’ written notice.  
3. **Termination for Cause** – Either party may terminate immediately if the other materially breaches and fails to cure within ten (10) days after written notice.

### 3  Fees, Expenses & Taxes
1. **Fixed Fee** – Client will pay a fixed fee of **USD [AMOUNT]** for the Services described in the SOW.  
2. **Payment Schedule** – Unless otherwise stated in the SOW, **100 % of the fee is due up-front** within five (5) business days of SOW execution; work begins once funds clear. *(Alternate schedule: 50 % up-front retainer, 50 % on acceptance.)*  
3. **Taxes** – Consultant is responsible for any federal, state, or local taxes arising from its income and operations (including any Hawaii GET). Consultant **will not invoice Client** for Hawaii GET, and Client is not required to reimburse or withhold such tax.  
4. **Late Payments** – Late balances accrue interest at 1 % per month or the maximum allowed by law, whichever is less.

### 4  Deliverables & Acceptance
1. Consultant will deliver the items listed in the SOW.  
2. Client will review each Deliverable within ten (10) business days. Absent a written rejection describing non-conformity, the Deliverable is deemed **accepted**.

### 5  Intellectual Property & Licenses
1. **Client Ownership** – Upon full payment, Consultant assigns to Client all rights in Deliverables created specifically for Client (“Project IP”).  
2. **Consultant Background IP** – Consultant retains ownership of its pre-existing tools, libraries, and generic components (“Background IP”). Consultant grants Client a perpetual, worldwide, royalty-free license to use Background IP only as incorporated into Deliverables.  
3. **Retained Copy** – Consultant may keep an archival copy of all code for record-keeping, portfolio, and internal reuse (excluding Client confidential data). Reuse of Project IP outside the Client’s project requires Client’s prior written consent unless addressed in a separate addendum.

### 6  Confidentiality
- Each party will safeguard Confidential Information with the same degree of care it uses to protect its own confidential materials (but no less than reasonable care) for five (5) years after disclosure.

### 7  Warranties & Disclaimers
1. Consultant warrants that the Services will be performed in a **professional, workmanlike manner** consistent with industry standards.  
2. **Disclaimer** – Except as expressly stated, Consultant makes **no other warranties**, whether express, implied, or statutory (including merchantability or fitness for a particular purpose).

### 8  Limitation of Liability
- Consultant’s total liability under this Agreement is limited to the **fees paid** by Client under the applicable SOW. Neither party is liable for consequential or punitive damages.

### 9  Indemnification
- Each party will indemnify and hold the other harmless from third-party claims arising from its own gross negligence or willful misconduct.

### 10  Independent Contractor
- Consultant is an **independent contractor**; nothing herein creates a partnership, joint venture, or employment relationship.

### 11  Governing Law & Dispute Resolution
- This Agreement is governed by the **laws of the State of Texas**.  
- Disputes will be resolved by **binding arbitration** in Houston, Texas under the Commercial Arbitration Rules of the AAA.

### 12  Miscellaneous
- Standard clauses on assignment, notices, force majeure, amendments, severability, and entire agreement.

---

## Schedule A — Statement of Work (SOW) Template

| Field | Value |
|-------|-------|
| **Project Name** | `[PROJECT_TITLE]` |
| **Project Duration** | `[START_DATE] – [END_DATE]` (target three-month engagement) |

### Objectives & Deliverables
- `[Goal 1 / Feature Area]`  
- `[Goal 2 / Feature Area]`  
- `Documentation / Knowledge-Transfer / Training`

### Progress & Communication
- Consultant will provide **monthly written status updates** summarizing progress, key decisions, and next steps.  
- Consultant is available via email/Slack for interim questions and ad-hoc updates throughout the project.  
- Live check-in calls or screen-share demos may be scheduled by mutual agreement as needed.

### Change Management
- Material changes (budget, deadlines, deliverables) require a written **Change Order** signed by both parties.  
- Minor task-level shifts within the overall objectives do **not** require a formal amendment.

### Fee & Payment Schedule
- **Fixed Fee:** USD `[AMOUNT]`  
- **Payment Trigger:** 100 % upfront (or alternate schedule as specified here)

### Acceptance Criteria
1. Deliverable meets the functional description under *Objectives & Deliverables*, **or**  
2. Client does not provide written notice of material non-conformity within ten (10) business days of delivery.

---

# 2 Mutual Non-Disclosure Agreement (MNDA)

**Effective Date:** `[DATE]`

**Parties:** G&K Software Consultancy LLC (“Party A”) and **[CLIENT_NAME]** (“Party B”)

1. **Purpose** – Explore and perform potential software-development projects.  
2. **Confidential Information** – Any non-public info disclosed, marked, or reasonably understood as confidential.  
3. **Obligations** – Use only for the Purpose; protect with reasonable care; limit access to personnel with a need to know.  
4. **Exclusions** – Information that is (i) publicly available, (ii) independently developed, (iii) lawfully received from a third party, or (iv) required to be disclosed by law.  
5. **Term** – Obligations last three (3) years from the Effective Date.  
6. **Return / Destruction** – Upon request, destroy or return Confidential Information.  
7. **No License** – Nothing herein grants a license except as explicitly stated.  
8. **Governing Law** – Texas law.  
9. **Publicity** – Consultant may identify Client by name and describe in *general* terms the nature of the Services in marketing materials, on its website, and during sales discussions, **provided no Client Confidential Information is disclosed**. Client may opt out at any time by written notice.

---

# 3 Source-Code Licensing & Retained-Rights Addendum (Optional)

**Reference:** MSA dated `[EFFECTIVE_DATE]` between Consultant and Client

1. **Grant Back to Consultant** – Client grants Consultant a non-exclusive, perpetual, royalty-free license to use, modify, and distribute technical components that are:  
   - (a) generic utilities,  
   - (b) tooling not specific to Client’s business logic, or  
   - (c) open-sourced by mutual agreement.  
   Consultant will **not** disclose Client Confidential Information.  
2. **Exclusions** – Business-specific logic, proprietary algorithms, and data schemas unique to Client remain **Client-owned**.  
3. **Attribution** – Consultant may list Client name/logo in marketing materials unless Client opts out in writing.

---

## Signature Blocks

| | |
|---|---|
| **Consultant**  <br>G&K Software Consultancy LLC  <br>By: **______________________________**  <br>Name: Gibson Martin  <br>Title: Co-Founder  <br>Date: __________ | **Client**  <br>[CLIENT_NAME]  <br>By: **______________________________**  <br>Name: ___________________________  <br>Title: ___________________________  <br>Date: __________ |

---

*End of Draft Templates*
