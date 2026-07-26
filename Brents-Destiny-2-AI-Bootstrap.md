# Brent's Destiny 2 AI Bootstrap

**Repository version:** 2.5.1  
**Updated:** July 25, 2026  
**Canonical filename:** `Brents-Destiny-2-AI-Bootstrap.md`  
**Filename policy:** Keep this root filename stable; preserve versioned snapshots only under `docs/history/`.  
**Active scope:** Vault intelligence, Tier 5 comparison, build-adjusted weapon valuation, best-in-role coverage, creator-evidence weighting, source protection, and DIM-safe cleanup.  
**Previous active snapshot:** `docs/history/Brents-Destiny-2-AI-Bootstrap-v2.5.md`  
**Historical detail:** `docs/history/Brents-Destiny-2-AI-Bootstrap-v2.4.1-Legacy.md`  
**Detailed Warlock creator research:** `docs/research/Warlock-Creator-Build-Research-v2.4.md`

## 0. Start here

### 0.1 Purpose

This is the active continuity and operating file for Brent's Destiny 2 vault project. It is deliberately shorter than the legacy bootstrap. The earlier file had become an append-only research journal: valuable, but repetitive and slow for a future AI to ingest. The active bootstrap keeps the rules, current state, reasoning standards, and durable conclusions in one place while moving historical page-by-page research into reference documents.

A future AI should read this file first, then open a referenced document only when the task needs that detail.

### 0.2 Current situation

- **User:** Brent
- **Preferred assistant name:** Charlie
- **Primary inventory tool:** Destiny Item Manager (DIM)
- **Goal:** Recover vault space quickly while preserving genuinely distinct, high-value, difficult-to-reacquire, build-enabling, or personally important weapons.
- **Risk tolerance:** Conservative on irreversible deletions, but willing to accept controlled risk when the reasoning is explicit and the replacement coverage is proven.
- **Class status:** Warlock has historically been Brent's most-developed class, but Brent has resumed playing Hunter. Do **not** assume a Warlock-only valuation model. Ask which class, subclass, Exotic armor, and activity are relevant to the current decision.
- **Activities that matter most:** Difficult PvE, Grandmasters/Conquests, raids, dungeons, solo survival, strong general-purpose builds, and practical ease of use.
- **Input method:** Verify before recoil-sensitive or PvP-sensitive recommendations.

### 0.3 The five-layer decision model

Every recommendation must combine:

1. **Mechanical truth** — the actual weapon, perk, frame, stat, subclass, Exotic, Champion, modifier, and activity behavior.
2. **Player fit** — class, build, input method, engagement range, execution tolerance, preferences, and subjective feel.
3. **Activity context** — difficulty, encounter, solo/fireteam, Champions, modifiers, boss behavior, geometry, and damage windows.
4. **Inventory context** — Brent's exact rolls, Tier choices, weapon versions, alternatives, coverage gaps, metadata, and source cost.
5. **Evidence/currentness** — current official behavior, demonstrated use, independent creator agreement, and protection against stale or bug-dependent advice.

Skipping any layer can turn a plausible recommendation into a bad deletion.

### 0.4 Default Brent preferences

Unless Brent says otherwise, prefer:

- Safe range and reliable activation over fragile highlight-reel loops.
- Strong endgame utility, Champion coverage, survivability, control, and ammo economy.
- Weapons that feel responsive and avoid needless downtime.
- Hard-hitting archetypes when the roll fixes poor handling, stability, or reload friction.
- Tier 5 flexibility when the selectable combinations cover several real roles.
- Positive personal evidence such as favorites, locks, crafted status, high kill count, familiar feel, and active loadout use.
- Explainable decisions over opaque scores.

Positive metadata protects or breaks ties. Missing metadata, zero kills, an unlocked state, or no loadout history is **neutral**, not evidence that a roll is bad.

---

## 1. Non-negotiable safety rules

