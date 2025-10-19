# Agreement Documents Repository

**Repository for Hijra Bank partnership and service agreements**  
**Last Updated:** October 19, 2025

---

## 📋 Table of Contents

- [Overview](#overview)
- [Agreement Files](#agreement-files)
- [Agreement Relationships](#agreement-relationships)
- [Version History](#version-history)

---

## Overview

This repository contains legally binding agreements between Hijra Bank S.C. (Ethiopia) and various technology and service providers. These agreements form an integrated ecosystem for digital wallet services, remittance processing, and financial technology operations.

**Key Partnerships:**
- **CICO Financial Technologies** - Digital Wallet Platform Provider (SaaS)
- **Hawilpay Inc.** - International Remittance Platform Partner
- **Consortium Partners** - CICO & HijraBank

---

## Agreement Files

### 1. **CICO HijraBank SLA.md**
**Full Title:** Software Utilization Support & Maintenance License Agreement  
**Parties:** CICO Financial Technologies PLC ↔ Hijra Bank S.C.  
**Date:** September 20, 2025  
**Status:** Active

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
**Status:** Active

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
**Parties:** CICO Financial Technologies PLC ↔ Hijra Bank S.C.  
**Date:** September 20, 2025  
**Status:** Active (Annex to CICO SLA)

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
**Full Title:** Consortium Partnership Agreement  
**Parties:** CICO Financial Technologies PLC ↔ Hijra Bank S.C.  
**Date:** July 20, 2025  
**Status:** Active

**Summary:**  
Consortium framework agreement establishing CICO as lead implementer and Hijra Bank as banking partner for joint RFQ/RFP/TOR responses and project execution. Defines roles, profit sharing (50/50 during implementation), fund flow, and governance for consortium projects.

**Key Terms:**
- CICO Role: Lead implementer, consortium manager, technical provider
- Bank Role: Regulated banking partner, regulatory approvals, infrastructure
- Profit Sharing: 50% CICO, 50% Bank (implementation phase only)
- Fund Flow: Revenues to Bank account → Bank transfers to CICO operating account
- Post-Project: No revenue sharing; continued IP use requires separate agreement
- Background IP: Utilizes pre-existing platforms (HalalPay, Soukify, etc.)

**Key Sections:**
- Section 2: Roles and responsibilities (CICO leads, Bank provides banking services)
- Section 3.2: 50/50 profit split during implementation
- Section 3.3: Fund flow (Bank receives, approves transfers to CICO)
- Section 3.4: No post-implementation revenue sharing
- Section 5: Consortium Steering Committee governance
- Section 8: Confidentiality and intellectual property
- Section 9: Dispute resolution (mediation then arbitration)

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
| Consortium Agreement | 1.0 | July 20, 2025 | Active |
| CICO HijraBank SLA | 1.0 | Sept 20, 2025 | Active |
| Hawilpay HijraBank RSA | 1.0 | Sept 20, 2025 | Active |
| CICO SaaS Pricing | 1.0 | Sept 20, 2025 | Active |

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
