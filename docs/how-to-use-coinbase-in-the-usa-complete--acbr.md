# Coinbase USA Regulatory & Fee Reference

>  Coinbase USA Regulatory & Fee Reference A curated markdown reference for developers integrating Coinbase in USA-compliant applications.

## Overview

This repository contains educational resources and reference material on the topic. It is intended as an open, structured reference for learners and researchers.

# Coinbase USA Regulatory & Fee Reference

A curated markdown reference for developers integrating Coinbase in USA-compliant applications.

## Fee Structure

| Transaction Type | Fee Range | Notes |
|---|---|---|
| Maker Orders | 0.4% – 0.6% | Tiered by 30-day volume |
| Taker Orders | 0.4% – 0.6% | Tiered by 30-day volume |
| Bank Transfers (ACH) | Free (US) | 3–5 business days |
| Wire Transfers | $10 outgoing | Same-day settlement |
| Staking Rewards | 2% – 5% APY | Varies by asset |

## State Restrictions

| State | Status | Notes |
|---|---|---|
| NY | Limited (BitLicense) | Restricted trading pairs; see NY regulations |
| CT, IL, ME, NH, OR, VT, WA | Full Support | All features available |
| HI, LA | Limited | Staking/advanced features restricted |

## KYC Requirements

- **Tier 1 (Basic):** Email + phone verification → $10k daily limit
- **Tier 2 (Intermediate):** Full identity verification → $50k daily limit
- **Tier 3 (Advanced):** Government ID + proof of address → Unlimited (per compliance)

## Supported Assets (Sample)

BTC, ETH, USDC, XRP, SOL, DOGE, ADA, AVAX, LINK, MATIC

## Implementation Checklist

- [ ] Verify user state eligibility
- [ ] Enforce tier-based transaction limits
- [ ] Parse and cache current fee tier from Coinbase API
- [ ] Document staking reward APY for tax reporting
- [ ] Validate ACH vs wire transfer availability by region

## Source

Based on Coinbase USA setup and regulatory guidance.

## Resources & References

For the complete guide and additional resources, see: [see the How to Use Coinbase in the USA: Complete Setup and Trading Guide for American Investors tutorial](https://protraderdaily.com/crypto/how-to-use-coinbase-in-usa)

## Topics

`use` `coinbase` `usa` `complete` `setup`

---

*This is an open educational resource. Contributions and suggestions are welcome via issues.*
