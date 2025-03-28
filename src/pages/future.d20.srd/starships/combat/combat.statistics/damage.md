---
title: Damage
layout: '~/layouts/MarkdownLayout.astro'
---

[ Index ](/) > [ Future D20 ](/future.d20.srd) > [Starships](/future.d20.srd/starships) > [Combat](/future.d20.srd/starships/combat) > [Combat Statistics](/future.d20.srd/starships/combat/combat) > Damage

## Damage

When a starship hits with a weapon, it deals damage according to the type of
weapon (see Table: Starship Weapons). Damage is deducted from the target’s
current hit points. If a starship’s hit points are reduced to 0 or fewer, the
ship is in bad shape (see Hit Points, below).

### Multiplying Damage

Sometimes a starship weapon multiplies damage by some factor, such as when it
scores a critical hit. Just as in character combat, you can either roll the
damage (with all modifiers) multiple times and total the results, or roll the
damage once and multiply the result by the given multiplier.

Bonus damage represented as extra dice, such as from the Engineer’s weapon
upgrade class ability, is an exception. Do not multiply bonus damage dice when
a starship scores a critical hit.

### Critical Hits

Critical hits by starships work just like critical hits by characters. When a
starship makes an attack roll and gets a natural 20, the starship hits
regardless of the target’s Defense, and it has scored a threat of a critical
hit. To find out whether it is actually a critical hit, the starship
immediately makes another attack roll with all the same modifiers as the
attack roll that scored the threat. If the second roll also results in a hit
against the target’s Defense, the starship’s attack is a critical hit.

For a more colorful application of the critical hit system, see Optional
Critical Hit Results, below.

### Optional Critical Hit Results

A critical hit with a starship weapon normally multiplies the weapon’s damage.
The GM may opt to use a randomized critical hit resolution system instead:
Whenever a critical hit is scored, the attacker rolls percentile dice and
consults Table: Optional Critical Hit Results to determine the effects of the
critical hit on the target.


<table> <tr><th colspan="2">Table: Optional Critical Hit Results</th></tr> <tr><th>d% Roll</th><th>Effect(s)</th></tr> <tr><td>01–35</td><td>Normal critical hit</td></tr> <tr class="shaded"><td>36–50</td><td>Normal critical hit, crew casualties</td></tr> <tr><td>51–55</td><td>Severe critical hit, artificial gravity disabled</td></tr> <tr class="shaded"><td>56–60</td><td>Severe critical hit, crew casualties</td></tr> <tr><td>61–65</td><td>Damaged system: comm system</td></tr> <tr class="shaded"><td>66–70</td><td>Damaged system: defense system</td></tr> <tr><td>71–75</td><td>Damaged system: engines</td></tr> <tr class="shaded"><td>76–80</td><td>Damaged system: sensors</td></tr> <tr><td>81–85</td><td>Damaged system: targeting system</td></tr> <tr class="shaded"><td>86–90</td><td>Damaged system: weapon</td></tr> <tr><td>91–95</td><td>Destroyed defensive system</td></tr> <tr class="shaded"><td>96–100</td><td>Destroyed weapon</td></tr> </table>


Normal Critical Hit: Roll critical hit damage normally.

Crew Casualties: A number of crewmembers and passengers are killed (this
effect applies only if the ship isn’t destroyed). Roll 1d10 to determine the
number of crew fatalities and, if the ship carries passengers, 1d10 to
determine the number of passenger casualties. Only supporting GM characters
are affected.

A starship with less than one-half of its normal crew complement takes a –2
penalty on all attack rolls and checks.

A starship with less than one-quarter of its normal crew complement takes a –4
penalty on all attack rolls and checks.

A starship with no crew flies on autopilot and cannot attack. If a crewless
ship doesn’t have a functional autopilot system, it is immobile. If this
result is rolled again and the ship has no living crew or passengers, ignore
this result and reroll.

Severe Critical Hit: Roll critical hit damage using a ×10 multiplier instead
of the weapon’s normal multiplier. In addition, the ship and its crew are
shaken for 1 round.

Artificial Gravity Disabled: The starship’s artificial gravity is disabled for
1d10 rounds. During this time, an untrained crew takes a –4 penalty on all
attack rolls and skill checks while coping with the zero-gravity conditions.
Trained, expert, or ace crews take no penalties, as they are assumed to have
the Zero-G Training feat. Ignore this result if it comes up again while the
artificial gravity system is disabled.

Damaged System: A damaged system remains inoperable until it is repaired,
which requires 10 hours of work and a successful Repair check (DC 30). A
starship’s engineer (or engineering team) can perform jury-rig repairs on the
system as a full-round action with a successful Repair check (DC 25), but the
repairs last only until the end of the battle (or until the system is disabled
again). During that round of jury-rigged repairs, the starship can continue to
take actions.

Comm System: One communications system of the attacker’s choice is disabled.
If this result is rolled again and the ship has no undamaged comm systems,
ignore this result and reroll.

Defense System: One defense system of the attacker’s choice is disabled. If
this result is rolled again and the ship has no undamaged defense systems,
ignore this result and reroll.

Engines: The starship’s tactical speed decreases by 1,000 feet until the
engines are repaired. If this result is rolled again, the effect is
cumulative. If the ship’s tactical speed has already been reduced to 0 feet
due to engine damage, ignore this result and reroll.

Sensors: The starship is blinded until repaired. All the ship’s targets gain
the equivalent of total concealment (50% miss chance). If this result is
rolled again, ignore the result and reroll.

Targeting System: The starship’s targeting system ceases to function. The
starship loses the targeting system’s equipment bonus on attack rolls until
the system is repaired. Reroll if this result comes up again.

Weapon: One of the starship’s beam weapons, projectile weapons, or missile
launchers (attacker’s choice) ceases to function. The weapon remains
inoperable until it is repaired. If this result is rolled again and the ship
has no functional weapons, ignore this result and reroll.

Destroyed Defensive System: One of the starship’s defensive systems
(determined by the attacker) is destroyed. It cannot be repaired and must be
replaced. If this result is rolled again and the ship has no defensive
systems, ignore this result and reroll.

Destroyed Weapon: One of the starship’s weapons (determined by the attacker)
is destroyed. It cannot be repaired and must be replaced. If this result is
rolled again and the ship has no weapons, ignore this result and reroll.

If the destroyed weapon was fire-linked, the other weapons to which it was
linked continue to function normally. If the destroyed weapon was part of a
weapon battery, the remaining weapons in the battery continue to function
normally.

### Starship Armor

Starship armor is designed to absorb damage rather than make a starship harder
to hit. Consequently, a starship’s armor plating provides hardness instead of
an equipment bonus to Defense.

Subtract a starship’s hardness from the damage each time it takes a hit. If a
ship’s hardness is greater than the amount of damage dealt by the attack, the
starship takes no damage.

See Starship Armor for the various types of armor available at different
Progress Levels, as well as the hardness of each type.

### Damage Control

A starship equipped with a damage control system can perform damage control as
a move action. With a successful Repair check (DC 15), the ship regains a
number of hit points depending on its type, as shown on Table: Damage Control
Systems. A ship with an improved or advanced damage control system regains
even more hit points (see Starship Defense Systems).

Damage control cannot be performed if the ship has been reduced to negative
hit points.

