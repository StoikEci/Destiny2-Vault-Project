# State Reconciliation Protocol

**Repository version introduced:** 2.8  
**Updated:** July 25, 2026  
**Status:** Required update protocol for active project knowledge

## 1. Why this exists

The repository contains several kinds of state that change at different speeds:

- Brent's current preferences and explicit corrections.
- The newest DIM inventory export.
- Current Destiny mechanics and sandbox behavior.
- Creator/community evidence.
- Active bootstrap summaries.
- Historical analyses and archived recommendations.

A bootstrap is a **cache of project knowledge**, not the ultimate source of truth. The failure mode this protocol prevents is simple: an old active sentence gets copied into a new release even though Brent has already changed the weapon or corrected the assumption.

Treat meaningful updates like a small database transaction: identify the authoritative change, write it to the right source, update every dependent view, validate consistency, and preserve history.

## 2. Source-of-truth map

- **Project purpose and success metrics:** `docs/Project-North-Star.md`
- **Brent's current preference, experience, or intent:** `docs/Brent-Personal-Evidence-Ledger.md`
- **Current inventory and exact item configuration:** newest DIM export
- **Current game behavior:** verified current mechanics
- **How the AI should reason:** `docs/Brent-Decision-Doctrine.md`
- **Active operating summary:** `Brents-Destiny-2-AI-Bootstrap.md`
- **Human-readable story:** `Brents-Destiny-2-Human-Bootstrap.md`
- **Historical provenance:** `docs/history/`, archived analyses, and changelog

No single file is authoritative for every kind of claim.

## 3. Events that trigger reconciliation

Run this protocol when any of the following occurs:

- Brent says “I changed,” “I recrafted,” “I prefer,” “that is wrong,” “I no longer use,” or equivalent.
- A new DIM export is added.
- A class, subclass, Exotic, artifact, perk, frame, or source mechanic changes.
- A creator-backed benchmark is replaced by newer evidence.
- An active recommendation is reversed.
- Brent reframes the project goal, success metrics, or priority order.
- A bootstrap, North Star, doctrine, ledger, or broad policy is rewritten.
- A new repository release is packaged.

## 4. Reconciliation transaction

### Step 1 — Capture the new fact without embellishment

Write down exactly what is known. Separate:

- Brent's words.
- Inventory observation.
- Verified mechanic.
- AI interpretation.
- Unknown details.

Do not add a perk, date, causal explanation, or configuration that was not actually established.

### Step 2 — Assign provenance and status

Create or update a Personal Evidence Ledger entry with a stable ID. Mark it Active, Contextual, Historical, Tentative, Superseded, or Open Question.

### Step 3 — Identify conflicts

Search for the subject across:

- Project North Star.
- AI bootstrap.
- Human bootstrap.
- Doctrine and policy references.
- Current analysis summaries and candidate audits.
- Templates and resume prompts.
- Changelog and release notes.

Classify each occurrence:

- Still correct.
- Correct but incomplete.
- Historical and properly labeled.
- Stale/conflicting.
- Unsupported assistant inference.

### Step 4 — Update active views

Update the Project North Star when purpose or priorities change. Update the AI bootstrap with full operational consequences. Update the human bootstrap when the change helps explain the story or a major lesson. Update policy documents when the change affects a general rule.

### Step 5 — Scan affected decisions

A changed fact may invalidate more than a sentence. Ask:

- Did any keep/delete recommendation rely on the old assumption or old project objective?
- Did a prior analysis optimize for space/retention instead of build power and enjoyment?
- Did the old assumption affect role coverage, Tier dominance, or a retained replacement?
- Does a current DIM proposal contain the weapon or related copies?
- Should a candidate move to Manual Review pending a new export?

Record affected decisions even when no immediate change is required.

### Step 6 — Preserve history

Do not silently overwrite the old state when it explains previous analysis. Preserve the prior bootstrap under `docs/history/` and retain historical ledger context.

### Step 7 — Validate

Run the release gates in Section 6. No release is complete merely because the Markdown renders.

### Step 8 — Commit as one logical change

Use a clear commit message that describes the knowledge change, not just “update files.” Example:

`Record Reconstruction preference and add reasoning doctrine`

## 5. Conflict resolution examples

### New explicit preference versus old bootstrap

New explicit preference wins for player-fit conclusions. The old bootstrap statement becomes Historical or is rewritten as chronology.

### New DIM export versus Brent's statement

The export wins for exact current perks and item IDs. Brent's statement wins for why he likes or dislikes the result. If they conflict, verify whether the export predates the change.

### Verified mechanic versus Brent's explanation

Correct the mechanic while preserving the preference. Brent can prefer the outcome even if the causal explanation was mistaken.

### Assistant statement versus no supporting source

Mark it UNVERIFIED. Do not propagate it into active documents. Example: a previously asserted current fourth-column perk on The Call must not become fact without confirmation.

### Creator consensus versus Brent's experience

Creator evidence can establish broad mechanical strength; Brent's experience establishes fit. Record both. Do not force either to answer the other's question.

## 6. Release gates

Before packaging a repository update, verify:

1. **Version gate:** Both root bootstraps and release documents show the intended version.
2. **Authority gate:** Active personal claims have ledger IDs and no conflicting active statements.
3. **Inventory gate:** Current-item claims identify the export date or explicitly state that the export may be stale.
4. **Inference gate:** AI inferences are not written as Brent quotes or direct statements.
5. **History gate:** Prior active bootstraps are preserved when materially changed.
6. **Reference gate:** README, manifest, templates, and bootstrap reference maps point to the Project North Star, doctrine, ledger, and protocol.
7. **Decision-impact gate:** Existing active DIM proposals are checked for dependence on changed assumptions or project-goal priorities.
8. **Data-integrity gate:** Vault exports, DIM imports, and analysis files are unchanged unless the release intentionally changes them.
9. **Checksum gate:** A new checksum manifest is generated after all edits.
10. **Stale-phrase gate:** Search for known superseded phrases and unsupported details.

## 7. Stale-phrase and contradiction checks

For each changed subject, create a small validation list. For the July 25 The Call update, active files should:

- Mention Reconstruction as the current stated perk.
- Mention the approximately 30-micro-missile stowed result as Brent's report.
- Treat the older Subsistence configuration as historical.
- Avoid asserting an unconfirmed current fourth-column perk.
- Note that the July 19 DIM export may predate the recraft.

Automated text checks cannot prove correctness, but they catch many copy-forward failures.

## 8. Decision receipts and traceability

Deletion audits should reference:

- Personal Evidence Ledger IDs.
- Current export filename/checksum.
- Verified mechanic date/source when material.
- Defined role and retained replacement.
- What would reverse the decision.

This creates a trace from Brent's statement to the active policy to the final recommendation.

## 9. Rollback rule

If a release is found to have over-compressed, invented, or incorrectly propagated information:

- Do not patch blindly from the flawed file.
- Return to the last trusted baseline.
- Reapply valid changes through this protocol.
- Preserve the flawed release as history only when useful for audit; do not let it remain an active source.

## 10. Final principle

**New information is not integrated merely because someone remembers it. It is integrated when provenance is recorded, conflicts are resolved, dependent decisions are checked, and the active repository passes validation. A goal reframe is the highest-impact kind of update because it changes how every later fact is valued.**
