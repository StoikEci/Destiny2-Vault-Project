# Brent Personal Evidence Ledger

**Repository version introduced:** 2.8  
**Updated:** July 25, 2026  
**Status:** Active source of truth for Brent-specific statements, corrections, preferences, and learned player-fit evidence  
**Reasoning policy:** `docs/Brent-Decision-Doctrine.md`  
**Update protocol:** `docs/State-Reconciliation-Protocol.md`

## 1. Purpose

This ledger records things Brent explicitly says or clearly demonstrates that can materially change vault analysis. It exists to prevent personal knowledge from being:

- Lost during bootstrap optimization.
- Buried inside old conversation history.
- Replaced by an assistant's inference.
- Left stale after Brent changes a weapon, class, build, or opinion.
- Overgeneralized beyond the context in which Brent said it.

This is **not** a diary and is not a place for every casual remark. Add an entry when the information could change a keep/delete decision, evidence weighting, workflow, or communication style.

## 2. Entry rules

Each entry should include:

- **ID:** Stable identifier that analyses can cite.
- **Date/source:** When and where the information came from, if known.
- **Evidence type:** BRENT-EXPLICIT, DIM-OBSERVED, AI-INFERENCE, HISTORICAL, or UNVERIFIED.
- **Status:** Active, Contextual, Superseded, Historical, Tentative, or Open Question.
- **Scope:** Weapon, build, class, activity, workflow, or general preference.
- **Statement:** What Brent said or what the evidence shows.
- **Interpretation:** The analytical consequence, clearly labeled when inferred.
- **Supersedes/related:** Older entries or document statements affected.
- **Do not overgeneralize:** Limits on how broadly the entry should be applied.

A current explicit statement can supersede an older active conclusion. Preserve the old context as Historical when it explains prior decisions.

## 3. Active entries

### BPEL-2026-07-25-001 — The Call now uses Reconstruction

- **Date/source:** July 25, 2026; Brent's explicit statement in the current project conversation.
- **Evidence type:** BRENT-EXPLICIT.
- **Status:** Active.
- **Scope:** The Call; crafted-weapon preference; reload and magazine behavior.
- **Statement:** Brent recrafted his favorite The Call with **Reconstruction**. He says it is “great” and “way better than Subsistence” for him because Reconstruction can load the weapon while it is stowed instead of requiring kills. He reports being able to pull it out with approximately **30 micro-missiles**, compared with its normal magazine of roughly 15.
- **Active conclusion:** The current preferred The Call should be evaluated as a proactive, stow-to-load, oversized-magazine weapon. Its appeal is immediate readiness, extended firing, weapon-swap compatibility, and no kill requirement.
- **AI-INFERENCE:** This strongly fits Brent's broader preference for reliable activation, low downtime, and weapons that prepare themselves during normal play.
- **Supersedes:** The active description that centered the favorite roll on Subsistence and a grenade/damage loop.
- **Historical context:** Earlier repository material documented a crafted Tier 5 The Call with Countermass, Flared Magwell, Subsistence, Adrenaline Junkie, Backup Mag, 15 magazine, and thousands of kills. That remains useful history but is no longer the active configuration description.
- **Open fact:** Brent did **not** identify the current fourth-column perk in the authoritative July 25 statement. Do not infer or record **Chaos Reshaped** as current fact unless Brent or a newer DIM export confirms it.
- **Inventory caution:** The July 19 DIM snapshot may predate the recraft. Use a newer export before relying on exact current perks, components, or item state.
- **Do not overgeneralize:** This does not prove Reconstruction is always better than Subsistence on every weapon. It is strong direct evidence for The Call and for similar low-friction, swap-friendly use cases.

### BPEL-2026-07-18-001 — Older The Call configuration and why it mattered

- **Date/source:** July 18, 2026; prior project conversation and repository records.
- **Evidence type:** HISTORICAL plus DIM-OBSERVED at the time.
- **Status:** Historical; superseded as the active configuration by BPEL-2026-07-25-001.
- **Scope:** The Call.
- **Statement:** Brent's earlier favorite crafted Tier 5 The Call was documented with Countermass, Flared Magwell, Subsistence, Adrenaline Junkie, Backup Mag, 15 magazine, and approximately 3,550 kills. He valued the complete feel package rather than only the main perks.
- **Analytical consequence:** Preserve the lesson that familiarity, handling, reload, stability, magazine behavior, projectile feel, and coherent perk interaction all matter. Do not preserve Subsistence as his current preference.
- **Do not overgeneralize:** Historical kill count and configuration should not be treated as current inventory without a new export.