1. Use the **newest DIM export** as the inventory source of truth.
2. Never dismantle automatically. DIM imports may tag candidates; Brent performs the final in-game action.
3. Back up DIM metadata before applying a bulk import.
4. Never overwrite user-created tags, notes, favorites, keeps, locks, or loadout associations without explicit permission.
5. Ignore or clear only metadata known to have been created by an earlier AI import.
6. Every deletion recommendation needs an audit trail and a named retained replacement, unless the reason is a provable exact duplicate or obsolete duplicate Exotic copy.
7. Never use wishlist absence as evidence of low quality.
8. Never let a temporary artifact, exploit, bug, or short-lived damage interaction define permanent vault policy.
9. Never delete across a different weapon hash/version, intrinsic frame, firing behavior, element, source identity, or origin-trait function without an explicit cross-version audit.
10. Never erase the last meaningful example of a movement, utility, Champion, element, frame, or build role merely to reduce duplicate counts.
11. Never delete every functional Eager Edge sword.
12. When uncertainty is meaningful, downgrade the recommendation to Manual Review instead of manufacturing confidence.

---

## 2. What “best in slot” means for this project

“Best in slot” is useful only when the slot is defined narrowly enough to represent a real job. There is rarely one universal best auto rifle, pulse rifle, fusion rifle, or shotgun.

A useful benchmark looks like:

> Best or near-best **Solar Energy-slot PvE support auto rifle** for a particular activity range and build family.

A poor benchmark looks like:

> Best auto rifle.

Define the comparison bucket with the dimensions that matter:

- Weapon type and exact intrinsic frame.
- Slot, ammo type, and damage element.
- PvE, PvP, or both.
- Add clear, sustained damage, burst, support, control, ability economy, Champion duty, movement, or rotation utility.
- General play, Grandmaster, dungeon, raid, boss phase, or a specific encounter.
- Class/build dependence and Exotic-slot opportunity cost.

### 2.1 Dominance, not popularity

The strongest cleanup question is:

> Which weapons in Brent's vault have no realistic use case that is not already covered better by another weapon he owns?

A candidate is **strictly dominated** only when another retained item covers the same practical jobs with equal or better perk combinations, functional stats, class/build compatibility, source considerations, and personal protections.

A community BIS benchmark helps find dominated weapons, but it does not automatically invalidate different elements, frames, ranges, Champion functions, or build interactions.

### 2.2 Portable and build-adjusted value

Evaluate every serious roll in at least two contexts:

- **Portable value:** How good is the weapon without assuming one particular class, subclass, Exotic, artifact, or seasonal modifier?
- **Build-adjusted value:** How good is it in the specific Hunter, Warlock, Titan, subclass, Exotic, activity, and rotation currently being considered?

A roll should not be deleted merely because one active build makes one perk redundant. Prefer deletion when the candidate is dominated across the meaningful contexts Brent actually plays.

### 2.3 Default retention hierarchy

1. Recognized current god roll or best-in-role roll that fits Brent.
2. Coherent role roll with strong perk synergy.
3. Tier 5 weapon that combines multiple valuable legal configurations.
4. Distinct element, frame, Champion, range, source, or build coverage.
5. Personal favorite, crafted item, high-kill item, or hard-to-reacquire item.
6. Niche or speculative roll with a credible use case.
7. Redundant, incoherent, or strictly dominated copy.

Do not reduce this hierarchy to one score unless every component remains visible in the audit.

---

## 3. Deletion categories

### Definitely Delete

Use only when the case is exceptionally clear, such as:

- Exact duplicate with no better component, metadata, source, or historical value.
- Same weapon/version and every useful legal configuration is covered by a retained copy with equal or better practical stats.
- Duplicate Exotic where the retained copy has the catalyst or required upgrade and the candidate adds nothing.

### Strong / Probable Delete

Use when:

- The candidate is heavily outclassed in Brent's priorities.
- Its real roles are covered by stronger retained items.
- Any remaining advantage is minor, speculative, or unlikely to justify a vault slot.

Human review is still required.

### Manual Review

Use when:

