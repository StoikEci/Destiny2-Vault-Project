# Class-Adjusted Reload and Magazine-Sustain Valuation

**Added:** v2.5, July 25, 2026  
**Purpose:** Prevent class-specific reload tools from producing either false keep decisions or false deletion decisions.

## 1. Core distinction

Do not collapse every “reload-like” effect into one category.

| Function | What it solves | Typical value |
|---|---|---|
| Reload speed | Shortens a manual reload animation | Portable, but can be redundant with instant reloads |
| Instant/ability reload | Refills one or more weapons through an ability or trigger | Powerful but consumes a resource and may have timing limits |
| Passive holstered reload | Refills while another weapon/ability is used | Excellent for swaps and damage rotations |
| Magazine overflow/preload | Starts above normal capacity or rebuilds while stowed | Creates burst/rotation value beyond a normal reload |
| Sustained-fire refund | Returns rounds while firing or on kills/hits | Prevents repeated interruptions |
| Ammo economy | Increases reserves, pickup value, generation, or efficiency | Not equivalent to reload speed |
| Reload-triggered payoff | Activates a damage/verb/healing effect after a qualifying reload | The trigger itself must be verified |

## 2. Hunter Marksman's Dodge

Official Destiny 2 Update 9.1.5 changed Marksman's Dodge so it:

- Reloads all equipped weapons on activation.
- Picks up nearby ammo bricks on activation.

Official source: <https://www.bungie.net/7/en/News/Article/destiny_update_9_1_5>

This materially lowers the marginal value of some conventional reload-speed solutions when Brent is actively using Marksman's Dodge and can spend the class ability at the needed time.

## 3. Hunter-specific implications

### Often devalued

- Reload-speed-only third-column perks on primary weapons.
- Reload-speed Masterworks when another Masterwork creates a larger functional gain.
- Rolls whose only advantage is faster manual reload.

### Still independently valuable

- Auto-Loading Holster and other passive holstered reloads.
- Reconstruction, Overflow, Envious-style preload/overflow, and similar effects.
- Subsistence, Rewind-style refunds, or other repeated sustain.
- Field Prep reserves, Rapid Hit stability, Demolitionist grenade interaction, and other hybrid benefits.
- Any perk whose value occurs before dodge is ready or without spending the class ability.

### Verify reload-trigger rules

Do not assume that a dodge reload activates every perk worded “after reloading.” Test or verify the current behavior for the exact perk. A forced reload, magazine refill, ammo refund, and normal reload animation can be treated differently by the game.

## 4. Opportunity-cost test

For each build-specific reload assumption, record:

1. Which class ability or trigger supplies the reload?
2. What cooldown/resource does it consume?
3. What alternative class ability or build effect is sacrificed?
4. Is it available in the critical damage or survival window?
5. Does the animation or movement create risk?
6. Does the build need that ability for invisibility, melee regeneration, Radiant, decoys, survivability, positioning, or an Exotic loop?

A class ability that is theoretically available is not the same as a free passive reload.

## 5. Required comparison scores

### Portable value

How good is the roll on any class or build without relying on a class-specific reload?

### Active-build value

How good is it with the confirmed Hunter/Warlock/Titan build, class ability, Exotic armor, artifact, and rotation?

### Rotation value

How much does it contribute when weapons are swapped during boss or major damage? Passive reload, preloading, overflow, and sustained-fire behavior receive explicit credit.

### Opportunity cost

What is spent to obtain the reload, and what else could occupy that perk, class ability, or Exotic slot?

## 6. Deletion rule

Do not delete a strong portable reload roll merely because one Hunter build currently solves reload. A high-confidence deletion requires either:

- Another retained copy dominates it in both portable and active-build contexts, or
- Brent explicitly chooses to optimize only for the current build and accepts the portability loss.

Do not keep three class-specific variants just because they differ theoretically. Keep an alternate only when it creates a materially different role, rotation, difficulty profile, or reliability advantage.

## 7. Audit language example

> Candidate has Outlaw + damage perk and is strong as a portable all-class roll. Retained copy replaces Outlaw with a utility perk and is superior while Marksman's Dodge supplies instant all-weapon reload. Because the retained copy does not dominate outside that Hunter setup, classify the candidate as Manual Review rather than automatic Junk unless Brent accepts Hunter-only optimization.
