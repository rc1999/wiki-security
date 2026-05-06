---
title: Crypto ISAC Threat Intelligence Sharing
created: 2026-05-06
updated: 2026-05-06
type: concept
tags: [threat-intel, crypto-isac, north-korea, crypto-security, social-engineering, collective-defense, api]
sources:
  - raw/articles/ripple-dprk-threat-intel-sharing.md
confidence: high
---

# Crypto ISAC Threat Intelligence Sharing

**Industry-wide information sharing initiative to combat North Korean infiltration of crypto firms through coordinated threat intelligence distribution via API.**

**Announced:** May 4, 2026  
**Key players:** [[ripple]], [[crypto-isac]], [[coinbase]]  
**Threat actor:** [[lazarus-group]] (DPRK)

---

## The Problem

North Korean hackers have shifted from remote exploits to **long-term social engineering infiltration**:

- Apply for jobs at crypto firms using fake identities
- Build trust over months of engagement
- Compromise devices through malicious software
- Bypass traditional IOC-based detection
- Extract funds via compromised multisig wallets

**The gap:** Without shared intelligence, each company screens applicants independently. A rejected DPRK operative at Company A applies to Companies B, C, D the same week — each starting from zero.

> "A threat actor might fail a background check at one company and apply to three others the same week. Without shared intelligence, each company is starting from zero."
> — Christina Spring, Director of Growth, Crypto ISAC

---

## The Solution: Crypto ISAC API

### What Gets Shared

| Data Type | Description | Use Case |
|-----------|-------------|----------|
| **DPRK-linked wallet addresses** | Blockchain addresses associated with Lazarus Group | On-chain monitoring, transaction screening |
| **Malicious domains** | Fraud-linked websites used in campaigns | DNS blocking, email filtering |
| **Indicators of Compromise (IOCs)** | Technical signatures from active campaigns | SIEM integration, threat detection |
| **Enriched operative profiles** | LinkedIn IDs, emails, phone numbers, locations | HR onboarding screening, background checks |
| **Correlated campaign signals** | Connections between individuals and broader operations | Campaign tracking, pattern analysis |

### What Makes It Different

Unlike generic threat feeds, Crypto ISAC's API provides **contextually enriched, high-confidence data**:

- A DPRK IT worker profile isn't just a name — it includes LinkedIn, email, location, phone, and correlated campaign signals
- Normalizes intelligence across **Web2 and Web3** threat indicators
- Built for direct integration into security operations
- Real-time updates as new intelligence flows in

---

## Key Incidents Driving the Initiative

### Drift Protocol Hack — $285M
- **When:** Early 2026
- **How:** 6-month social engineering campaign
- **Tactic:** Malicious actors gained trust of Drift contributors over months, compromised devices via malicious software, bypassed IOCs, compromised multisig wallets
- **Significance:** Demonstrated the "wolves in sheep's clothing" approach — patient, inside-out infiltration

### Kelp DAO Hack — $292M
- **When:** Early 2026
- **How:** Similar social engineering infiltration
- **Total DPRK 2026 losses:** $577M from these two incidents alone
- **Share of global crypto theft:** 76% of all crypto hack value in 2026 (through April)

---

## Scale of the Threat

| Metric | Value | Source |
|--------|-------|--------|
| DPRK share of 2026 crypto hacks | 76% | TRM Labs |
| Total DPRK crypto theft (since 2017) | >$6.7 billion | Chainalysis, TRM Labs |
| DPRK crypto theft (2025 alone) | >$2 billion | Chainalysis, TRM |
| DPRK share growth (2020→2025) | <10% → 64% | TRM Labs |
| Drift Protocol loss | $285M | Incident reports |
| Kelp DAO loss | $292M | Incident reports |
| Total early 2026 losses | $577M | Combined |

---

## How the API Works

```
Crypto ISAC Member Companies
         |
         v
   [Threat Detection]
   - AI-enhanced workflows
   - Human analyst validation
   - Cross-reference with campaign data
         |
         v
   [Enrichment Layer]
   - Add LinkedIn, email, location
   - Correlate with broader campaign
   - Assign confidence score
         |
         v
   [Crypto ISAC API]
   - Normalized data format
   - Web2 + Web3 indicators
   - Real-time updates
         |
         v
   [Member Firms]
   - Onboarding screening
   - Threat intel workflows
   - SIEM integration
```

---

## Quotes from Key Stakeholders

> "Crypto ISAC's newly updated API represents a meaningful step forward in how intelligence is shared across the ecosystem. As an early adopter, we've been working closely with Crypto ISAC to onboard and operationalize new data sources in a way that aligns with our internal workflows."
> — Erin Plante, Director of Brand Security and Intelligence, Ripple

> "For too long, information sharing was seen as optional. Today, it is the gold standard for security and Ripple's action through Crypto ISAC is the definitive proof of concept."
> — Justine Bone, Executive Director, Crypto ISAC

> "One of the biggest challenges in crypto threat intelligence is bridging the gap between raw signals and operational decisions. Working with Crypto ISAC on developing their updated API allowed us to help shape a data model that preserves context and confidence — not just indicators."
> — Jeff Lunglhofer, Chief Information Security Officer, Coinbase

---

## Recommended Actions for Firms

1. **Join Crypto ISAC** — Access the threat intelligence feed
2. **Integrate into onboarding** — Screen applicants against DPRK operative profiles
3. **Add to threat intel workflows** — Feed IOCs into SIEM, SOAR, detection pipelines
4. **Share back** — When you detect a threat actor, contribute to the collective pool
5. **Monitor reapplication patterns** — Track if rejected candidates reapply elsewhere in the same timeframe

---

## Related Concepts

| Concept | Connection |
|---------|-----------|
| [[social-engineering]] | The primary vector — long-term trust-building infiltration |
| [[collective-defense]] | Industry-wide coordination as the new security standard |
| [[crypto-security-market]] | $3.99B market growing at 21.7% CAGR, driven by threats like this |
| [[north-korea-crypto-theft]] | Systematic nation-state campaign funding weapons programs |

---

## Sources

- **Crypto ISAC Official:** https://www.cryptoisac.org/news-member-content/north-korean-hackers-are-infiltrating-crypto-companies-ripple-and-crypto-isac-are-sharing-the-intelligence-to-help-stop-them
- **Crypto.news:** https://crypto.news/ripple-begins-sharing-dprk-threat-intel-with-crypto-firms/
- **Crypto Briefing:** https://cryptobriefing.com/ripple-shares-north-korean-threat-intel-to-curb-crypto-hacks-by-2026/
- **TRM Labs Report:** https://fensory.com/intelligence/defi/north-korea-crypto-theft-6-billion-trm-labs-report
- **Future Market Insights:** https://www.futuremarketinsights.com/reports/crypto-security-market

---

*Compiled from multiple sources, May 2026.*