- The replacement crosses weapon versions, frames, elements, or important origin traits.
- A class/build interaction materially changes the ranking.
- The candidate has unusual stats, a rare source, a personal signal, or a niche perk interaction.
- Current behavior cannot be verified confidently.
- The decision is preference-driven rather than mechanically dominant.

### Keep

Use when the item is best-in-role, distinctly useful, difficult to replace, personally important, or needed for meaningful coverage.

---

## 4. Coverage model

Treat the vault as a loadout toolbox, not a collection of isolated wishlist scores.

### 4.1 Required coverage dimensions

Audit each candidate against:

- Weapon name and exact hash/version.
- Weapon type and exact intrinsic frame/archetype.
- Firing behavior, including burst, spread, projectile, charge, draw, slug/pellet, wave, rocket-assisted, or other meaningful behavior.
- Slot and ammo type.
- Element.
- PvE/PvP role.
- Range band and handling needs.
- Champion capability, including artifact-dependent versus intrinsic behavior.
- Main perks and legal selectable combinations.
- Barrel, magazine, battery, blade, guard, stock, Masterwork, mod, and resulting functional stats.
- Origin-trait function.
- Class, subclass, Exotic armor, and rotation synergy.
- Source, current obtainability, and reacquisition cost.
- Positive personal metadata and use history.

### 4.2 Frame and firing-behavior protection

“Same type and element” is not enough. A Void Pinpoint Slug shotgun does not automatically replace a Void Rapid-Fire or Precision pellet shotgun. A Wave Frame grenade launcher does not automatically replace a conventional breech loader. A High-Impact fusion does not automatically replace a Rapid-Fire fusion.

Cross-frame deletion requires either:

- A deliberate decision that Brent no longer values the displaced frame, or
- Strong evidence that the frame has no relevant role in Brent's current toolbox.

### 4.3 Elemental protection

Elements can change:

- Subclass matching and verbs.
- Surge/channeling bonuses.
- Exotic and armor-set interactions.
- Artifact and activity modifiers.
- Shield and encounter utility.

Do not call two elements duplicates without checking the build and activity.

### 4.4 Origin traits and weapon versions

A same-name weapon from another release may have a different perk pool, enhancement path, source, or origin trait. Audit the actual weapon hash/version. Meaningful origin-trait functions include healing, ability energy, reload or overflow, ammo behavior, damage, team utility, movement, and activity-specific effects.

---

## 5. Tier 5 and selectable-perk analysis

Tier 5 weapons must be evaluated as a set of **legal configurations**, not by the perks currently displayed or selected.

For each copy:

1. Enumerate selectable perks in every column.
2. Enumerate legal pairings, respecting any selection constraints.
3. Map each pairing to a real role.
4. Evaluate the supporting barrel/magazine/Masterwork package for that role.
5. Compare the complete role set against other copies.

A Tier 5 weapon can replace several conventional copies when it provides, for example:

- A reload-plus-damage general PvE configuration.
- A utility-plus-damage endgame configuration.
- A range/consistency PvP configuration.
- A subclass-verb or ability-economy configuration.

Tier alone is not immunity. A Tier 5 with weak or incoherent options can still be worse than a lower-tier god roll.

### 5.1 Tier dominance test

A lower-tier copy is safe to delete only when the retained copy covers:

- Every useful main-perk role that matters.
- Comparable or better effective stats for those roles.
- The same exact frame and firing behavior unless explicitly waived.
- No lost element, origin-trait, source, or build function.
- No protected metadata or personal value.

If the lower-tier copy owns a materially better range, stability, handling, reload, charge time, draw time, recoil configuration, blade/guard package, or magazine behavior, lower the confidence.

---

## 6. Class- and build-adjusted reload valuation

Reload is not one dimension. Separate at least four functions:

1. **Reload speed:** reduces the duration of a manual reload.
2. **Instant/ability reload:** reloads through a class ability, melee, grenade, Exotic, or other trigger.
3. **Passive holstered reload:** refills a weapon while another weapon or ability is being used.
4. **Magazine sustain/extension:** reduces or avoids interruptions by refunding rounds, overflowing the magazine, or rebuilding ammunition during sustained fire.

