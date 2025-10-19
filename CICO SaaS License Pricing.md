# **CICO MANAGED PLATFORM & OPERATIONS FEES**

## **1\) Managed Model (Scope Snapshot)**

**CICO provides:** fully hosted & managed Digital Wallet & Operator Management Platform, plus day‑to‑day **customer support**, **marketing operations**, and **user/operator onboarding**.

**Bank retains:** regulatory compliance & licensing, AML/CFT decisions, product/fee approvals, brand/policy oversight, and L3 complaint adjudication. CICO executes operations under Bank oversight per SLA/Scope.

## **2\) One‑Time Fees**

**System Setup & SaaS License (incl. implementation, tenant provisioning, capacity up to 1,000,000 registered users):** **ETB 0.00**.

**Additional License Capacity:** Above 1,000,000 registered users, one‑time top‑up **ETB 5.00 per additional user**.

**License Warranty:** First **12 months** from Go-Live covers core software defects and bugs (per SLA). This warranty covers defect resolution only, not operational services.

## **3\) Monthly Managed Fee (SaaS \+ Operations)**

*(Also referred to as "AMS Fee" or "Application Maintenance Services Fee" in the SLA)*

*Covers hosting, security/monitoring, platform maintenance & upgrades, L1/L2/L3 helpdesk, incident response, environment management, **customer support ops**, **operator/user onboarding ops**, and **marketing ops & campaign execution** (media spend excluded; see §5).*

**Payment Start:** Monthly Managed Fee is payable starting from **Go-Live (Month 1)**.

**Tier basis:** total **Registered Users** at month-end (all wallet accounts created, regardless of activity status). 

| Registered Users | Monthly Managed Fee (ETB) |
| ----- | ----- |
| 0 – 5,000 | 25,000 |
| 5,001 – 10,000 | 35,000 |
| 10,001 – 25,000 | 55,000 |
| 25,001 – 50,000 | 70,000 |
| 50,001 – 100,000 | 85,000 |
| 100,001 – 250,000 | 150,000 |
| 250,001 – 500,000 | 275,000 |
| 500,001 – 1,000,000 | 450,000 |
| 1,000,001 – 1,500,000 | 675,000 |
| 1,500,001 – 2,000,000 | 900,000 |
| \> 2,000,000 | **Custom** (not less than **0.90 ETB/user/month**) |

## **4\) Services Included in the Managed Fee**

* **Hosting & Security:** Ethiopia‑resident hosting, 24/7 monitoring, backups/DR, patching.

* **Application Maintenance:** bug fixes, patches, minor enhancements, version upgrades.

* **Support Operations:** L1/L2/L3 helpdesk (voice/email/chat), incident mgmt., RCA, knowledge base & FAQs.

* **Customer Ops:** onboarding/KYC workflow execution & education.

* **Operator/Agent Ops:** onboarding & training coordination, field playbooks, performance nudges.

* **Marketing Ops:** campaign setup/execution, CRM segments, in‑app promos, field activations (*media spend is pass‑through*).

* **Reporting & Governance:** KPI dashboards, monthly service review, quarterly roadmap, **quarterly marketing plans** (campaigns, budgets, calendar for Bank approval), monthly marketing performance reports.

  ## **5\) Revenue Share & Pass‑Through**

**Revenue Sharing on Net Chargeable Transaction Fees:**

* **CICO:** 50%

* **Operator Incentive:** 10% (allocated in real time)

* **Bank:** 40%

**Pass‑Through (deducted first to arrive at Net):** national/payment switch fees; gateway MDR/scheme & dispute fees; SMS/USSD/OTT costs; KYC/AML/biometric verifications; FX/remittance corridor fees; transaction‑linked statutory levies/taxes; **media buying** for Bank‑approved marketing.

**Ineligible for pass‑through (included in Managed Fee):** core hosting, core application maintenance, and the staff running managed operations.

**Computation:** **Net \= Gross Fees – Pass‑Through** → apply **50/10/40** split on **Net**.

*Example:* Gross ETB 10.00 – Pass‑Through ETB 2.00 \= **Net ETB 8.00** → CICO 4.00, Operator 0.80, Bank 3.20.

## **6\) Changes & Custom Work**

* Minor configuration is included.

* **Custom development / integrations** beyond scope: **ETB 5,000 per man‑day** (or fixed price) via Change Request with BRS.

* New third‑party providers not in scope: priced via CR.

  ## **7\) Payment & Settlement**

* **Managed Fee:** invoiced **monthly in advance**; due **Net 30 days**.

* **Revenue Share:** real‑time allocation in platform, or **monthly in arrears** with statement by the **15th business day**.

* **Pass‑Through:** itemized monthly with vendor references; deducted before revenue split.

* **Currency:** ETB to CICO’s designated account.

  ## **8\) Quick Sheet Formulas (for Excel/Sheets)**

* **Tier Fee:**  
   `=IFS(A<=5000,25000, A<=10000,35000, A<=25000,55000, A<=50000,70000, A<=100000,85000, A<=250000,150000, A<=500000,275000, A<=1000000,450000, A<=1500000,675000, A<=2000000,900000, TRUE, "Custom")`

* **Net Fees:**  
   `=Gross_Fees - Pass_Through`

* **Revenue Split:**  
   `CICO = Net_Fees*0.50`  
   `Operator = Net_Fees*0.10`  
   `Bank = Net_Fees*0.40`

  ### **Notes**

* "Registered User" = any wallet account created in the System, regardless of transaction activity or balance status. Billing is based on total registered users at month-end, not just active ones.

* "Active Subscriber" = wallet that transacted or held positive balance during the billing month (for reporting and performance metrics only, not for billing).

* This Pricing Sheet, when incorporated into a Service Level Agreement (SLA) or contract, forms part of the commercial terms as specified in the SLA's precedence provisions. For standalone commercial discussions, this Pricing Sheet represents CICO's standard commercial terms.
