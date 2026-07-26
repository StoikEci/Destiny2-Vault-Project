# Brent's Destiny 2 AI Repository v2.4

This repository packages the current Destiny 2 AI bootstrap and reusable workflow files.

## Start here

Open:

`Brents-Destiny-2-AI-Bootstrap-v2.4.md`

That file contains the full continuity context, vault-cleanup framework, Tier 5 rules, buildcrafting analysis, creator-evidence model, Champion, elemental, exact-frame, firing-behavior, and origin-trait coverage rules, and Brent-specific preferences.

## Important safety rules

- Never dismantle directly from an AI ranking.
- Back up DIM tags and notes before importing changes.
- Treat dungeon, raid, Trials, Adept, crafted, Tier 5, retired, and limited-source gear as higher-reacquisition-cost items.
- A dungeon-exclusive item is not an automatic keeper, but it requires a stronger deletion case.
- Preserve meaningful coverage by weapon type × exact intrinsic frame × element.
- Do not use one shotgun frame, fusion frame, grenade-launcher frame, or other distinct archetype to erase another without an explicit player decision.
- Cross-version weapon hashes require origin-trait and perk-pool review.
- Old deletion CSVs are intentionally not included because earlier AI-generated junk tags contained mistakes.
- Add the newest DIM export to `Vault-Exports/latest/` before a new analysis.
- Save proposed DIM imports under `DIM-Imports/proposed/`.
- Store metadata backups under `DIM-Imports/metadata-backups/`.

## Filename policy

Downloadable files use safe names with no spaces, apostrophes, or percent signs. The human-readable document title still uses “Brent's.”

## Repository contents

- Full bootstrap
- Change log
- Friend/player interview template
- Reusable vault-analysis prompt
- Dungeon and endgame source-protection guide
- Empty folders for current exports, proposed imports, backups, and evidence


## Permanent baseline and current analysis

- Permanent baseline: `Vault-Exports/baseline/2026-07-18-DIM-Weapons-Permanent-Baseline.csv`
- SHA-256: `26a046a058528a7b9d824f53306fc5447ccb4cdd2b0f405297bd458351ffc9bd`
- Analysis workbook: `Analysis/Brents-Destiny-2-Vault-Analysis-2026-07-18.xlsx`
- Candidate audit CSV: `Analysis/Brents-Destiny-2-Vault-Deletion-Audit-2026-07-18.csv`
- High-confidence DIM import: `DIM-Imports/proposed/DIM-Import-High-Confidence-Delete-2026-07-18.csv`

Only one permanent baseline export is bundled to avoid unnecessary repository growth. Future exports should be stored as dated snapshots and pruned deliberately, but this baseline should not be removed.


## v2.3 duplicate-analysis refinement

The original 54 `Could Delete` candidates are now split into:

- 38 same-version candidates in `DIM-Imports/proposed/DIM-Import-Could-Delete-38-Same-Version-Review-2026-07-19.csv`
- 16 cross-version holds in `Analysis/Could-Delete-Cross-Version-Hold-16-2026-07-19.csv`

The 38-item file is still a review aid, not an automatic dismantle instruction.


## v2.4 current working analysis

- Current snapshot: `Vault-Exports/latest/2026-07-19-DIM-Weapons-Current.csv`
- Current snapshot SHA-256: `6d5226e6e50801155f61a4b667debfba4a22ed67a3119d402a4fa09963c08f40`
- Proposed import: `DIM-Imports/proposed/DIM-Import-Junk-God-Roll-Validated-7-2026-07-19.csv`
- Detailed audit: `Analysis/Brents-Destiny-2-God-Roll-Junk-Audit-2026-07-19.csv`
- Summary: `Analysis/Brents-Destiny-2-God-Roll-Junk-Analysis-2026-07-19.md`

The active import contains seven conservative candidates. Older automated review imports were moved to `DIM-Imports/archive/` and are not current recommendations.