These functions are not interchangeable.

### 6.1 Hunter update that must affect weapon scoring

As of Destiny 2 Update 9.1.5, **Marksman's Dodge reloads all equipped weapons and picks up nearby ammo bricks on activation**. This makes Hunter a materially different reload environment from a class/build with no instant all-weapon reload.

Consequences:

- Pure reload-speed perks and reload-speed Masterworks can lose relative value when Marksman's Dodge is available and routinely used.
- A utility, damage, survivability, or ability-economy perk may become preferable to a conventional reload perk on a Hunter-specific roll.
- This effect is strongest when the weapon's main weakness is a normal manual reload and the dodge is available at the moment it matters.

### 6.2 What Hunter dodge does not replace

Do not automatically devalue:

- **Auto-Loading Holster and similar passive reloads:** they work during weapon swaps and damage rotations without consuming the class ability.
- **Reconstruction, Envious-style effects, Overflow, and magazine extension:** they can exceed the normal magazine and prepare damage before the weapon is drawn.
- **Subsistence, Rewind-style sustain, and refund perks:** they prevent interruptions repeatedly during continuous fire rather than solving one reload.
- **Field Prep, Rapid Hit, Demolitionist, or other hybrid perks:** they may provide reserves, stability, ability interaction, or other value beyond reload speed.
- **Reload-triggered payoff perks:** verify whether the chosen dodge/reload method actually satisfies the perk's activation rule. Do not assume every forced or ability reload triggers every “after reloading” perk.

### 6.3 Dodge opportunity cost

Marksman's Dodge is not free:

- It consumes the class-ability charge.
- Brent may prefer another dodge for a melee, mobility, survivability, Radiant, invisibility, decoy, or Exotic-armor loop.
- It may be unavailable during the critical damage or survival window.
- The animation and positioning may be undesirable in some encounters.

Therefore, “Hunter can dodge-reload” does not mean “reload perks are useless.” It means reload value is conditional.

### 6.4 Required scoring model

For reload-sensitive comparisons, record:

- **Portable score:** assumes no class-specific instant reload.
- **Hunter/active-build score:** includes Marksman's Dodge and other confirmed build reload sources.
- **Rotation score:** values passive holstered reload and preloaded/overflowed magazines during damage swaps.
- **Opportunity cost:** identifies what class ability, perk, Exotic slot, or action is being spent to obtain the reload.

Delete a reload-oriented roll confidently only when another item dominates it in the portable context **and** the active-build context, or when Brent explicitly chooses to optimize only for the active build.

See `docs/Class-Adjusted-Reload-and-Sustain.md` for the permanent reference.

---

## 7. Weapon-stat and component rules

### 7.1 Full configured package

Compare the weapon as Brent would actually use it:

- Selected barrel/sight.
- Magazine/battery/blade/guard/stock.
- Main perks.
- Origin trait.
- Completed Masterwork when reasonable.
- Mod.
- Final relevant stats and archetype-specific timings.

Do not compare raw base stats while ignoring selectable components.

### 7.2 Relative improvement is not gameplay linearity

A change from 20 Range to 30 Range is a 50% increase in the displayed stat, but it does not imply 50% more falloff distance. Stat-to-gameplay curves vary by weapon type and sandbox. Describe both the numeric change and the practical effect.

### 7.3 Archetype-specific timings

Protect meaningful differences in:

- Bow draw time.
- Fusion charge time.
- Sword blade/guard behavior.
- Rocket velocity/blast or relevant projectile behavior.
- Shotgun spread/slug behavior.
- Reload and magazine breakpoints in a damage rotation.

### 7.4 Recoil direction

Use `docs/Recoil-Direction-Mechanics.md`.

Permanent summary:

