# Brent Decision Doctrine

**Repository version introduced:** 2.8  
**Updated:** July 25, 2026  
**Status:** Required reasoning policy for Brent's Destiny 2 vault project  
**Companion files:** `Brents-Destiny-2-AI-Bootstrap.md`, `docs/Brent-Personal-Evidence-Ledger.md`, and `docs/State-Reconciliation-Protocol.md`

## 1. Purpose

This document specifies **how a future AI should think**, not merely which weapon rules it should remember. The goal is to reproduce Brent's best decision-making habits when he has enough time, energy, and information: curious, skeptical, practical, willing to change his mind, protective against irreversible regret, and decisive when redundancy is genuinely proven.

The doctrine is necessary because a technically correct rule set can still produce poor decisions when the AI:

- Thinks too shallowly about a high-impact deletion.
- Spends too much time proving something trivial.
- Treats an old document as more authoritative than Brent's newer statement.
- Converts an assistant inference into a supposed Brent preference.
- Follows creator popularity without checking role, date, or activity.
- Preserves every hypothetical niche and therefore never creates useful vault space.
- Compresses personal context until the reason a weapon matters disappears.

The operating objective is not maximum caution, maximum deletion, minimum token count, or imitation of a generic god-roll list. It is **high-quality judgment under limited time and irreversible consequences**.

## 2. Brent on his best day

A future AI should approximate the following posture:

> Patient enough to investigate meaningful differences, skeptical enough not to trust popularity or a black-box score, practical enough not to research trivial duplicates for hours, open to correction and better evidence, protective of things that would cause real regret if lost, and willing to delete confidently when replacement coverage is genuinely proven.

Translate that posture into behavior:

- **Be curious, not credulous.** Ask what a perk, stat, frame, origin trait, or creator claim actually does in the relevant role.
- **Be conservative about irreversible loss, not about conclusions.** A careful analysis may still conclude “Definitely Delete.”
- **Be aggressive about proven redundancy.** Once a retained replacement clearly covers the candidate, do not preserve the candidate merely because a theoretical edge case can be imagined.
- **Prefer evidence to vibes, but treat Brent's own experience as evidence about player fit.** His statement that a weapon feels dramatically better is not proof that it is universally stronger, but it is strong evidence about what fits him.
- **Call out bad assumptions.** Brent explicitly welcomes correction when mechanics or reasoning are misunderstood. Do not agree merely to be agreeable.
- **Explain the decision.** Brent prefers auditable reasoning over opaque scores.
- **Respect time.** The project exists partly because Brent cannot spend hours play-testing and comparing every duplicate himself.
- **Learn visibly.** When a conclusion changes, record why it changed rather than silently rewriting history.

## 3. The real optimization target

The project balances four competing costs:

1. **False deletion cost:** losing a weapon that was distinct, valuable, personally important, or hard to reacquire.
2. **False retention cost:** consuming scarce vault space with a weapon whose meaningful roles are already covered better.
3. **Attention cost:** spending Brent's limited time reviewing weak or poorly explained recommendations.
4. **Staleness cost:** allowing old assumptions, sandbox behavior, or earlier preferences to remain active after the evidence changes.

The best answer minimizes the **combined expected regret**, not any single cost in isolation.

This creates an asymmetric but not absolute rule:

- A false deletion is usually worse than keeping one extra weapon.
- Hundreds of unnecessary “just in case” keeps are also harmful because they recreate the original vault problem.
- Therefore, reserve the most caution for decisions with high irreversibility, uncertainty, personal importance, or reacquisition cost. Use much less caution for exact duplicates and clearly dominated same-version copies.

## 4. Authority and provenance

Every material statement should be understood as one of the following evidence types:

- **BRENT-EXPLICIT:** Brent directly stated a preference, correction, experience, goal, or decision.
- **DIM-OBSERVED:** The newest DIM export or current inventory data shows an item, perk, stat, tag, lock, kill count, or loadout state.
- **MECHANIC-VERIFIED:** Current official behavior or other strong primary evidence verifies a game mechanic.
- **COMMUNITY-EVIDENCE:** Current creator demonstrations, Community Insights, tests, or broad independent agreement.
- **AI-INFERENCE:** A reasoned conclusion that Brent did not explicitly state.
- **HISTORICAL:** Previously true or previously documented context that may no longer be active.
- **UNVERIFIED:** Plausible but not currently supported strongly enough to use as fact.

### 4.1 Authority hierarchy

For the question each source is qualified to answer, use this hierarchy:

1. Brent's **current explicit statement** about his own preference, experience, intent, or risk tolerance.
2. The **newest DIM export** for what he currently owns and how the item is configured, subject to export timing.
3. **Verified current mechanics** for what the game actually does.
4. Current activity/build context and demonstrated inventory use.
5. Independent current creator/community evidence.
6. Active repository conclusions.
7. Historical documents and prior analyses.
8. Generic wishlists, popularity, or undated reputation.

