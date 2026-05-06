---
title: Drift Protocol
created: 2026-05-06
updated: 2026-05-06
type: entity
tags: [defi, solana, hack, social-engineering, lazarus, dprk]
sources:
  - raw/articles/ripple-dprk-threat-intel-sharing.md
confidence: high
---

# Drift Protocol

**Solana-based perpetual futures DEX. Lost $285 million in a 6-month social engineering infiltration by North Korean operatives in early 2026.**

## Profile

| Attribute | Detail |
|-----------|--------|
| **Type** | Perpetual futures DEX |
| **Blockchain** | Solana |
| **Loss** | $285 million |
| **Attribution** | Lazarus Group (DPRK) |
| **When** | Early 2026 |

## The Attack

Not a smart contract exploit or zero-day. The attack began with **human infiltration:**

1. **Months of engagement** — Malicious actors gained trust of Drift contributors
2. **In-person meetings** — Attended conferences, built relationships face-to-face
3. **Malicious software** — Compromised contributor devices
4. **Bypass IOCs** — Traditional indicators of compromise didn't catch this
5. **Multisig compromise** — Used device access to compromise multisig wallets
6. **Fund extraction** — $285M stolen

## Significance

> "The Drift incident represents a new level of operational sophistication. These weren't opportunistic attacks but carefully orchestrated infiltrations involving physical presence and long-term relationship building."
> — TRM Labs researcher

This incident demonstrated that:
- **Social engineering is the new primary vector** — Not code exploits
- **Inside access beats perimeter defense** — Trusted insiders are the threat
- **Traditional security tools fail** — IOC-based detection doesn't catch humans
- **Collective defense is essential** — One company's detection benefits all

## Response

The Drift hack directly triggered [[ripple]]'s decision to share DPRK intelligence through [[crypto-isac]], and accelerated the development of Crypto ISAC's enriched threat intelligence API.

## Related Pages

| Page | Connection |
|------|-----------|
| [[lazarus-group]] | Attributed threat actor |
| [[crypto-isac-threat-sharing]] | Industry response triggered by this incident |
| [[kelp-dao]] | Similar attack pattern, same timeframe |

---

*Compiled from incident reports, TRM Labs analysis, and Crypto ISAC communications, May 2026.*
