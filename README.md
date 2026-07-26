# Brent's Destiny 2 Vault Project v2.7

This repository packages Brent's Destiny 2 vault-intelligence framework, current vault snapshots and analyses, reusable prompts, and preserved research history.

## Choose the right starting file

### For an AI continuing or performing vault analysis

Open:

`Brents-Destiny-2-AI-Bootstrap.md`

This is the authoritative operating file. It contains the full decision model, Brent-specific preferences and explicit statements, safety rules, Tier and coverage analysis, class/build-adjusted valuation, current project state, evidence standards, source protection, and DIM workflow.

### For a friend or other human who wants to understand the project

Open:

`Brents-Destiny-2-Human-Bootstrap.md`

This tells the story of the project in a readable form: why the vault is difficult to clean, what makes Destiny weapon comparisons complicated, what Brent has learned, how the safeguards work, and where the project currently stands.

The human file explains the system; it does not replace the AI file for deletion analysis.

## Stable-file policy

Future releases should overwrite both canonical root files:

- `Brents-Destiny-2-AI-Bootstrap.md`
- `Brents-Destiny-2-Human-Bootstrap.md`

Do not add version-numbered bootstrap files to the repository root. Preserve snapshots under `docs/history/`.

## v2.7 highlights

- Restored the richer v2.5.1 AI-bootstrap structure after rejecting the over-compressed v2.6 experiment.
- Added the separate human-facing bootstrap instead of forcing one document to serve both AI and human audiences.
- Made Brent's explicit statements, corrections, preferences, examples, and protected items first-class project data that must not be optimized away.
- Preserved separate retention hierarchy, deletion categories, coverage rules, Tier logic, workflow, verification checklist, onboarding questions, and personal examples.
- Added a two-bootstrap architecture reference and archived the exact v2.5.1 AI bootstrap.
- No vault exports, DIM imports, spreadsheets, candidate audits, or weapon-policy reference documents changed.

## Important safety rules

- Never dismantle directly from an AI ranking.
- Back up DIM metadata before imports.
- Preserve user-created tags, notes, locks, favorites, keeps, loadouts, and meaningful personal signals.
- Compare exact weapon versions, intrinsic frames, firing behavior, elements, origin traits, legal Tier configurations, and full configured stat packages.
- Treat class/build reload tools as contextual; do not erase portable value or passive rotation reload.
- Treat costly dungeon, raid, Trials, Adept, crafted, retired, and limited-source gear with a higher deletion threshold.
- Require an auditable retained replacement for every proposed deletion.

## Permanent baseline and current snapshot

- Baseline: `Vault-Exports/baseline/2026-07-18-DIM-Weapons-Permanent-Baseline.csv`
- Baseline SHA-256: `26a046a058528a7b9d824f53306fc5447ccb4cdd2b0f405297bd458351ffc9bd`
- Current snapshot: `Vault-Exports/latest/2026-07-19-DIM-Weapons-Current.csv`
- Current SHA-256: `6d5226e6e50801155f61a4b667debfba4a22ed67a3119d402a4fa09963c08f40`

## Current recommendation

The only active proposed DIM import is:

`DIM-Imports/proposed/DIM-Import-Junk-God-Roll-Validated-7-2026-07-19.csv`

Older eight-item and 38-item files are archived and are not current recommendations. The 16 cross-version candidates remain a manual-revalidation hold set.

## Key references

- `docs/Bootstrap-Architecture-v2.7.md`
- `docs/Class-Adjusted-Reload-and-Sustain.md`
- `docs/Super-Economy-and-Bad-Juju.md`
- `docs/Recoil-Direction-Mechanics.md`
- `docs/Frame-Intrinsic-and-Origin-Trait-Coverage.md`
- `docs/Dungeon-and-Source-Protection.md`
- `docs/God-Roll-Perk-Synergy-and-Metadata-Policy.md`
- `docs/research/Warlock-Creator-Build-Research-v2.4.md`
- `docs/history/Brents-Destiny-2-AI-Bootstrap-v2.5.1.md`
- `docs/history/Brents-Destiny-2-AI-Bootstrap-v2.4.1-Legacy.md`
