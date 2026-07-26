# Frame, Intrinsic, and Origin-Trait Coverage

## Why this matters

Element plus broad weapon type does not fully describe how a weapon behaves.

A Void Pinpoint Slug Frame shotgun, Void Rapid-Fire Frame pellet shotgun, and Void Precision Frame pellet shotgun occupy different practical roles even though all are Void shotguns.

## Definitions

- **Intrinsic frame/archetype:** the built-in frame that controls fundamental behavior.
- **Firing behavior:** slug/pellet, burst, charge, wave, projectile, draw profile, rate of fire, and related practical characteristics.
- **Origin trait:** the separate source/foundry/activity trait.
- **Weapon hash/version:** identifies a specific release/version and may imply a different perk pool, origin trait, source, Tier behavior, or enhancement path.

## Coverage rule

Preserve meaningful coverage by:

`weapon type × exact intrinsic frame × element`

Then account for:

- Ammo and slot
- Champion role
- Engagement range
- Build role
- Origin-trait function
- Source and reacquisition cost

## Nessa's Oblation example

Nessa's Oblation can replace weaker Void Pinpoint Slug Frame shotguns when its roll is superior.

It does not automatically replace:

- Void Rapid-Fire Frame pellet shotguns
- Void Precision Frame pellet shotguns

Cross-frame consolidation must be an intentional player choice.

## Deletion rule

Use Manual Review when:

- Candidate and replacement have different frames.
- Candidate and replacement have different hashes/versions.
- Origin traits are absent or unclear.
- A deletion may remove the last useful element/frame combination.
- The player has not stated whether they value the displaced frame.

## Audit fields

Record:

- Candidate and replacement IDs
- Candidate and replacement hashes
- Exact frames
- Firing behavior
- Origin traits
- Element
- Role
- Source
- Coverage remaining after deletion
