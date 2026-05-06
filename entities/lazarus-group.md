---
title: Lazarus Group
created: 2026-05-06
updated: 2026-05-06
type: entity
tags: [threat-actor, north-korea, crypto, hacking, social-engineering, nation-state]
sources:
  - raw/articles/ripple-dprk-threat-intel-sharing.md
confidence: high
---

# Lazarus Group

**North Korean state-sponsored hacking group responsible for the majority of cryptocurrency theft globally. Evolved from remote exploits to long-term social engineering infiltration.**

## Profile

| Attribute | Detail |
|-----------|--------|
| **Affiliation** | Democratic People's Republic of Korea (DPRK) |
| **Also known as** | Hidden Cobra, APT38, Zinc, Guardian of Peace |
| **Sponsorship** | Nation-state — funds weapons programs and sanctions evasion |
| **Primary target** | Cryptocurrency and DeFi protocols |

## Scale of Operations

| Metric | Value | Period |
|--------|-------|--------|
| Share of global crypto theft | 76% | 2026 (through April) |
| Total stolen (since 2017) | >$6.7 billion | Cumulative |
| Annual theft (2025) | >$2 billion | 2025 |
| Share growth | <10% → 64% | 2020 → 2025 |

## Evolution of Tactics

### Phase 1: Remote Exploits (2017–2023)
- Smart contract vulnerabilities
- Exchange hacks
- DeFi protocol exploits
- Traditional remote exploitation

### Phase 2: Social Engineering Infiltration (2024–present)
- Apply for jobs at crypto firms with fake identities
- Build trust over months of engagement
- Attend conferences, meet in person
- Compromise devices through malicious software
- Bypass traditional IOC-based detection
- Extract funds via compromised multisig wallets

**Key incidents demonstrating new tactics:**

| Incident | Loss | Method | Timeline |
|----------|------|--------|----------|
| [[drift-protocol]] | $285M | 6-month social engineering infiltration | Early 2026 |
| [[kelp-dao]] | $292M | Similar insider infiltration | Early 2026 |

## The "Reapplication Pattern"

A critical operational signature:
> "Threat actors rejected by one firm often reapply to several others the same week."

This pattern is exactly what [[crypto-isac]] was built to disrupt. Without shared intelligence, each company independently screens the same actor, missing the broader campaign context.

## Funding Purpose

According to U.S. Treasury Department assessments, stolen funds:
- Fund North Korea's weapons programs
- Support sanctions evasion efforts
- Undergo complex laundering via mixers and cross-chain bridges
- Converted to traditional currencies

## Related Pages

| Page | Connection |
|------|-----------|
| [[crypto-isac-threat-sharing]] | Industry response to Lazarus infiltration tactics |
| [[drift-protocol]] | $285M hack via Lazarus social engineering |
| [[kelp-dao]] | $292M hack via Lazarus infiltration |
| [[crypto-isac]] | Collective defense organization targeting Lazarus |

---

*Compiled from TRM Labs, Chainalysis, Crypto ISAC, and incident reports, May 2026.*