### BPEL-2026-07-18-002 — Full stat packages matter

- **Date/source:** July 18, 2026; Brent's explicit project guidance.
- **Evidence type:** BRENT-EXPLICIT.
- **Status:** Active durable preference.
- **Scope:** All weapon comparisons.
- **Statement:** Barrel, magazine, and Masterwork choices can matter hugely, especially on weapons with low range or stability. Main-perk comparisons alone are inadequate.
- **Analytical consequence:** Compare the complete configured weapon, including final stats and archetype-specific timings, before declaring dominance.
- **Related:** The Call is a Rocket-Assisted/Micro-Missile sidearm; ordinary sidearm range assumptions should not be applied blindly to its projectile behavior.

### BPEL-2026-07-18-003 — Range sensitivity and sidearm caveat

- **Date/source:** July 18, 2026; Brent's explicit statement.
- **Evidence type:** BRENT-EXPLICIT.
- **Status:** Active contextual preference.
- **Scope:** Conventional sidearms and low-range weapons.
- **Statement:** Conventional sidearms below roughly 30 Range are generally undesirable to Brent.
- **Analytical consequence:** Range deserves meaningful weight on ordinary sidearms, especially when a low-range roll has no compensating role.
- **Do not overgeneralize:** The Call and other unusual projectile weapons require archetype-specific evaluation; displayed Range may not map to ordinary sidearm behavior.

### BPEL-2026-07-18-004 — Welcome correction; do not flatter

- **Date/source:** July 18, 2026; Brent's explicit instruction.
- **Evidence type:** BRENT-EXPLICIT.
- **Status:** Active durable communication preference.
- **Scope:** Reasoning and communication.
- **Statement:** Brent wants the AI to call out bad reasoning or misunderstood mechanics. Corrections are welcome.
- **Analytical consequence:** Do not agree merely to be agreeable. State uncertainty, correct mistakes, and distinguish fact from inference.

### BPEL-2026-07-20-001 — Reacquisition risk is vital

- **Date/source:** July 20, 2026; Brent's explicit project preference.
- **Evidence type:** BRENT-EXPLICIT.
- **Status:** Active durable preference.
- **Scope:** Source protection and deletion confidence.
- **Statement:** Reacquisition difficulty is a vital part of cleanup decisions.
- **Analytical consequence:** Raid, dungeon, Trials, Adept, event, retired, crafted, enhanced, and RNG-heavy items require a stronger deletion case. Source cost is not immunity, but it changes the regret calculation.

### BPEL-2026-07-20-002 — Vault pressure and need for meaningful cleanup

- **Date/source:** July 20, 2026; Brent's explicit project context.
- **Evidence type:** BRENT-EXPLICIT.
- **Status:** Active contextual preference.
- **Scope:** Cleanup aggressiveness and attention allocation.
- **Statement:** Brent begins to feel vault pressure when he is within roughly 50 slots of the cap. He wants broad, efficient cleanup where a category is demonstrably overstocked, rather than preserving every speculative niche.
- **Analytical consequence:** The project should not collapse into endless Manual Review. After proving role coverage, it should be willing to consolidate aggressively, especially in bloated categories.
- **Do not overgeneralize:** Broad category reduction still requires protection for movement, rare sources, personal value, exact frames, and real role diversity.

### BPEL-2026-07-25-002 — Warlock history and resumed Hunter play

- **Date/source:** July 25, 2026 project state, based on Brent's explicit statements.
- **Evidence type:** BRENT-EXPLICIT.
- **Status:** Active contextual state.
- **Scope:** Class-adjusted valuation.
- **Statement:** Warlock has historically been Brent's most-developed class, but he has resumed playing Hunter.
- **Analytical consequence:** Evaluate portable value and active-build value separately. Hunter reload tools can reduce the relative value of pure manual-reload perks without erasing passive reload, overflow, sustain, or other-class value.
- **Do not overgeneralize:** Current Hunter use is a build state, not permission to delete all Warlock- or Titan-relevant rolls.

### BPEL-2026-07-25-003 — Personal statements must survive optimization

- **Date/source:** July 25, 2026; Brent's explicit repository-design preference.
- **Evidence type:** BRENT-EXPLICIT.
- **Status:** Active durable policy.
- **Scope:** Documentation and continuity.
- **Statement:** References to Brent's personal preferences and things he explicitly told the AI should be preserved rather than optimized away.
- **Analytical consequence:** Personal evidence is first-class project data. Compression may improve wording but must not erase meaning, chronology, or current status.

### BPEL-2026-07-25-004 — Separate AI and human bootstraps