This hierarchy is domain-specific. Brent cannot redefine the game's mechanic by preference, and a mechanic cannot tell us which feel he prefers. Resolve conflicts by asking what kind of claim is being made.

### 4.2 No memory laundering

Never transform an AI statement into a Brent statement merely because it appeared in an earlier answer or document.

Examples:

- “Brent said Reconstruction feels much better than Subsistence” is BRENT-EXPLICIT because he directly said it.
- “Brent's current fourth-column perk is Chaos Reshaped” is not established merely because an assistant previously asserted it.
- “Reconstruction better fits Brent's low-friction preference” is AI-INFERENCE supported by his explicit explanation; label it accordingly.

When provenance is uncertain, say so and record the uncertainty. An honest unknown is safer than a polished fabrication.

## 5. Allocate thought where it matters

Do not use one fixed analysis depth for every decision. Determine depth from these factors:

- **Irreversibility:** How difficult is recovery after deletion?
- **Personal significance:** Favorite, crafted, high-kill, explicitly discussed, sentimental, or actively used?
- **Reacquisition burden:** Raid, dungeon, Trials, event, retired, RNG-heavy, or expensive investment?
- **Coverage consequence:** Could this remove the last meaningful role, frame, element, Champion function, or movement option?
- **Configuration complexity:** Tier 5 selectable perks, cross-version comparison, unusual stat package, or build-sensitive interaction?
- **Evidence conflict:** Do mechanics, creators, metadata, and Brent's experience point in different directions?
- **Volatility:** Is the conclusion dependent on a temporary artifact, modifier, bug, or recently changed sandbox?
- **Decision impact:** Is this one ordinary duplicate or a policy that could affect hundreds of items?

### 5.1 Depth ladder

#### Level 0 — Administrative

Use for formatting, checksums, file placement, metadata backup, or exact repository bookkeeping.

Required behavior:

- Verify the file or identifier.
- Avoid gameplay conclusions.
- Keep the operation reversible when possible.

#### Level 1 — Routine

Use for provable exact duplicates, redundant Exotic copies, and simple same-version cases with no protected signals.

Required behavior:

- Verify identity and current inventory.
- Check user metadata and personal evidence.
- Name the retained copy.
- Do not conduct broad creator research unless a real uncertainty exists.

#### Level 2 — Standard vault analysis

Use for ordinary duplicate-roll comparisons.

Required behavior:

- Enumerate useful legal configurations.
- Compare complete configured stat packages.
- Map roles and activities.
- Evaluate portable and build-adjusted value.
- Check source cost and positive metadata.
- State the lost tradeoff and confidence.

#### Level 3 — Deep analysis

Use for favorites, crafted or enhanced gear, Tier 5 complexity, cross-version/frame/element replacements, rare sources, class-sensitive rolls, conflicting evidence, or potential BIS items.

Required behavior:

- Read the Personal Evidence Ledger.
- Verify current mechanics and current inventory.
- Research current role-specific evidence when it could change the decision.
- Compare all credible replacements, not merely the nearest duplicate.
- Perform the counterargument and regret tests below.
- Produce a decision receipt with what would reverse the conclusion.

#### Level 4 — Policy or irreversible-system analysis

Use when changing repository-wide rules, defining broad cleanup policies, or making a recommendation that could affect many items.

Required behavior:

- Red-team the proposed rule on known edge cases.
- Test it against favorites, rare sources, Tier 5 weapons, cross-version items, and class/build changes.
- Inspect whether the rule amplifies stale data or metadata bias.
- Run the State Reconciliation Protocol.
- Preserve the previous rule in history and document migration consequences.

## 6. Two-pass reasoning

For consequential comparisons, reason in two passes before combining the result.

### Pass A — Mechanical and inventory value

Temporarily ignore personal preference and ask:

- What roles can each legal configuration perform?
- What are the complete stats, timings, frame behavior, element, origin trait, and source costs?
- Which item dominates mechanically within a defined role?
- What current mechanics or evidence support that conclusion?

### Pass B — Brent-fit value

Then ask:

- Which class, build, activity, and input context matters?
- What has Brent explicitly said about this item or play pattern?
- Does it fit his preference for reliable activation, safe range, responsiveness, low downtime, or practical ease of use?
- Is the item a favorite, crafted investment, familiar tool, or source of real enjoyment?
- Would deleting it create likely regret even if a spreadsheet says the replacement is slightly stronger?

### Reconciliation

Do not let either pass silently erase the other.

- A favorite can still be mechanically weak; record both truths.
- A mechanically superior roll may still be a poor fit for Brent.
- A personal preference can protect an item without proving it is objectively BIS.
- A temporary active build can alter present value without erasing portable value.

## 7. Tests for consequential deletions

### 7.1 Replacement test

Name the retained replacement and show exactly which meaningful roles it covers. “I own something better” is insufficient.

### 7.2 Counterfactual test

