# Overview
GURPS only uses six-sided dice, and uses abbreviations for die rolls – for instance, a roll on three dice would be shown as “3d”.
## Task Resolution
The basic mechanic of GURPS is the success roll against a Skill or Attribute. To succeed, you must roll less than or equal to the number with 3d. The GM may assign modifiers to your skill from -10 (extremely hard) to +10 (extremely easy). A 3 on the dice always succeeds and an 18 always fails!
### Quick Contest
When two characters are competing to do something very quickly – for instance, two enemies lunging for an item. This is called a quick contest. Each competitor attempts a success roll. If one succeeds and the other fails, the winner is obvious. If both succeed, the winner is the one with the largest margin of success. If both fail the winner is the one with the smallest margin of failure. A tie means no one won.
# Character
## Attributes
Most adventurer's have stats between 8-20, with 10 being the Foulkn Average. The four attributes are as follows.

**Strength (ST)**: Sets **Hit Points (HP)**, and **Damage (Dmg)**.

**Dexterity (DX)**: Helps determine **Speed** and is used for many skills.

**Intelligence (IQ)**: Determines **Perception**, **Will**, and is used for many skills.

**Health (HT)**: Governs how well you resist bad effects, your **Fatigue Points (FP)** and helps determine **Speed**.
## Secondary Attributes
These are derived from your Attributes.

**Hit Points (HP)**: Your body's ability to sustain injury.

**Fatigue Points (FP)**: Your body's “energy supply”. 

**Basic Lift**: is the maximum weight you can lift over your head with one hand in one second.

**Encumbrance (Encmbr)**: is a measure of the total weight you are carrying, relative to your **ST**. Numbered from 0 to 4. When a rule tells you to add or subtract your encumbrance level, this is the number to use. For instance, encumbrance gives a penalty to Climbing, Stealth, and Swimming.

**Will**: your ability to withstand psychological stress and resist supernatural attacks.

**Perception (Per)**: Your general awareness and accuracy with your senses.

**Speed**: A measure of your reflexes. Used to determine initiative.

**Move**: A measure of how far you can move in one turn, in hexes (yards).

**Damage**: Damage is broken up into Swing damage (Sw) and Thrust damage (Thr). Weapons will use these as the base of their damage dealt.
## [Skills](Skills.md)
Skills govern what your character is good at. If you don't have a skill you may still be able to "use" it by rolling against it's **default**. This will be an **attribute** minus a number.

While every character should have at least one weapon/combat skill, you need more than just weapons to survive. For a full list of Skills check [here](Skills.md).
## Traits
Traits are details about your character and how they interact with the game; world and system. These cover everything from your kin, magical powers, place in society, languages known, to even attractiveness.
# Combat
Combat proceeds in rounds with a round lasting one second. Each round, characters act in the order of their Speed, with the highest number going first. Each player chooses a Maneuver for their character from the following list.
## Maneuvers
### Basic Maneuvers
**Move**: Use this maneuver to take Full Movement.

**Attack**: Attack an enemy with a ready weapon. Make a success roll against your skill with the weapon. If you succeed the target must then fail to Defend (see active Defense below). As part of your Attack you may Step.

**Aim**: Aim at a specific, visible target. If you attack your target on your next turn, you may add your attack's Acc bonus to your effective skill – but if you lose sight of your enemy or make an Active Defense the bonus is lost. As part of your Aim you may Step.

**Ready/Concentrate**: Used as catchalls for actions not covered by other maneuvers. Such as drawing a weapon or casting a spell. Some action require multiple or concurrent uses of these maneuvers. As part of Either Ready or Concentrate you may Step.

**Free Actions**: Free actions can be performed at any time and do not take up the character’s turn. The most common free actions are to drop something and to talk.
## Active Defense
These are defensive maneuvers used on the enemy's turn to prevent them from hitting. After a successful attack the target may attempt one Active Defense, as long as they are aware of the attack.

**Dodge**: If you make a success roll against this number, you dodge the attack. You may dodge any type of attack and there is no limit to the number of different attacks you can dodge in a turn.

**Parry**: Make a success roll against this number and you have parried the attack. You may only parry melee attacks, thrown weapons, or attacks and spells that specify they can be parried. Once you’ve attempted a parry with a given weapon or hand, further parries with that weapon or hand have a cumulative -4 per parry after the first.