- **Date/source:** July 25, 2026; Brent's explicit repository-design decision.
- **Evidence type:** BRENT-EXPLICIT.
- **Status:** Active durable policy.
- **Scope:** Repository architecture.
- **Statement:** Maintain one robust, detailed AI bootstrap and one human-readable bootstrap that tells the story with enough depth to appreciate the project without taking an hour to read.
- **Analytical consequence:** Do not shorten the AI file merely to serve human readability. Do not overload the human file with every operating detail.

### BPEL-2026-07-25-005 — Desired reasoning style

- **Date/source:** July 25, 2026; Brent's explicit request to build a doctrine that helps a future AI think like “Brent on his best day.”
- **Evidence type:** BRENT-EXPLICIT.
- **Status:** Active durable policy.
- **Scope:** AI reasoning.
- **Statement:** The repository should guide how much and how deeply an AI thinks, and how much importance it assigns to different aspects of the project.
- **Analytical consequence:** Use `docs/Brent-Decision-Doctrine.md`; allocate depth according to irreversibility, uncertainty, personal significance, source cost, configuration complexity, and policy impact.


### BPEL-2026-07-25-006 — Project goal reframe: builds first, armory second, space third

- **Date/source:** July 25, 2026; Brent's explicit “Project Goal Reframe – Immediate Update.”
- **Evidence type:** BRENT-EXPLICIT.
- **Status:** Active durable policy.
- **Scope:** Entire project; build strategy; deletion philosophy; prioritization; proactive recommendations.
- **Statement:** The ultimate goal is maximizing enjoyment and power in Destiny 2 by creating the strongest, most fun, and most capable builds possible so Brent can beat the content he cares about. The vault is only a tool in service of that goal and should function as a high-performance armory, not a museum or risk-avoidance system.
- **Success metrics:** Primary = “Does this help me make stronger and more enjoyable builds?” Secondary = inventory clarity and reduced decision fatigue. Vault space is a distant tertiary concern.
- **Deletion consequence:** Be more willing to delete clearly outclassed or redundant rolls when a superior option exists for the roles and build engines Brent actually uses and enjoys. Keep the strong protections for exact frames, origin traits, costly sources, and personal metadata, but do not let maximum retention override power and fun.
- **Build priority:** Prioritize weapons that complete or unlock powerful build engines, especially current Warlock engines, over pure theoretical coverage.
- **Proactive consequence:** Suggest what Brent should chase, craft, focus, enhance, catalyst, or test to unlock better builds. Every meaningful item analysis should ask: **“What new or stronger loadouts does keeping/deleting this enable?”**
- **Supersedes:** Earlier goal statements that framed rapid vault-space recovery as the primary project objective. Earlier safeguards remain active as constraints and confidence thresholds.
- **Do not overgeneralize:** This is not permission to ignore frames, origin traits, source cost, personal enjoyment, or portable value. It changes the optimization target and the burden of justification, not the mechanical truth.

## 4. Open questions and facts requiring confirmation

### BPEL-OPEN-001 — Current complete The Call configuration

- **Status:** Open Question.
- **Known:** Reconstruction is current and Brent reports approximately 30 loaded micro-missiles after stowing.
- **Unknown:** Current fourth-column perk, barrel, magazine, Masterwork, mod, exact displayed stats, item ID, and whether the newest export contains the recraft.
- **Best next source:** Brent's newest DIM weapons export or an explicit statement/screenshot.
- **Restriction:** Do not fill the gap from an earlier assistant answer.

### BPEL-OPEN-002 — Input method

- **Status:** Open Question when recoil- or PvP-sensitive analysis requires it.
- **Known:** The bootstraps require verification before input-sensitive recommendations.
- **Restriction:** Do not assume controller or mouse and keyboard from platform alone.

## 5. Supersession and correction rules

- An Active BRENT-EXPLICIT entry overrides a conflicting Historical entry about Brent's current preference or configuration.
- A newer DIM export overrides an older export for inventory state, but does not override Brent's explanation of why he likes something.
- Verified mechanics can correct a misunderstood causal explanation without invalidating the underlying preference.
- AI-INFERENCE must never silently become BRENT-EXPLICIT.
- When an entry changes, preserve the prior state as Historical or Superseded and identify affected analyses.

## 6. How analyses should cite this ledger

For a consequential recommendation, include relevant IDs in the decision receipt, for example:

- `Personal evidence: BPEL-2026-07-25-001`
- `Source-risk preference: BPEL-2026-07-20-001`

This makes the reasoning auditable and prevents a personal preference from being vaguely remembered or misquoted.
