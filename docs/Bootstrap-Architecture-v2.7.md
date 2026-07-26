# Two-Bootstrap Architecture — v2.7

## Decision

The repository now uses two stable root-level bootstrap files because one document should not be forced to satisfy two conflicting audiences.

- `Brents-Destiny-2-AI-Bootstrap.md` is the authoritative, detailed operating file for an AI performing or continuing vault analysis.
- `Brents-Destiny-2-Human-Bootstrap.md` is a readable narrative for friends, clanmates, or other people who want to understand the project and appreciate its technical depth without reading the full operating specification.

Both filenames are stable. Future releases overwrite them and preserve versioned snapshots under `docs/history/` when needed.

## AI bootstrap design

The AI file is based on the richer v2.5.1 structure. It retains separate sections for safety, BIS/dominance, deletion categories, coverage, Tier 5 configurations, Hunter reload valuation, configured stats, recoil, perk roles, Super economy, creator evidence, source cost, workflow, DIM imports, project state, personal examples, build-library guidance, onboarding, verification, and the resume prompt.

The file is allowed to repeat an important safeguard when that repetition prevents a different class of mistake. Its optimization target is not minimum word count; it is reliable continuity and safe, auditable decisions.

Brent-specific preferences, corrections, examples, protected items, and explicit statements are first-class project data. They must not be removed merely to shorten the file.

## Human bootstrap design

The human file tells the story in plain language:

- Why Brent needs the project
- Why Destiny vault cleanup is not a simple god-roll ranking
- How Tier 5 selectable perks, frames, elements, stats, classes, and builds complicate decisions
- What the Hunter reload discovery changed
- What was learned from specific weapons Brent discussed
- How creator evidence and safety rules are used
- What the repository currently contains and where the cleanup stands

It is not intended to authorize deletion or replace the technical rules. A friend can read it in one sitting and understand both the purpose and the sophistication of the project.

## Version history note

v2.6 was an over-compression experiment and was rejected as the active design. v2.7 restores the v2.5.1 level of detail, adds explicit personal-information preservation rules, and solves the audience problem through two files rather than further shortening the AI file.
