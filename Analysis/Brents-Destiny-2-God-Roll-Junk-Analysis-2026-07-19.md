# Brent's Destiny 2 God-Roll and Synergy Vault Analysis

**Working snapshot:** `2026-07-19-DIM-Weapons-Current.csv`  
**Snapshot SHA-256:** `6d5226e6e50801155f61a4b667debfba4a22ed67a3119d402a4fa09963c08f40`  
**Weapons analyzed:** 1,073  
**Unique weapon names:** 500  
**Duplicate-name groups:** 231  
**Copies beyond one per weapon name:** 573  
**Tier 5 weapons:** 105

## Result

The new DIM import contains **7 conservative junk candidates**.

This is intentionally much smaller than the earlier automated lists. The previous 54-item and 38-item imports are superseded because they did not consistently apply:

- Current Community Insights.
- Community-supported role/god-roll pairings.
- Perk-to-perk synergy.
- Exact frame behavior and archetype-specific stats.
- Origin traits and weapon versions.
- Positive-only metadata treatment.

## New scoring order

1. Current community-supported god rolls and role rolls.
2. Coherent perk synergy for a real PvE, PvP, DPS, add-clear, support, movement, or build role.
3. Exact intrinsic frame and firing behavior.
4. Archetype-specific stats such as draw time and charge time.
5. Element, Champion, ammo, slot, engagement range, and build coverage.
6. Origin trait, Tier flexibility, source, and reacquisition cost.
7. Positive personal evidence such as Favorite, Keep, lock, loadout use, crafted status, or kill history.

**Zero kills, no lock, and no tag are neutral—not negative.**

DIM wishlist recommendations and community god-roll pages are evidence, not infallible commands. Wishlist absence cannot mean a roll is bad. The final judgment still accounts for Brent's preferences and actual inventory.

## Junk candidates

- **Whisper of the Worm** — tag `6917529997616595154` as Junk; retain `6917529997642907065`. **Definitive.** The retained copy is the same Whisper of the Worm definition and stat package, but it also has Whispered Breathing. The uncatalyzed copy adds no unique frame, element, origin-trait, or perk-combination coverage.
- **Agape** — tag `6917530186063785629` as Junk; retain `6917530186089352609`. **Strong duplicate consolidation.** Same weapon hash, Heavy Burst frame, element, origin trait, and selected main-perk pair. The retained Tier 2 copy preserves the role and adds a broader component package, including Light Mag as an alternate. One Pugilist + Incandescent copy is sufficient.
- **Axial Lacuna** — tag `6917530029617827498` as Junk; retain `6917530025492912305`. **High for Brent's PvE priorities.** The candidate's crouch-dependent consistency and post-kill damage loop is much more PvP/niche oriented. The retained copy matches the current community Max DPS pairing and is the stronger PvE boss/major option. Other retained Axial copies still cover Surrounded and Incandescent roles.
- **Combined Action** — tag `6917530021130544255` as Junk; retain `6917530192841996351`. **High for Brent's PvE priorities.** Offhand Strike creates a specialized hip-fire loop after a kill, while Brent primarily values safe, reliable PvE utility. The retained locked copy uses the community PvE pairing Eddy Current + Voltshot, turning reload support directly into repeated Jolt application.
- **Marcato-45** — tag `6917530064716810577` as Junk; retain `6917529970982048243`. **High duplicate-role reduction.** Steady Hands + Adagio is usable, but it is a generic post-kill roll with no strong Strand verb loop. The retained Slice + Hatchling copy matches the current community Strand-synergy recommendation, has 100 recoil direction, and preserves the element/frame role. A locked Demolitionist + Onslaught copy also preserves an ability/damage alternative.
- **Someday** — tag `6917530022275957653` as Junk; retain `6917530029653892225`. **High duplicate-role reduction.** Both copies use Dual Loader, but Recombination provides a clearer stored-burst role for a Precision Frame shotgun. The retained copy is the current community Max Damage pairing. Other Someday copies still preserve Lead from Gold + Vorpal and Threat Remover + Opening Shot roles.
- **Ulterior Observation** — tag `6917530187931340048` as Junk; retain `6917530193082640691`. **High duplicate-role reduction.** Subsistence + Dynamic Sway Reduction is coherent but lacks either a damage payoff or Stasis verb payoff. The retained Tier 3 copy can run the exact community Stasis pairing Headstone + Rimestealer and can also run Feeding Frenzy + Killing Tally for a strong add-clear loop. Another retained Tier 3 copy preserves Subsistence-based options.

## Deliberate holds

These were specifically **not** placed in the junk import:

- **Neoptolemus II — To the Pain + Wellspring, 600 draw time:** preserved because its draw speed creates a distinct, responsive bow role.
- **No Hesitation — Demolitionist + Desperate Measures:** preserved as a coherent grenade-energy, grenade-reload, and damage-loop roll.
- **Staccato-46 — Compulsive Reloader + Rampage:** preserved for now because it is a recognizable reload/damage loop and deserves hands-on comparison rather than generic dismissal.
- **All Eager Edge swords:** protected. At least one functional Eager Edge sword must always remain, and the current copies preserve different element/frame combinations.
- **New or untested weapons:** no item was penalized for having zero kills, no lock, no tag, or no loadout history.
- **Bows with materially different draw times, fusions with different charge times, and swords with different blade/guard packages:** held unless the practical stat tradeoff was explicitly resolved.

## Files

- DIM import: `DIM-Import-Junk-God-Roll-Validated-7-2026-07-19.csv`
- Detailed audit: `Brents-Destiny-2-God-Roll-Junk-Audit-2026-07-19.csv`
- This summary: `Brents-Destiny-2-God-Roll-Junk-Analysis-2026-07-19.md`