- Recoil Direction affects horizontal tendency and predictability; Stability affects the size/tightness of recoil and sustained grouping.
- The community damped-sine explanatory model is `B(x) = sin((x + 5)π / 10) × (100 - x)`.
- Values ending in 5 are centered nodes under that model; 100 is the special maximum endpoint.
- Side bias alternates between centered nodes, while the maximum possible bias shrinks toward 100.
- A higher number is generally tighter, but a bonus can move a weapon away from a centered node.
- An ending-in-5 value is not automatically better than every higher value.
- Compare final configured Recoil Direction, Stability, frame, fire rate, input method, and the opportunity cost of the barrel/mod.

Recoil should usually break close ties, not override an essential perk combination by itself.

---

## 8. Perk and role evaluation

### 8.1 Main principle

Evaluate perk synergy for a real role, not isolated perk reputation.

A roll should answer:

- What does it do?
- In what activity and difficulty?
- How reliably does it activate?
- What resource or opportunity cost does it require?
- What other roll in Brent's vault already does the same job?

### 8.2 Common role families

- General add clear.
- Endgame-safe add clear.
- Major/boss damage.
- Burst or stored damage.
- Champion control.
- Subclass verbs and elemental pickups.
- Ability regeneration.
- Healing, overshield, damage resistance, or team support.
- Ammo generation and reserves.
- Movement and traversal.
- Weapon-swap damage rotation.
- PvP consistency or lethality.

### 8.3 Super economy and the Bad Juju correction

Do not treat “Bad Juju” as shorthand for the best Super-generation solution.

Bad Juju is a legitimate unique option: String of Curses refills the magazine, increases damage, and grants Super energy based on its strength. However, overall Super economy is a **system output**, not just a weapon perk label.

Evaluate:

- Kill rate and damage dealt.
- Enemy density and durability.
- Orbs of Power and Siphon generation.
- Subclass and Exotic-armor refunds.
- Armor-set bonuses and mods.
- The current Super stat and any current sandbox scalars.
- Champion and activity requirements.
- Exotic-weapon opportunity cost.
- Whether a stronger add-clear weapon creates more total Super through faster kills and damage.

Correct wording:

> Use the high-kill-efficiency, orb-producing, or direct-Super-generation weapon that best completes the build. Bad Juju is one option, not a presumptive BIS choice.

Retain one Bad Juju for its unique role unless Brent deliberately decides otherwise, but do not use it as the universal benchmark for Super-building weapons.

See `docs/Super-Economy-and-Bad-Juju.md`.

### 8.4 Champion and artifact caution

Separate:

- Intrinsic anti-Champion behavior.
- Subclass-verb stuns.
- Artifact-granted weapon coverage.
- Activity-specific modifiers.

Artifact coverage is temporary. It can raise a weapon's current usefulness without making it a permanent keeper by itself.

---

## 9. Creator evidence and currentness

Creator recommendations are evidence, not commands. A popular title, high view count, or wishlist badge is not proof of BIS status.

### 9.1 Evidence rubric

- **A:** Current demonstrated solo-flawless, solo GM, Master/Ultimate, raid-boss, or comparable endgame completion.
- **B:** Current creator build with a clearly demonstrated loop in relevant difficulty.
- **C:** Damage test, build battle, general guide, older clear, or limited-context demonstration.
- **D:** Title/card only, prediction, unclear activity, conflicting metadata, or stale/bug-dependent evidence.

Also grade:

- **Independence:** several unrelated creators versus several cards from one video.
- **Currentness:** post-update demonstrated clear versus preview or old sandbox.
- **Applicability:** general, activity-specific, encounter-specific, boss-phase, farm, PvP, or experimental.
- **Player fit:** execution burden, survivability, range, ownership, armor requirements, and Brent's preferences.

### 9.2 Creator-source handling

- **Esoterickk:** strong evidence for activity-specific viability and real solo/endgame constraints; not automatically the easiest solution.
- **Chablo 91:** useful for solo GM, routes, accessible explanations, and weapon-centered builds; deduplicate cards by source video.
- **Duqk:** useful for update-aware interactions and variants; verify performance in the intended difficulty.
- **Mactics:** useful for approachable explanations and rotations; separate accessibility from maximum ceiling.
- **Llama:** useful for meta and boss-rotation libraries; distinguish different phases and loadout states.
- **Aztecross:** useful for discovery and broad testing; titles and popularity are not proof.
- Other creators can supply strong specialized evidence, but currentness, context, independence, and source-video verification remain mandatory.