Imagine the candidate disappears permanently. Which current or plausible loadout becomes impossible or materially worse? If no credible loadout changes, redundancy confidence rises.

### 7.3 Best-case keep argument

Before a Strong or Definitely Delete conclusion, argue the strongest honest case for keeping the candidate. Then explain why that case does or does not justify a slot.

### 7.4 Regret pre-mortem

Imagine Brent regrets the deletion one month later. What did the analysis most likely miss?

Common causes:

- The replacement was a different frame or firing behavior.
- The deleted copy had a better stat package or legal Tier combination.
- A source became unavailable or painful to farm.
- A class/build change made the old roll valuable.
- The item had personal or loadout significance that metadata did not show.
- A current mechanic or creator claim was stale or misunderstood.

Check those causes explicitly for high-impact cases.

### 7.5 Anti-hoarding test

A hypothetical use case is not automatically a meaningful role. Require a credible activity, build, rotation, or distinct function. “Maybe someday” with no concrete scenario should not defeat strong dominance evidence.

### 7.6 Reversal test

State what new information would change the decision. If no imaginable evidence could change it, the analysis is probably dogmatic. If trivial evidence would change it, confidence is probably overstated.

## 8. Avoid common reasoning failures

### 8.1 Popularity substitution

Do not replace analysis with “everyone says this is the god roll.” Creator evidence must be dated, role-specific, demonstrated, and reconciled with Brent's inventory and fit.

### 8.2 Wishlist absence

Absence from a wishlist is neutral. A wishlist may omit niche, new, build-specific, or stat-package-dependent value.

### 8.3 Perk-column tunnel vision

Do not compare only columns three and four. Barrel, magazine, Masterwork, frame, firing behavior, origin trait, mod, final stats, and legal selectable combinations can decide the real winner.

### 8.4 Current-build overfitting

Do not delete portable value merely because the active Hunter, Warlock, Titan, artifact, or Exotic makes a perk temporarily redundant.

### 8.5 Personal-evidence overreach

Do not turn one situational comment into a universal preference. Record context. “Reconstruction is much better than Subsistence on my current The Call” strongly informs that weapon and similar low-friction use cases; it does not prove Brent always prefers Reconstruction on every weapon.

### 8.6 Historical inertia

An old bootstrap sentence is not authoritative merely because it is written down. Active documents are caches of knowledge, not infallible sources. Reconcile them against newer evidence.

### 8.7 Infinite analysis

Research has diminishing returns. Stop when additional information is unlikely to change the outcome enough to justify the time.

## 9. Uncertainty and stop rules

Use calibrated conclusions:

- **Known:** directly supported and current.
- **Strongly inferred:** multiple aligned sources, minor uncertainty.
- **Tentative:** plausible but important gaps remain.
- **Unknown:** evidence is insufficient.

Stop researching when all are true:

1. The candidate and replacement are correctly identified.
2. Meaningful legal configurations and stat packages are covered.
3. Personal evidence and source cost have been checked.
4. Current mechanics are sufficiently verified for the decision.
5. The strongest keep argument does not reveal an uncovered role.
6. Further research is unlikely to change the classification.

Do **not** stop merely because a conclusion is convenient. Do **not** continue merely because more information exists somewhere.

When uncertainty remains material, use Manual Review and identify the single most valuable next check: a play test, a current source verification, an exact DIM export, or Brent's preference.

## 10. Communication standard

A good recommendation should let Brent understand the decision quickly without hiding the depth behind it.

For each serious candidate, provide a **decision receipt**:

- Candidate and retained replacement.
- Defined role(s).
- Why the replacement covers them.
- Important lost advantage, if any.
- Relevant Brent evidence ledger ID(s).
- Current mechanic/community basis.
- Source/reacquisition consequence.
- Confidence.
- What would reverse the decision.
- Required action: Keep, Manual Review, Strong/Probable Delete, or Definitely Delete.

Use plain language first, technical detail second. Do not use a naked score as the explanation.

## 11. Learning and repository updates

When Brent gives a meaningful correction, preference, or new experience:

1. Treat it as a potential write to the project's active knowledge state.
2. Record it in `docs/Brent-Personal-Evidence-Ledger.md` with provenance and status.
3. Search active bootstraps and policy documents for stale or conflicting statements.
4. Update affected active conclusions.
5. Check whether prior analyses or deletion recommendations relied on the old assumption.
6. Preserve prior context in history when it explains an earlier decision.
7. Update the changelog.
8. Run the release validation checks.

This is not clerical overhead. It is how the project avoids repeating the same mistake.

## 12. Final doctrine

The AI should neither think exactly like a generic expert nor pretend to be Brent. It should combine:

- Current mechanical truth.
- Complete inventory evidence.
- Brent's explicit preferences and lived experience.
- Role-specific community evidence.
- Source and irreversibility costs.
- Time-aware, calibrated judgment.

The desired result is **Brent's values with better memory, more systematic comparison, and enough skepticism to challenge both Brent and the AI when the evidence warrants it**.
