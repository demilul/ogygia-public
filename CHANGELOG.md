# Changelog

Milestone releases of **Ogygia**. Each version is a playable step, not a patch bundle.

---

## v0.4.0 — Social & Quality of Life
*2026-07-24*

Neighbours got names, and the palace started asking for the right buildings.

- **Username & friends** — choose a unique handle and add people by it. Friends are personal and
  cross alliance lines; you can quietly block someone without a drama channel.
- **Push that earns its keep** — nudges for an incoming attack and a friend request, each switchable
  on its own. When a build or research finishes, the idle-track nudge now says *what* reached its new
  level.
- **Name your city** — give your palace a public name that shows on the map and in reports.
- **The military chain** — raise a Warrior Hall before infantry and scouts, a Stable before cavalry.
  Each level of those halls also shortens training time for the units they speed.
- **Clearer progression** — research that needs a building says so, the construction list follows a
  designed order, and the night defence window follows Berlin time including daylight saving.

## v0.3.0 — Intelligence & Diplomacy
*2026-07-23*

Knowing became a resource of its own.

- **Espionage** — a dedicated scout unit and march type, opposed by scouts garrisoned at the target.
  Intel arrives in tiers: commit more and you learn more, from a bare resource tally up to buildings
  and troop movements. A failed mission tells you nothing.
- **Counter-intelligence** — defenders now get their own reports: someone has been watching you, and
  sometimes you learn from where.
- **Non-aggression pacts** — alliances can propose, accept and cancel pacts, with a visible cooldown
  before a broken pact can be re-signed.
- **Accounts** — passwordless sign-in (email link, Apple, Google), guest play that can be upgraded to a
  real account later without losing progress, and sessions that survive a restart.

## v0.2.0 — Async PvP (Raiding)
*2026-07-22*

The game got teeth.

- **Raiding** — asynchronous, server-resolved combat with a deterministic outcome: army composition,
  walls, morale, night-time and a bounded luck factor all feed one closed-form resolution.
- **Overextension** — the signature twist: raids far from home, or with oversized armies, weaken
  themselves through provisioning. Reach costs you.
- **Protection that isn't a wall of rules** — night-time defence bonus, a tapering shield for newcomers,
  and a punch-up gate so bigger accounts cannot farm smaller ones.
- **Reports and warnings** — full battle reports for both sides, shareable, plus incoming-attack
  warnings; a surprise posture trades strength for stealth.
- **Alliances** — membership with roles, a shared map layer, and reinforcement troops that defend an
  ally's palace and take casualties alongside them.

## v0.1.0 — MVP: Economy Slice
*2026-07-18*

The first playable loop.

- **Four-resource economy** with production, storage caps and grain as a genuine upkeep pressure.
- **Two parallel tracks** — infrastructure and research — so there is always a meaningful next choice.
- **A world that runs without you**: state is derived from elapsed time, and scheduled events land
  whether or not you are watching.
- **A living map** with AI neighbours that grow over time.

## v0.0.1 — Foundation
*2026-07-18*

Architecture first: the server-authoritative model, the data schema, and the first client build.