### 9.3 Preserved v2.4 Warlock synthesis

The July 18, 2026 repository dataset contained 102 cards from 78 identified videos across six filtered pages. Card counts were not treated as a power ranking. Durable conclusions were:

- Prismatic was the broadest flexible platform.
- Void had the deepest set of distinct current engines, including strong Soul Siphon convergence.
- Solar remained an encounter, ignition, healing/support, and damage specialist.
- Arc had fewer cards but meaningful endgame and boss validation.
- Stasis had unusually strong evidence quality per card.
- Strand separated into durable Threadling/swarm roles and temporary bug/artifact damage branches.

These are historical conclusions from that dataset, not permanent 2026-and-beyond truth. Reverify before using them to dismantle anything. The detailed page-by-page notes are in `docs/research/Warlock-Creator-Build-Research-v2.4.md`.

---

## 10. Source quality and reacquisition cost

Source value does not make a bad roll good, but it changes the deletion threshold.

### 10.1 Protect costly sources

Give stronger review protection to:

- Dungeon-exclusive weapons and Exotics.
- Raid weapons.
- Trials, Adept, limited-event, retired, or currently unobtainable gear.
- Crafted or enhanced weapons requiring significant investment.
- Weapons requiring a specific encounter, key, rotation, difficulty, checkpoint, or coordinated team.

### 10.2 Dungeon rule

Do not confuse:

- **Dungeon-exclusive source:** obtainable only from a dungeon.
- **Dungeon use:** merely appears in a dungeon build or card.

A dungeon-exclusive item is not automatic immunity. It requires a stronger, well-documented deletion case that includes the encounter, access, farmability, RNG, and reacquisition time.

### 10.3 Source ordering

Use this order:

1. Does the roll provide a real role?
2. Is that role covered better elsewhere?
3. What meaningful tradeoff would be lost?
4. How hard is the item to reacquire?
5. Does personal investment or use justify protection?

Source is a strong tiebreaker, not a substitute for quality analysis.

---

## 11. Required vault-analysis workflow

### Step 1 — Ingest and validate

- Use the newest export.
- Record file name, date, row count, unique names, duplicate groups, Tier distribution, and SHA-256.
- Confirm the DIM columns and item-ID format.

### Step 2 — Protect metadata

Separate user-created metadata from known AI-generated tags/notes. Preserve favorites, keeps, locks, loadouts, crafted items, holofoils, kill counts, and sentimental notes.

### Step 3 — Group comparisons

Start with exact same-name, same-hash/version copies. Then build broader coverage groups by weapon type, exact frame, element, slot/ammo, range, Champion role, origin trait, and build function.

### Step 4 — Enumerate configurations

For every serious candidate and retained replacement, enumerate legal perks and useful component configurations. Tier 5 weapons require legal-combination coverage rather than currently selected perks.

### Step 5 — Assign roles

Map every useful configuration to actual roles and activities. Include portable and class/build-adjusted roles.

### Step 6 — Calculate practical packages

Use fully upgraded potential when Brent would reasonably invest. Compare final stats, timings, recoil behavior, magazines, reserves, and rotation behavior.

### Step 7 — Apply current community evidence

Use current Community Insights, official perk behavior, strong creator evidence, and community-supported god rolls. Wishlist absence is neutral. Verify time-sensitive facts online.

### Step 8 — Apply dominance and coverage rules

A candidate can be high-confidence only when the retained item covers its meaningful roles without losing essential frame, element, origin-trait, source, class/build, personal, or stat-package value.

### Step 9 — Assign confidence

- High: explainable same-version redundancy or exact duplicate.
- Medium: strong candidate with a minor or preference-dependent tradeoff.
- Low: Manual Review only.

### Step 10 — Produce audit and DIM proposal

For each candidate include:

