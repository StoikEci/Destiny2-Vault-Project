# Brent's Destiny 2 Weapon Vault Analysis — July 18, 2026

## Snapshot

- Permanent baseline: `2026-07-18-DIM-Weapons-Permanent-Baseline.csv`
- SHA-256: `26a046a058528a7b9d824f53306fc5447ccb4cdd2b0f405297bd458351ffc9bd`
- Weapon rows: 1,035
- Unique names: 495
- Duplicate-name groups: 224
- Excess copies beyond one per name: 540

## Recommendations

| Category | Count |
|---|---:|
| Definitely Delete | 1 |
| Strong Delete | 7 |
| Could Delete | 54 |
| Manual Review | 43 |
| Protected | 222 |
| Keep - Only Copy | 204 |
| Keep - Costly Source | 32 |
| Keep - Distinct/Best | 472 |

## Immediate safe review set

The separate DIM import contains only **8** high-confidence candidates. It does not contain the `Could Delete` or `Manual Review` groups.

## High-confidence candidates

- **Ammit AR2** — delete `6917529871753015710`; retain `6917529890036663960`. All legal main-trait combinations are covered by the retained copy. Stat utility difference +4.8; stat-option quality +2.3.
- **Giver's Blessing** — delete `6917530186398994492`; retain `6917530187969778474`. All legal main-trait combinations are covered by the retained copy. Stat utility difference +5.0; stat-option quality +3.1.
- **Giver's Blessing** — delete `6917530188023157531`; retain `6917530187969778474`. All legal main-trait combinations are covered by the retained copy. Stat utility difference +8.2; stat-option quality +1.2.
- **Loaded Question** — delete `6917530189348803930`; retain `6917529091756856209`. Exact functional duplicate: same weapon, legal perks, Tier, Masterwork type, and Holofoil status; retained copy has stronger protection/use history.
- **Nightshade** — delete `6917530191318329432`; retain `6917530189840231319`. All legal main-trait combinations are covered by the retained copy. Stat utility difference +5.4; stat-option quality +1.7.
- **Nox Perennial V** — delete `6917530022197957209`; retain `6917530188590375722`. All legal main-trait combinations are covered by the retained copy. Stat utility difference +1.8; stat-option quality +0.0.
- **Syncopation-53** — delete `6917529895391569842`; retain `6917529648603200454`. All legal main-trait combinations are covered by the retained copy. Stat utility difference +1.2; stat-option quality -1.4.
- **Whisper of the Worm** — delete `6917529321229532959`; retain `6917529997642907065`. Redundant Whisper of the Worm copy. Retained crafted level 18 copy includes Whispered Breathing; this copy has no kills, lock, tag, or loadout.

## Interpretation

This is a conservative duplicate/perk-combination analysis, not a generic god-roll ranking. Tier 5 flexibility, barrels, magazines, Masterworks, practical stats, PvE perk quality, build roles, user metadata, kill history, dungeon/raid source cost, and retained replacement coverage were all considered.

The `Could Delete` sheet is the main space-saving work queue. Review it manually, especially where a weapon has unusually high range, stability, recoil direction, a niche perk interaction, or an activity-specific source.


## v2.3 frame/version safety note — July 19, 2026

The 54 `Could Delete` entries were retroactively checked against candidate and replacement weapon hashes:

- 38 use the same weapon hash/version.
- 16 use a different weapon hash/version.
- All 16 cross-version pairs still show the same DIM archetype, but may differ in origin traits, perk pools, source identity, and enhancement behavior.

The 16 cross-version entries are now a hold/manual-revalidation set. Use the new 38-item review import rather than treating all 54 as equally comparable.
