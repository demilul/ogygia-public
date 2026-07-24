# Ogygia

**A mobile-first, server-authoritative, slow-burn strategy / empire-builder** in the tradition of
*Die Stämme* (Tribal Wars), *Grepolis* and *OGame* — depth and a satisfying slow rise over graphics.

> **Current version: v0.4.0 — "Social & Quality of Life"** · in active development
> This repository is a public showcase. The source code is kept in a private repository.

**Setting:** the Late Bronze Age Mediterranean — Sea Peoples, Phoenician traders, Aegean palaces —
woven through with hidden references to Homer's *Odyssey* (the name *Ogygia* is Calypso's island).
It is **not** an Odyssey retelling and **not** a Greek-pantheon city-builder.

## The idea in one paragraph

You are a **Wanax** (palace-lord) building a fragile trade-and-palace economy on a dangerous sea.
Keep your people fed — **grain** is a survival-grade upkeep resource, not just another number — grow
through parallel Infrastructure and Research tracks, and survive systemic overextension: the historical
**Bronze Age Collapse** is the game's structural anti-snowball engine. Player-versus-player conflict is
the north star, reached in slow, deliberate steps rather than a rush.

## What's in the game today

- **Economy** — four resources with real scarcity (tin is the bottleneck), storage caps, an unraidable
  floor, and grain upkeep that punishes overextension.
- **Asynchronous PvP** — deterministic raiding resolved server-side, with a distance-and-size
  *provisioning* penalty as its signature twist, night-time protection, beginner protection, and
  full battle reports for both sides.
- **Espionage** — a dedicated scout unit and staggered intel tiers: the more you commit, the more you
  learn. Defenders get counter-intelligence reports about who has been watching them.
- **Diplomacy & alliances** — alliances with roles and reinforcement, plus alliance-to-alliance
  non-aggression pacts with an announced cancellation period.
- **Social identity** — a unique username, friends across alliance lines, and a name for your own city.
- **Military buildings** — Warrior Hall and Stable gate who you can train, and higher levels train
  those units faster.
- **Two flavours of AI neighbours** — passive barbarian camps to practise on, and disguised aggressors
  that play by the same rules you do.
- **German and English** throughout, including a consistent in-world vocabulary.

## How it is built

- **Backend:** Supabase (PostgreSQL). All authoritative game logic lives in PL/pgSQL functions on a
  non-exposed schema; clients submit **intent** only and never compute outcomes.
- **Time model:** *lazy settlement* — state is computed from elapsed time on read — plus a scheduled
  sweep for discrete events, so the world keeps running while you are offline.
- **Client:** Flutter, one codebase for iOS, Android and Web.

Design decisions are recorded as ADRs and a living domain glossary in the private repository.

## Versions

See [CHANGELOG.md](CHANGELOG.md) and the [Releases](../../releases) tab.

---

*Ogygia is a personal project, built in the open enough to be shown — but not open source.*