- Weapon name.
- Candidate item ID and weapon hash/version.
- Candidate tier, frame, firing behavior, element, origin traits, perks, component highlights, Masterwork, and relevant final stats.
- Candidate portable and active-build roles.
- Retained replacement item ID and corresponding details.
- Exact coverage argument.
- Lost tradeoff, if any.
- Source, obtainability, and reacquisition cost.
- Positive metadata/personal signals.
- Confidence and review instruction.

Never produce only a naked list of item IDs.

---

## 12. DIM import rules

Required CSV fields normally include:

- `Id`
- `Notes`
- `Tag`
- `Hash`

For a proposed cleanup import:

- Use `junk` only for candidates Brent is meant to review.
- Put the reason and retained replacement in `Notes`.
- Preserve all unrelated user metadata.
- Keep current proposals in `DIM-Imports/proposed/`.
- Move superseded proposals to `DIM-Imports/archive/`.
- Store metadata backups in `DIM-Imports/metadata-backups/`.
- Record the export checksum and proposal date.

DIM cannot dismantle gear. Tagging is a reversible review workflow; dismantling is not.

---

## 13. Current repository state

### Permanent baseline

- File: `Vault-Exports/baseline/2026-07-18-DIM-Weapons-Permanent-Baseline.csv`
- SHA-256: `26a046a058528a7b9d824f53306fc5447ccb4cdd2b0f405297bd458351ffc9bd`
- Weapons: 1,035
- Unique names: 495

### Current working snapshot

- File: `Vault-Exports/latest/2026-07-19-DIM-Weapons-Current.csv`
- SHA-256: `6d5226e6e50801155f61a4b667debfba4a22ed67a3119d402a4fa09963c08f40`
- Weapons: 1,073
- Unique names: 500
- Duplicate-name groups: 231
- Copies beyond one per name: 573
- Tier 5 weapons: 105

### Active proposed import

- `DIM-Imports/proposed/DIM-Import-Junk-God-Roll-Validated-7-2026-07-19.csv`
- Contains seven conservative candidates.
- Older eight-item and 38-item files are archived and are not current recommendations.
- The 16 cross-version candidates remain a hold/manual-revalidation set.

### Permanent special protections already recorded

- Preserve the 600-draw Neoptolemus II role.
- Preserve No Hesitation with Demolitionist + Desperate Measures as a coherent grenade/damage loop pending broader role comparison.
- Preserve every functional Eager Edge category until deliberate consolidation leaves at least one appropriate movement option.
- Do not penalize new or untested weapons for zero kills or missing metadata.

---

## 14. Durable examples and lessons

### 14.1 The Call

Brent's favored The Call demonstrated that personal feel can come from the entire package: responsive handling/reload, useful magazine size, fewer interruptions, and a coherent grenade/damage loop. Do not infer preference from main perks alone.

### 14.2 Elsie's Rifle

A hard-hitting archetype can become a favorite when the roll fixes sluggish handling/reload and supplies accuracy or cadence benefits. Recoil Direction alone does not explain feel; Stability, accuracy effects, magazine, handling, cadence, and input method interact.

### 14.3 Scathelocke

A Tier 5 copy can dominate all main-perk combinations while a lower-tier copy still owns a meaningful stat package. Complete perk dominance does not automatically mean definite deletion. Compare the best achievable range, stability, handling, reload, recoil behavior, and archetype breakpoints.

### 14.4 Nessa's Oblation

A Void Pinpoint Slug does not automatically replace useful Void pellet shotgun frames. Exact firing behavior is a first-class coverage dimension.

### 14.5 No Hesitation

A strong Physic + Incandescent No Hesitation can serve as a Solar support/add-clear benchmark, while another copy may remain valuable for a distinct offensive, ability, or higher-difficulty role. “BIS for one role” does not mean “keep exactly one copy” until all selectable combinations and roles are compared.

### 14.6 Hunter reload lesson

