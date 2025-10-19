# Agreement Documents Repository

**Repository for Hijra Bank partnership and service agreements**  
**Last Updated:** October 19, 2025

---

## 📋 Table of Contents

- [Overview](#overview)
- [Agreement Files](#agreement-files)
- [Agreement Relationships](#agreement-relationships)
- [Version History](#version-history)
- [How to Report Issues](#how-to-report-issues)
- [Contact Information](#contact-information)

---

## Overview

This repository contains legally binding agreements between Hijra Bank S.C. (Ethiopia) and various technology and service providers. These agreements form an integrated ecosystem for digital wallet services, remittance processing, and financial technology operations.

**Key Partnerships:**
- **CICO Financial Technologies** - Digital Wallet Platform Provider (SaaS)
- **Hawilpay Inc.** - International Remittance Platform Partner
- **Consortium Partners** - [If applicable]

---

## Agreement Files

### 1. **CICO HijraBank SLA.md**
**Full Title:** Software Utilization Support & Maintenance License Agreement  
**Parties:** CICO Financial Technologies LLC ↔ Hijra Bank S.C.  
**Date:** September 20, 2025  
**Status:** ✅ Active

**Summary:**  
SaaS license agreement for CICO's multi-currency digital wallet and operator management platform, co-branded as "CICO - HijraBank". Includes hosting, support, maintenance, and revenue sharing (50/10/40 model).

**Key Terms:**
- Platform: Digital wallet, operator management, multi-channel access
- Pricing: Tiered monthly fees (ETB 25K - 900K+) based on registered users
- Revenue Share: CICO 50%, Operators 10%, Bank 40% (on Net fees)
- Initial Capacity: 1M registered users
- Term: 3 years initial, auto-renew annually

**Key Sections:**
- Section 2.2: System functionality (multi-currency wallet)
- Section 2.8: Co-branding as "CICO - HijraBank"
- Section 3.1: Hybrid fee model (AMS + Revenue Share)
- Section 7.7: Data residency (Ethiopia only)
- Annex F: Detailed pricing tiers
- Annex I: Pass-through cost structure

---

### 2. **Hawilpay HijraBank RSA.md**
**Full Title:** Remittance Platform and Services Agreement  
**Parties:** Hawilpay Inc. (USA) ↔ Hijra Bank S.C. (Ethiopia)  
**Date:** September 20, 2025  
**Status:** ✅ Active

**Summary:**  
Partnership agreement for international remittance services (USA → Ethiopia corridor). Hijra Bank serves as non-exclusive payout partner for Hawilpay platform, with integration to CICO - HijraBank digital wallet for wallet-based payouts.

**Key Terms:**
- Bank Obligations: 30% interest-free loan, 0% transaction fees, marketing costs
- Payout Methods: Cash pickup, bank account, CICO wallet (USD or ETB)
- FX Control: Bank sets all exchange rates, keeps 100% of FX spread
- Settlement: T+2 (48 hours) in USD
- Term: 5 years initial, auto-renew annually
- Termination: Bank can exit if volume < $50K/month for 6 months

**Key Sections:**
- Section 2.7: CICO - HijraBank wallet integration (multi-currency)
- Section 3: Financial covenants (loans, fees, marketing)
- Section 27: FX pricing authority and transparency
- Section 27.3: Multi-bank competitive model (non-exclusive)
- Annex A: Service Level Agreement (99.8% uptime)

---

### 3. **CICO SaaS License Pricing.md**
**Full Title:** CICO Digital Wallet & Operator Management Platform - Pricing Schedule  
**Parties:** CICO Financial Technologies LLC ↔ Hijra Bank S.C.  
**Date:** September 20, 2025  
**Status:** ✅ Active (Annex to CICO SLA)

**Summary:**  
Detailed pricing structure for CICO platform services. Defines one-time fees, monthly managed fees, revenue sharing model, pass-through costs, and included services.

**Pricing Overview:**
- **One-Time:** ETB 0 setup (up to 1M users), ETB 5/user above 1M
- **Monthly Managed Fee:** ETB 25K - 900K+ (tiered by registered users)
- **Revenue Share:** 50/10/40 split on Net Chargeable Transaction Fees
- **Custom Development:** ETB 5,000 per man-day
- **Payment Terms:** Monthly fee in advance (Net 30), Revenue share in arrears (15th day)

**Services Included:**
- Hosting, security, backups, disaster recovery
- L1/L2/L3 support (24/7)
- Customer and operator onboarding
- Marketing operations (media spend is pass-through)
- System upgrades and maintenance

---

### 4. **Consortium Partnership Agreement.md**
**Full Title:** [To be determined]  
**Parties:** [To be determined]  
**Date:** [To be determined]  
**Status:** 📝 Draft / ⏳ Pending

**Summary:**  
[Placeholder for consortium partnership details]

---

## Agreement Relationships

### Integration Architecture

```
┌─────────────────────────────────────────────────────────┐
│                    HIJRA BANK S.C.                      │
│                  (Licensed Bank - Ethiopia)              │
└─────────────────┬─────────────────┬─────────────────────┘
                  │                 │
        ┌─────────▼─────────┐   ┌──▼──────────────────┐
        │   CICO SLA        │   │  Hawilpay RSA       │
        │   (Platform)      │   │  (Remittances)      │
        └─────────┬─────────┘   └──┬──────────────────┘
                  │                 │
                  │    Integration  │
                  │   Referenced in │
                  │   Both Agreements│
                  │                 │
        ┌─────────▼─────────────────▼─────────────────┐
        │   CICO - HijraBank Digital Wallet           │
        │   • Multi-currency (USD, ETB)               │
        │   • Receives Hawilpay remittance payouts    │
        │   • Bank controls FX rates (100% spread)    │
        └─────────────────────────────────────────────┘
```

### Cross-References

| **Provision** | **CICO SLA** | **Hawilpay RSA** | **Alignment** |
|---------------|--------------|------------------|---------------|
| **Co-Branding** | Section 2.8: "CICO - HijraBank" | Section 2.7(a): References CICO SLA | ✅ Consistent |
| **FX Control** | Bank has pricing authority | Section 27.1: Bank sets all FX rates | ✅ Consistent |
| **FX Revenue** | FX spread NOT in revenue share | Section 27.1(c): Bank keeps 100% | ✅ Aligned |
| **Wallet Integration** | Section 2.2: Remittance partners | Section 2.7: CICO wallet payouts | ✅ Linked |
| **Multi-Currency** | Multi-currency wallet support | USD or ETB wallet credits | ✅ Supported |

---

## Version History

### Current Versions

| **Agreement** | **Version** | **Date** | **Status** |
|--------------|-------------|----------|-----------|
| CICO HijraBank SLA | 1.0 | Sept 20, 2025 | Active |
| Hawilpay HijraBank RSA | 1.0 | Sept 20, 2025 | Active |
| CICO SaaS Pricing | 1.0 | Sept 20, 2025 | Active |
| Consortium Agreement | Draft | TBD | Pending |

### Recent Updates (October 19, 2025)

#### CICO SLA:
- ✅ Added Section 2.8: Co-branding provisions ("CICO - HijraBank")
- ✅ Added Hawilpay integration reference in Section 2.2

#### Hawilpay RSA:
- ✅ Added Section 2.7: CICO - HijraBank wallet integration
- ✅ Enhanced Section 27.1: FX control and CICO SLA consistency
- ✅ Updated "Payout Location" definition to include wallet credits
- ✅ Added Section 27.3: Multi-bank competitive model (non-exclusive)
- ✅ Fixed cross-reference error in Section 14.3(a) (15.2 → 16.2)

---

## How to Report Issues

### Issue Categories

When creating an issue, please use one of the following categories:

1. **🔴 Legal Issue** - Contractual conflicts, ambiguities, or missing provisions
2. **💰 Financial Issue** - Pricing disputes, payment terms, fee calculations
3. **🔧 Technical Issue** - Integration problems, API issues, system compatibility
4. **📊 Compliance Issue** - Regulatory concerns, NBE requirements, data protection
5. **📝 Documentation Issue** - Errors, typos, unclear language
6. **🤝 Cross-Agreement Issue** - Conflicts between multiple agreements

---

### Issue Template

When creating an issue, please provide the following information:

```markdown
## Issue Summary
[One sentence description of the issue]

## Category
[Select: Legal | Financial | Technical | Compliance | Documentation | Cross-Agreement]

## Priority
[Select: 🔴 Critical | 🟡 High | 🟢 Medium | ⚪ Low]

## Affected Agreement(s)
- [ ] CICO HijraBank SLA
- [ ] Hawilpay HijraBank RSA
- [ ] CICO SaaS Pricing
- [ ] Consortium Partnership Agreement

## Affected Section(s)
- Agreement: [Name]
- Section: [Number and Title]
- Line Numbers: [If applicable]

## Issue Description
[Detailed description of the issue]

### Current State
[What the agreement currently says]

### Problem
[Why this is an issue - conflict, ambiguity, missing provision, etc.]

### Impact
[Business, legal, or operational impact]

## Proposed Resolution
[How to fix the issue]

### Recommended Change
[Specific language to add/modify/remove]

### Alternative Options
[Other possible solutions, if any]

## Related Issues
[Link to related issues, if any]

## Additional Context
[Any other relevant information, background, or references]
```

---

### Example Issues

#### Example 1: Legal Conflict
```markdown
## Issue Summary
Conflict between CICO revenue share and Hawilpay FX control

## Category
Cross-Agreement

## Priority
🟡 High

## Affected Agreement(s)
- [x] CICO HijraBank SLA
- [x] Hawilpay HijraBank RSA

## Affected Section(s)
- Agreement: CICO SLA
- Section: 3.1(b) - Revenue Share Model
- Agreement: Hawilpay RSA
- Section: 27.1 - FX Exchange Rate Responsibility

## Issue Description
Potential ambiguity about whether FX spread earned on wallet-based 
remittance payouts is subject to CICO's 50/10/40 revenue share.

### Current State
- CICO SLA: 50/10/40 split on "Net Chargeable Transaction Fees"
- Hawilpay RSA: Bank keeps 100% of FX spread

### Problem
If recipient receives USD in CICO wallet and converts to ETB later, 
unclear if FX spread is "transaction fee" subject to CICO revenue share.

### Impact
Millions in potential revenue allocation disputes.

## Proposed Resolution
Add clarification that FX spread is NOT a "transaction fee" and is 
excluded from CICO revenue share model.

### Recommended Change
Added Section 27.1(d) in Hawilpay RSA clarifying FX spread exclusion
from CICO revenue share. ✅ RESOLVED
```

---

#### Example 2: Financial Discrepancy
```markdown
## Issue Summary
Marketing cost cap missing in Hawilpay RSA Section 3.3

## Category
Financial

## Priority
🟡 High

## Affected Agreement(s)
- [x] Hawilpay HijraBank RSA

## Affected Section(s)
- Agreement: Hawilpay RSA
- Section: 3.3 - Client Incentives and Marketing Finance

## Issue Description
Bank commits to "fully finance" marketing costs but no annual cap defined.

### Current State
"All such campaigns...shall be mutually agreed upon in writing by the 
Parties, but the financial obligation for their execution shall rest 
solely with Hijrabank."

### Problem
"Mutually agreed" is vague. No explicit protection against unlimited 
marketing costs.

### Impact
Bank could be pressured into excessive marketing spend.

## Proposed Resolution
DECISION: Keep as-is. "Mutually agreed in writing" provides sufficient 
protection without artificial cap that could limit growth. 
✅ RESOLVED - No change needed
```

---

## Quick Reference Guide

### Key Financial Obligations

| **Obligation** | **Source** | **Amount/Terms** |
|----------------|-----------|------------------|
| CICO Monthly Fee | CICO SLA 3.1(a) | ETB 25K - 900K+ (tiered) |
| CICO Revenue Share | CICO SLA 3.1(b) | 50% to CICO, 10% operators, 40% Bank |
| Hawilpay Operational Loan | Hawilpay RSA 3.4 | Up to 30% of inflow, 0% interest |
| Hawilpay Transaction Fees | Hawilpay RSA 3.2 | Bank pays 100% (0% to users) |
| Hawilpay Marketing | Hawilpay RSA 3.3 | Bank funds, mutually agreed |
| FX Spread Revenue | Both agreements | 100% to Bank (not shared) |

### Key Performance Metrics

| **Metric** | **Source** | **Target/Requirement** |
|-----------|-----------|------------------------|
| CICO Platform Uptime | CICO SLA Annex A | 99.8% monthly |
| Hawilpay API Uptime | Hawilpay RSA Annex A | 99.8% monthly |
| Settlement Timeline | Hawilpay RSA 3.6(c) | T+2 (48 hours) |
| Payout Processing | Hawilpay RSA Annex A | Real-time confirmation |

### Key Contacts

| **Party** | **Agreement** | **Contact Type** |
|-----------|--------------|------------------|
| CICO Financial Technologies | CICO SLA | Technology Provider |
| Hawilpay Inc. | Hawilpay RSA | Remittance Partner |
| Hijra Bank Legal | All | Internal Counsel |
| Hijra Bank Treasury | Hawilpay RSA | FX & Settlement |
| Hijra Bank IT | Both | Integration Lead |

---

## Document Maintenance

### Owners
- **Primary Owner:** Hijra Bank Legal Department
- **Technical Owner:** Hijra Bank IT Department
- **Financial Owner:** Hijra Bank Treasury Department

### Review Schedule
- **Quarterly:** Review for operational alignment
- **Annual:** Comprehensive legal and financial review
- **Ad-hoc:** Upon material changes to business or regulations

### Amendment Process
1. Identify issue or required change
2. Create issue using template above
3. Legal review and risk assessment
4. Business impact analysis
5. Negotiate with counterparty
6. Execute amendment
7. Update repository and version history

---

## Notes

- All agreements dated September 20, 2025
- All agreements use Ethiopian Birr (ETB) and US Dollars (USD)
- All agreements subject to Ethiopian law and NBE regulations
- Data must be hosted in Ethiopia (per CICO SLA 2.4 and 7.7)
- All agreements contain confidentiality provisions

---

## License & Confidentiality

⚠️ **CONFIDENTIAL - INTERNAL USE ONLY**

These documents contain proprietary and confidential information. 
Unauthorized disclosure, reproduction, or distribution is strictly prohibited.

**Classification:** Confidential  
**Distribution:** Authorized Hijra Bank personnel only  
**Retention:** Per Hijra Bank document retention policy

---

*For questions or issues, please create an issue using the template above or contact the Legal Department.*
