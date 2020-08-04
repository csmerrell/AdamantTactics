# Kohr Fighter
Momentum Brawler

## Lore
When the DehnKohr arent pounding dirt and mud, they dance. The Capistani and the Selis call them backwater farmers and brick-shapers, but don't be fooled.

Look closely at their motions, and you will see where our school of Dancing Blades finds its lethal roots. The movements of the "Kohr Step" exert a mastery over the body that few men or women will ever know. Where our Dancers step, the Kohr surge with a spirit that charges every movement.

Our Dancers channel kinetic energy into a blade. A proper Kohr fighter sharpens their soul and strikes with every limb.

## Base stats
* Base Damage Modifier: -25%
    * Low up front damage, but attacks more than once per turn.
* Base Attack Range: 2
* Base Defensive Modifier: -15% (Uniform for all close range fighters)
* Base Wait time Modifier: -10 to -20% (random each turn).
* Base MOV Modifier: +1, (0 in a non-neutral step)
* When attacking, choose a destination tile adjacent to enemy target and end turn there.

## Default Loadout
### Active skills
* Rhythmic Revisions
    * Adjust the meter of the Kohr's steps to suit the changing needs of battle.
    * Cost: Free
    * Does not consume turn
    * Only 1 use per turn
    * Drop Step
        * MOV -1
        * -25% All outgoing damage dealt
        * +30% Evasion
        * Counterattack enemies in range
    * Forward Progression
        * MOV -1
        * +25% All incoming damage received
        * +25% All outgoing damage dealt
        * Wait time between turns reduced an additional (random) amount each turn (15% - 30%)
    * Adaptive Free Form
        * MOV -1
        * -10% outgoing damage dealt
        * +20% Evasion
        * Wait time between turns reduced an additional (random) amount each turn (10% - 20%)
    * Steady Step (Neutral)
        * Revert stance changes
    * (Locked) Aggressive Sway (Neutral)
        * Unlocked by the _Gon-trained Ring Fighting_ passive trait. Replaces Steady Step
        * +25% Outgoing damage
        * +25% Evasion
* Dancer's Double
    * The intricate steps of the Kohr dance stretch the soul into a second visage whose movements carry an uncanny weight in the physical realm.
    * Range: Default (2+)
    * Cost: Free
    * Attack twice this turn. The second attack deals half damage.
    * Wait time +60% (After reduction modifiers)

### Default action
* Sharpen Soul
    * +5(n)% damage boost on all sources for the remainder of the battle
    * +1(n)% defense penetration for remainder of the battle
        * n for both of the above is the number of times this move is used.
    * Stacks infinitely

### Passive skills
* Lightfooted
    * Time between turns is reduced by a random amount between 10 and 20% each turn.

## Unlockables
### Active Skills
* Elbow Drive
    * Spring forward with a penetrating elbow thrust.
    * Cost: Default
    * Range: +1
    * -15% damage
    * +25% def penetration
* Reversal Kick
    * Pivot into a reverse horse-kick.
    * Range: -1
    * +50% damage
    * +25% def penetration
* Caesura
    * Take respite from the surging tides of battle. Reflect, and realign the body with the soul.
    * Cost: +25% wait time
    * Range: Self
    * Heal x HP (med)
    * _It is only in these brief moments of stillness that the mind grasps and tracks the soul's elusive steps._
* Soul Strike (Confine)
    * Deliver an open-palm strike that suppresses the opponent's soul.
    * Cost: Default
    * Range: +1
    * -50% damage
    * Target deals -33% damage
    * +25% wait time for target.
    * Debuff Duration: 2 Unit Turns
* Soul Strike (Expose)
    * Deliver an open-palm strike that latches onto and pulls the opponent's soul into the open.
    * Cost: Default
    * Range: +1
    * -25% damage
    * Target takes +33% damage from all sources
    * +25% wait time for target.
        * Duration: 2 Unit turns
* _The Diligent Will_
    * The soul exerts dominance over the body. Take an additional turn immediately.
    * Cost: Free
    * Take another turn after this one. (Movement, too)
    * +110% wait time (After reduction modifiers)

### Passive Skills
* Flame-forged Soul
    * +1 attack range for all single-hit melee attacks (Barefisted only)
    * Stackable (Max: 3)
* Forfeit Control
    * -5% All outgoing damage
    * +10% Evasion.
    * +20% Counterattack chance.
    * Stackable (Max: 2)
* Gon-trained Ring Fighting
    * Replaces "Steady Step (Neutral)" with "Aggressive Sway (Neutral)"
        * +25% Outgoing damage
        * +25% Evasion
* Momentum's Master
    * Attack range can be split, allowing single target melee attacks to hit multiple targets
    * E.g. - For an ability with max range (3), the player can:
        * Select 1 target at 3 tiles
        * Select 2 targets. 1st at 1 tile, 2nd at 2 tiles
        * Select 3 targets, all at 1 tile
    * -20% potency per additional target beyond one.
* Soul Weaving
    * Caesura and Sharpen Soul also affect nearby allies
    * Range: 2 tile radius
* Building Steps
    * Each successful attack stores additional potency stacks for Sharpen Soul and Caesura.
    * Sharpen Soul:
        * +1x multiplier per stack
    * Caesura:
        * +10% heal potency per stack
    * All stacks expended each time either move is used.
* Soulful Steps
    * Sharpen Soul Generates +2n% damage per use
    * Caesura potency +10%
    * Stackable (Max: 3)
* Clear Mind
    * -10% wait time when using Sharpen Soul and Caesura
    * Stackable (Max: 3)
* Battleborn Stamina
    * MOV + 1
    * Stackable
    * WPN, BLD, CHI, INTR
* Battle Sense
    * +2% evasion
    * +10% chance to counter
    * Stackable
    * WPN, BLD, RUN, CHI, INTR

## Notes
* Wait time reduction modifiers are always applied before delay modifiers.
* Reduction modifiers add together before calculation (non-diminishing returns).