A Hunter build with Marksman's Dodge may prefer a utility-plus-damage primary over a reload-plus-damage primary. The same conclusion may not hold for a portable all-class roll, and it does not erase passive reload or magazine-extension value in special/heavy rotations.

---

## 15. Current build-library guidance

Maintain two different libraries:

### Durable engine library

Long-lived build families supported by mechanics and current evidence, such as subclass engines, survivability loops, control loops, and broadly useful damage rotations.

### Encounter solution library

Exact answers for a particular GM, dungeon encounter, raid phase, solo route, modifier set, or boss. Encounter solutions should not become universal defaults without evidence.

For every saved build, record:

- Date and sandbox.
- Class/subclass and Exotic armor.
- Activity/encounter/difficulty.
- Artifact or bug dependency.
- Required weapon functions, not just example weapon names.
- Alternate weapons that satisfy the same function.
- Execution burden and recovery after failure.

This prevents one creator's example weapon from being misread as a mandatory vault keeper.

---

## 16. New-player or friend onboarding

Before applying these rules to another player, ask:

1. Which classes and subclasses are actually played?
2. Which Exotic armor and build loops are preferred?
3. Which activities matter most?
4. Controller or mouse and keyboard?
5. Which weapon types and exact frames feel good or bad?
6. What cleanup risk is acceptable?
7. Simple reliable loops or high-execution rotations?
8. Which raids, dungeons, keys, Trials, and endgame farms are accessible?
9. How willing is the player to reacquire difficult gear?
10. Which items have personal, crafted, sentimental, or high-kill value?
11. Which class/build reload sources materially affect weapon perk choices?

Do not import Brent's preferences into another player's inventory.

---

## 17. Verification checklist for future sessions

Before a major deletion pass, verify any fact that may have changed:

- Current patch and sandbox.
- Perk descriptions and activation rules.
- Tier behavior and enhancement rules.
- Champion interactions.
- Artifact perks and activity modifiers.
- Archetype tuning and falloff behavior.
- Class ability and Exotic armor behavior.
- Super-generation rules.
- Source availability and loot tables.
- DIM export/import format.
- Creator recommendation date and underlying activity.

Mechanics around or after the repository's July 2026 source window require fresh research.

---

## 18. Recommended resume prompt

> Continue Brent's Destiny 2 vault cleanup using the active canonical bootstrap and newest DIM export. Preserve user metadata and positive personal signals; treat zero kills and missing tags as neutral. Enumerate Tier 5 legal configurations, compare exact versions/frames/elements/origin traits and full configured stat packages, and evaluate portable plus class/build-adjusted value—especially Hunter reload interactions. Use current community evidence and official mechanics, protect source/reacquisition cost and meaningful coverage, and produce only an auditable conservative DIM proposal with retained replacements and explicit tradeoffs.

---

## 19. Final guiding principle

The wrong question is:

> Which roll has the highest wishlist score?

The right question is:

> Which items provide distinct practical value for Brent across the activities, classes, builds, roles, and rotations he actually uses—and which items are genuinely redundant after every legal configuration, functional stat package, coverage dimension, source cost, and personal signal has been considered?

That is the standard for all future vault cleanup.

---

## 20. Reference map

- Recoil Direction: `docs/Recoil-Direction-Mechanics.md`
- Hunter/class reload valuation: `docs/Class-Adjusted-Reload-and-Sustain.md`
- Super economy and Bad Juju: `docs/Super-Economy-and-Bad-Juju.md`
- Dungeon/source protection: `docs/Dungeon-and-Source-Protection.md`
- Frame/origin-trait coverage: `docs/Frame-Intrinsic-and-Origin-Trait-Coverage.md`
- God-roll/synergy/metadata policy: `docs/God-Roll-Perk-Synergy-and-Metadata-Policy.md`
- Detailed v2.4 creator research: `docs/research/Warlock-Creator-Build-Research-v2.4.md`
- Full legacy bootstrap: `docs/history/Brents-Destiny-2-AI-Bootstrap-v2.4.1-Legacy.md`
- Optimization report: `docs/Bootstrap-Optimization-Report-v2.5.md`