**Block**: To block, you must have a readied shield or cloak. Make a success roll against this number and you have blocked the attack. You can block any melee or ranged attack, but further blocks suffer a cumulative -5 penalty.

## Movement
Each maneuver allows for a different amount of movement based on your Move. The three types of Movement are as follows.

**Full Movement**: Move a number of hexes equal to your Basic Move. Alternatively spend half your movement to shift from Prone to Kneeling or from Kneeling to Standing (for more details see Posture).

**Half Movement**: Move a number of hexes equal to half of you Basic Move rounded up. Alternatively shift from Prone to Kneeling or from Kneeling to Standing.

**Step**: Move 1 hex. Alternatively you may Stand up from Kneeling.
### Facing
Whenever you have at least a step of movement you may shift your facing freely. You must always face toward one of the six hexes adjacent to your hex. Your facing defines your front, right, left, and back hexes (see illustration). Active defenses suffer a -2 when defending from the side and it is impossible to defend from the back. You may only attack into your front hexes.
![Facing](https://raw.githubusercontent.com/HeringtonPress/HeringtonPress.github.io/main/Images/Facing.png)
### Posture
It is always a free action to move down in posture. i.e. falling prone.

**Prone**
While prone you have a movement of 1. You have a -4 to hit with melee attacks. You have a -3 to Active Defense. ranged attacks have a -2 to hit you.

**Kneeling**
While kneeling you have 1/2 movement (Drop Fractions) to a minimum of 1. You have a -2 to hit with melee attacks. You have a -2 to active defense. ranged attacks have a -2 to hit you.

**Standing**
While standing you are unpenalized.
## [Advance Combat Options](Monday-GURPS-Combat.md)

# Damage, Health, and Recovery
**Damage**: Damage is almost always **ST**-based and expressed as a modifier to the wielder’s basic **thrusting (thr)** or **swinging (sw)** damage. For example, a spear does “thr+2,” so with thrusting damage of 1d-1, you’ll inflict 1d+1 damage with a spear.

Each damage rating is followed by an abbreviation indicating damage type:

| Abbreviation |      Type      | Wounding Multiplier |
|:------------:|:--------------:|:-------------------:|
|      cr      |    crushing    |         x1          |
|     cut      |    cutting     |        x1.5         |
|     imp      |    impaling    |         x2          |
|     pi-      | small piercing |        x0.5         |
|      pi      |    piercing    |         x1          |
|     ect     |   see notes    |                     |

A successful attack always does at least 1 point of damage (before DR).

**Damage Resistance (DR)**: Is the measure of how well you are physically protected. Typically this is from the armour you are wearing. Reduce all incoming damage by this amount.

Any damage that penetrates DR is multiplied by the damage type's Wounding Multiplier. A victim loses HP equal to this new sum.

**Hit Points**: You do not automatically die at 0 HP, but every turn thereafter you must make a success roll against HT, with a -1 for each multiple of negative HP. Failure means you instantly fall unconscious.
> If you reach the end of an encounter and are still below 0 HP make an HT roll -5 (Include negative HP penalty). On a success no further rolls are needed till you receive damage again, on a failure you fall unconscious.

**Dying**: If you reach a negative multiple of your HP, you must immediately make an HT roll. On a failure of 3 or more you die. If you fail by 2 or less you pass out.

If you reach -5xHP you die instantly, -6xHP your body is destroyed.

**Recovery**: A character with the First Aid skill can make a success roll to attempt to heal an injured character (don't forget modifiers). This requires one minute and restores 1 HP if successful. If the caregiver continues to care for the wounded character for another 29 minutes, the wounded character recovers 1d-2 HP (minimum 1) more hp.

Further healing requires rest. At the end of each day of rest, make a success roll against HT. On success, the character regains 1 HP for every 10 points of max HP (minimum 1).

Characters that fell unconscious automatically wake up 15 minutes after their HP becomes positive. Or an hour after receiving First Aid.

**Fatigue points** can be recovered at a rate of 1 per ten minutes of rest.
# [Equipment](Monday-GURPS-Equipment.md)