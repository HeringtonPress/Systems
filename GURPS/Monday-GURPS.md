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

**Ready**: Used for any predominantly physical activity not covered by another maneuver. Use this Maneuver to draw a weapon, pick something up, or load a ranged weapon. Some actions require multiple or even concurrent readies, such as retrieving a potion from you backpack. As part of your Ready you may Step.

**Concentrate**: Focus on a primarily mental task - Spellcasting, non combat skills, or activating an ability that requires this maneuver. As part of Concentrate you may Step.

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

![Facing](https://github.com/HeringtonPress/HeringtonPress.github.io/assets/93562930/446fa56c-2cea-482e-b27c-1c9589aa7dd0)

### Posture
It is always a free action to move down in posture. i.e. falling prone.

**Prone**
While prone you have a movement of 1. You have a -4 to hit with melee attacks. You have a -3 to Active Defense. ranged attacks have a -2 to hit you.

**Kneeling**
While kneeling you have 1/2 movement (Drop Fractions) to a minimum of 1. You have a -2 to hit with melee attacks. You have a -2 to active defense. ranged attacks have a -2 to hit you.

**Standing**
While standing you are unpenalized.
## [Advance Combat](Monday-Gurps-Combat.md)

# Damage, Health, and Recovery
**Damage**: Damage is almost always ST-based and expressed as a modifier to the wielder’s basic thrusting (thr) or swinging (sw) damage, from the Damage Table (see Character Creation above). For example, a spear does “thr+2,” so with ST 11 and therefore a basic thrusting damage of 1d-1, you’ll inflict 1d+1 damage with a spear.

Each damage rating is followed by an abbreviation indicating damage type:

| Abbreviation |      Type      | Wounding Multiplier |
|:------------:|:--------------:|:-------------------:|
|      cr      |    crushing    |         x1          |
|     cut      |    cutting     |        x1.5         |
|     imp      |    impaling    |         x2          |
|     pi-      | small piercing |        x0.5         |
|      pi      |    piercing    |         x1          |
|     spec     |   see notes    |                     |

Any damage that penetrates DR is multiplied by the damage type's Wounding Multiplier. A victim loses HP equal to this new sum.

A successful attack always does at least 1 point of damage (before DR).

**Damage Resistance (DR)**: Is the measure of how well you are physically protected. Typically this is from the armour you are wearing. Reduce all incoming damage by this amount.

**Hit Points**: You do not automatically die at 0 HP, but every turn thereafter you must make a success roll against HT, with a -1 for each multiple of negative HP. Failure means you instantly pass out.

If you reach the end of an encounter and are still below 0 HP make an HT roll -5. On a success no further rolls are needed till you receive damage again, on a failure you pass out.

If you reach a negative multiple of your HP, you must immediately make an HT roll. On a failure of 3 or more you die. If you fail by 2 or less you are "Mortally wounded".

While Mortally Wounded you must make an HT roll every half hour or die. If you critically succeed on this roll you recover miraculously. If someone is tending to you, you can make a roll against their First Aid or Medicine skill instead but this requires that they be with you the full half hour. It takes an hour and a roll against Medicine -3 to stabilize someone who is Mortally Wounded.

If you reach -5xHP you die instantly, -6xHP your body is destroyed.

**Recovery**: A character with the First Aid skill can make a success roll to attempt to heal an injured character (don't forget equipment modifiers). This requires one minute and restores 1 HP if successful. If the caregiver continues to care for the wounded character for another 29 minutes, the wounded character recovers 1d-2 HP (minimum 1) more hp.

Further healing requires rest. At the end of each day of rest, make a success roll against HT. On success, the character regains 1 HP for every 10 points of max HP (minimum 1).

Characters that fell unconscious automatically wake up 15 minutes after their HP becomes positive. Or an hour after receiving First Aid.

**Fatigue points** can be recovered at a rate of 1 per ten minutes of rest.
# Equipment
All characters can use their starting money to outfit themselves. Any magical gear must be run by the GM before being bought as starting gear.
## Weapon Stats
### Acc (Accuracy)
Add Accuracy to your weapon skill if you took an Aim maneuver on the turn prior to your attack. If you have Heroic Archer (p. 35) and are wielding a bow, you don’t need to Aim – add Acc to skill whenever you Attack or All-Out Attack outside of close combat!
### Bulk
A measure of the weapon’s size and handiness. Bulk penalizes weapon skill during a Move and Attack maneuver or in close combat.
### Parry
A number, such as “+2” or “-1,” indicates the bonus or penalty to your Parry defense when using that weapon.
- “F” means the weapon is a fencing weapon, which suffers only half the penalty for multiple parries.
- “U” means the weapon is unbalanced: you cannot use it to parry after using it to attack on your turn (or vice versa).
- “X” means the weapon cannot parry.
### Range
If a weapon has only one range number, this is the Maximum Range (Max) in hexes (yards) at which it can attack a target. If two numbers appear, separated by a slash, the first is Half-Damage Range (1/2D) while the second is Max. Nearly all ranged weapons list range as multiples of the wielder’s ST. For bows and crossbows, use the weapon’s ST in these formulas (see below in Strength).
### Reach
The distance in hexes at which a melee weapon can strike; e.g., reach “2” means the weapon can only strike foes two hexes away, not closer or more distant ones. “C” indicates you can use the weapon for Close Combat, meaning in the same hex you are in.

Some weapons have more than one reach; e.g. A spear with reach “1, 2” can strike targets either one or two hexes away. An asterisk (\*) next to reach means the weapon requires a Ready maneuver to change reach (e.g., between 1 and 2).

### ST (Strength)
The minimum Strength needed to use the weapon properly. If you use a weapon that requires more ST than you have, you suffer -1 to weapon skill per point of ST deficit and lose one extra FP at the end of the fight.

For a melee or thrown weapon, your effective ST for damage purposes cannot exceed triple the weapon’s ST statistic. For instance, a large knife has minimum ST 6, so its “maximum ST” is 18.

“†” means the weapon requires two hands. If you have at least 1.5 times the listed ST (round up), you can use a weapon like this one-handed, but it becomes unready after you attack with it. If you have at least twice the listed ST, you can wield it one-handed with no readiness penalty.

“‡” means the weapon requires two hands and becomes unready after you attack with it, unless you have at least 1.5 times the listed ST (round up). To use it one-handed without it becoming unready, you need at least 3 times the listed ST.

**Bows, Crossbows, and ST**: Bows and crossbows have their own ST, which you must specify when you buy such a weapon. The ST in the table is the lowest possible value. Use the weapon’s rated ST instead of your ST to determine range and damage. You can always use a weapon that’s weaker than you. You can use a stronger crossbow with no penalty, but it will take longer to cock (see Reloading).
## Melee Weapon Table
Melee weapons are grouped under the skills required to use them. Skill names appear in capital letters, with defaults in parentheses.
### AXE/MACE (DX-5)

| Weapon         | Damage   | Reach | Parry | Cost | Weight | ST  | Notes |
| -------------- | -------- | ----- | ----- | ---- | ------ | --- | ----- |
| Axe            | sw+2 cut | 1     | 0U    | $50  | 4      | 11  |       |
| Club           | sw+1 cr  | 1     | 0U    | $10  | 3      | 10  |       |
| Great Axe      | sw+4 cut | 1, 2* | 0U    | $100 | 8      | 12‡ |       |
| Humongous Club | sw+6 cr  | 1, 2* | 0U    | $100 | 15     | 16‡ |       |
| Mace           | sw+2 cut | 1     | 0U    | $50  | 5      | 12  | [1]   |
| Maul           | sw+5 cr  | 1, 2* | 0U    | $80  | 12     | 13‡ |       |
| Pick           | sw+1 imp | 1     | 0U    | $70  | 3      | 10  | [2]   |
| Scythe         | sw+3 cut | 1     | 0U    | $15  | 5      | 11‡ |       |
| or             | sw+1 imp | 1     | 0U    |      |        | 11‡ |       |
| Throwing Axe   | sw cut   | 1     | 0U    | $40  | 2      | 8   | [1]   |
| Warhammer      | sw+4 imp | 1, 2* | 0U    | $100 | 7      | 12‡ |       |

### BRAWLING (DX)
The skill is bought as if it where DX-5

| Weapon         | Damage   | Reach | Parry | Cost | Weight | ST  | Notes   |
| -------------- | -------- | ----- | ----- | ---- | ------ | --- | ------- |
| Bite           | thr-1 cr | C     | X     |      |        |     | [3]     |
| Brass Knuckles | thr cr   | C     | 0     | $10  | 0.25   |     | [3]     |
| Kick           | thr cr   | C, 1  | X     |      |        |     | [3][6] |
| Punch          | thr-1 cr | C     | 0     |      |        |     | [3]     |

### FLAIL (DX-6)

| Weapon      | Damage       | Reach | Parry | Cost   | Weight | ST   | Notes   |
| ----------- | ------------ | ----- | ----- | ------ | ------ | ---- | ------- |
| Flail       | sw+4 cr      | 1, 2* | 0U    | $100   | 8      | 13†  | [4]     |
| Kusari      | sw+2 cr      | 1-4*  | -2U   | $70    | 5      | 11   | [4][5]  |
| or          | thr+2 cr     | 1-4*  | -2U   |        |        |      | [4][5]  |
| Morningstar | sw+3 cr      | 1     | 0U    | $80    | 6      | 12   | [4]     |
| Whip        | sw-3(0.5) cr | 1-7*  | -2U   | $20/yd | 1/yd   | var. | [5][7] |

### KNIFE (DX-4, Sword-3, Fencing-3)

| Weapon      | Damage   | Reach | Parry | Cost | Weight | ST  | Notes |
| ----------- | -------- | ----- | ----- | ---- | ------ | --- | ----- |
| Dagger      | sw-2 cut | C, 1  | -1    | $40  | 1      | 6   |       |
| or          | thr imp  | C     | -1    |      |        | 6   | [1]   |
| Long Knife  | sw-1 cut | 1     | 0     | $120 | 1.5    | 7   |       |
| or          | thr imp  | C, 1  | 0     |      |        | 7   |       |
| Main-Gauche | sw-3 imp | C, 1  | 0     | $50  | 1.25   | 6   |       |
| or          | thr imp  | C     | 0     |      |        | 6   |       |
| Short Baton | sw-1 cr  | C, 1  | -1    | $10  | 0.5    | 5   |       |
| or          | thr cr   | C     | -1    |      |        | 5   |       |

### POLEARM (DX-5, Spear/Staff-3, Axe/Mace-4)

| Weapon  | Damage    | Reach | Parry | Cost | Weight | ST  | Notes |
| ------- | --------- | ----- | ----- | ---- | ------ | --- | ----- |
| Glaive  | sw+3 cut  | 2, 3* | 0U    | $100 | 8      | 11‡ |       |
| or      | thr+3 imp | 1-3*  | 0U    |      |        | 11‡ |       |
| Halberd | sw+5 cut  | 2, 3* | 0U    | $150 | 12     | 13‡ |       |
| or      | sw+4 imp  | 2, 3* | 0U    |      |        | 13‡ | [2]   |
| or      | thr+3 imp | 1-3*  | 0U    |      |        | 12‡ |       |

### Fencing (DX-5, Sword-4)
Successive parries suffer a -2 instead of -4

| Weapon       | Damage    | Reach | Parry | Cost   | Weight | ST  | Notes |
| ------------ | --------- | ----- | ----- | ------ | ------ | --- | ----- |
| Edged Rapier | sw cut    | 1, 2  | 0F    | $1,000 | 3      | 10  |       |
| or           | thr+1 imp | 1, 2  | 0F    |        |        | 10  |       |
| Main-Gauche  | sw-3 imp  | C, 1  | 0F    | $50    | 1.25   | 6   |       |
| or           | thr imp   | C     | 0F    |        |        | 6   |       |
| Rapier       | thr+1 imp | 1, 2  | 0F    | $500   | 2.75   | 9   |       |


### SHIELD (DX-4)

| Weapon       | Damage   | Reach | Parry | Cost | Weight | ST  | Notes |
| ------------ | -------- | ----- | ----- | ---- | ------ | --- | ----- |
| Shield Bash  | thr cr   | 1     | X     | var  | var    | -   |       |
| Shield Spike | thr+1 cr | 1     | X     | +$20 | var    | _   |       |

### SWORD (DX-5, Fencing-4)

| Weapon        | Damage    | Reach | Parry | Cost   | Weight | ST  | Notes |
| ------------- | --------- | ----- | ----- | ------ | ------ | --- | ----- |
| Bastard Sword | sw+1 cut  | 1, 2  | 0U    | $750   | 5      | 11  |       |
| *or*          | thr+2 imp | 2     | 0U    | -      | -      | 11  |       |
| *Two Handed*  | sw+2 cut  | 1, 2  | 0     | -      | -      | 10† |       |
| *or*          | thr+3 imp | 2     | 0     | -      | -      | 10† |       |
| Broadsword    | sw+1 cut  | 1     | 0     | $600   | 3      | 10  |       |
| *or*          | thr+2 imp | 1     | 0     | -      | -      | 10  |       |
| Edged Rapier  | sw cut    | 1, 2  | 0     | $1,000 | 3      | 10  |       |
| *or*          | thr+1 imp | 1, 2  | 0     | -      | -      | 10  |       |
| Falchion      | sw+1 cut  | 1     | 0     | $400   | 3      | 10  |       |
| *or*          | thr-2 imp | 1     | 0     | -      | -      | 10  |       |
| Greatsword    | sw+3 cut  | 1, 2  | 0     | $900   | 7      | 12† |       |
| *or*          | thr+3 imp | 2     | 0     | -      | -      | 12† |       |
| Quarterstaff  | sw+2 cr   | 1, 2  | 0     | $10    | 4      | 9†  |       |
| *or*          | thr+1 cr  | 2     | 0     | -      | -      | 9†  |       |
| Shortsword    | sw cut    | 1     | 0     | $400   | 2      | 8   |       |
| *or*          | thr+1 imp | 1     | 0     | -      | -      | 8   |       |

### SPEAR/STAFF (DX-5, Polearm-3)

| Weapon       | Damage    | Reach | Parry | Cost | Weight | ST  | Notes |
| ------------ | --------- | ----- | ----- | ---- | ------ | --- | ----- |
| Long Spear   | thr+2 imp | 2, 3* | 0U    | $60  | 5      | 11  |       |
| *two hands*  | thr+3 imp | 2, 3* | 0     |      |        | 10† |       |
| Long Staff   | sw+2 cr   | 2, 3  | +2    | $15  | 5      | 10† |       |
| *or*         | thr+2 cr  | 2, 3  | +2    |      |        | 10† |       |
| Pike         | thr+3 imp | 4,5*  | 0U    | $80  | 13     | 12† |       |
| Quarterstaff | sw+2 cr   | 1, 2  | +2    | $10  | 4      | 7†  |       |
| *or*         | thr+2 cr  | 1, 2  | +2    |      |        | 7†  |       |
| Spear        | thr+2 imp | 1, 2* | 0U    | $40  | 4      | 10  | [1]   |
| *two hands*  | thr+3 imp | 1, 2* | 0     |      |        | 9†  |       |

[1] Can be thrown with a range of ST x1/x1.5 and a bulk of -4. 

[2] Any attack that injures an enemy embeds your weapon.
- If your victim tries to move away, roll a Quick Contest of ST: If you lose, your weapon is pulled from your grasp! If you win, your enemy can’t move. A tie means the weapon comes free.
- At the start of your next turn, you may try a ST roll as Ready maneuver. A successful ST roll pulls your weapon free. Failure leaves it embedded.
- If the weapon comes free for any reason, it inflicts half the injury it did going in.
- Critical failure on any of your ST rolls means the weapon is till after the battle.

[3] This attack receives damage bonuses per die based on your skill.  +1 if you know it at DX, +2 if you know it at DX+2. Claws don’t affect damage with blows assisted by weapons.

[4] Attempts to parry this weapon are at -4; knives and fencing weapons can’t parry at all! Attempts to block such weapons are at -2.

[5] Gets +2 to disarm. To grapple, attack at -4; a successful hit inflicts no damage and you must use a ready maneuver to make a quick ST contest each round to maintain the grapple.

[6] Kicks have a -2 to hit.

[7] Specify maximum reach (1-7 yards) when bought. Cost and weight are per yard. The whip requires ST 3, +1 per yard.
- Anyone injured on the arm by a whip must roll Against Will modified by the shock penalty for the injury or drop anything in that hand.
- You can “crack” a whip at -4 to hit, for +2 damage.
## Ranged Weapon Tables
### Reloading
The parenthetical number represents the number of ready actions needed to reload. 

**Thrown Weapons**: pick it up or ready a new weapon!

**Bows and Slings**: (2) means one Ready to draw and position a stone or arrow, and another to prepare the loaded weapon for shooting. A successful Fast-Draw roll turns the first into a free action, making effective reload time (1).

**Crossbows**: “(4)” means two consecutive Ready maneuvers to cock the weapon, one to draw and load a bolt, and one to bring the weapon back into shooting position. This assumes the weapon’s ST is no greater than yours. If its ST is one or two greater, reload time is (8); if its ST is three or four greater, you need a “goat’s foot” device and must be standing, reload time is (20); and if its ST is five greater or more, you cannot cock it! A successful Fast-Draw roll shaves off one Ready maneuver.

### BOW (DX-5)

| Weapon        | Damage    | Acc | Range   | Weight  | Cost | ST  | Bulk |
| ------------- | --------- | --- | ------- | ------- | ---- | --- | ---- |
| Bow           | thr+1 imp | 2   | x15/x20 | 2/0.1   | $100 | 10† | -7   |
| Composite Bow | thr+3 imp | 3   | x20/x25 | 4/0.1   | $900 | 10† | -7   |
| Longbow       | thr+2 imp | 3   | x15/x20 | 3/0.1   | $200 | 11† | -8   |
| Shortbow      | thr imp   | 1   | x10/x15 | 1.5/0.1 | $50  | 7†  | -6   |

### CROSSBOW (DX-4)

| Weapon   | Damage    | Acc | Range   | Weight | Cost | ST  | Bulk | 
| -------- | --------- | --- | ------- | ------ | ---- | --- | ---- | 
| Crossbow | thr+4 imp | 4   | x20/x25 | 6/0.06 | $150 | 7†  | -6   | 

### NET (DX-6)
May entangle or ensnare target.

Range is (ST + Skill/5); round down. Can also be held and used as a melee weapon with reach 1, 2.

| Weapon | Damage | Acc | Range | Weight | Cost | ST  | Bulk |
| ------ | ------ | --- | ----- | ------ | ---- | --- | ---- |
| Net    | -      | 1   | Spec. | 5      | $20  | 8   | -4   |

### SLING (DX-6)
Requires two hands to ready, but only one hand to attack.

| Weapon | Damage | Acc | Range  | Weight   | Cost | ST  | Bulk |
| ------ | ------ | --- | ------ | -------- | ---- | --- | ---- |
| Sling  | sw pi  | 0   | x6/x10 | 0.5/0.05 | $20  | 6   | -4   |

## Armor

| Armour      | DR  | Cost  | Weight | Notes   |
| ----------- | --- | ----- | ------ | ------- |
| Cloth       | 1   | $150  | 18     | [3]     |
| Leather     | 2   | $450  | 36     |         |
| Light Scale | 3/2 | $960  | 48     | [1,2]   |
| Light Mail  | 3/1 | $1500 | 36     | [1,2,3] |
| Scale       | 4/3 | $1650 | 84     | [1,2]   |
| Mail        | 4/2 | $2700 | 45     | [1,2,3] |
| Plate       | 6   | $7500 | 60     | [2]     |

[1] Use lower DR against crushing attacks.
[2] Considered metal for the purposes of armor modifiers, lightning damage, reaction penalties in town, etc.
[3] Flexible armour that can be worn under non flexible armour, with at least DR 3, to stack DR. When Layered split DR is ignored.

### Shields
**Defense Bonus (DB)**: is added to all of your active defense role from attacks to your front or shield side. This bonus is only applicable if the shield is readied. To ready or store a shield takes an amount of ready maneuvers equal to its DB.

| Shield        | DB  | Cost | Weight | Notes |
| ------------- | --- | ---- | ------ | ----- |
| Cloak         | 1   | 20   | 2      | [1]      |
| Small Shield  | 1   | $40  | 8      | [2,3] |
| Medium Shield | 2   | $60  | 15     | [2,3] |
| Large Shield  | 3   | $90  | 25     | [2,4] |

[1] Can be used offensively to Feint or grapple at reach C, 1 (but not for a shield bashing). Occupies a hand, and a failed block may endanger your arm.

[2] Can be used offensively, see Shield Bash on the melee weapons table. A spike that gives +1 to damage adds $20 to cost and 5 lbs. to weight.

[3] Also available as a buckler. You can ready a buckler with one Ready maneuver and drop it as a free action, like a weapon – but it occupies a hand, and can be dropped. No effect on statistics.

[4] Large shields get in the way: -2 to all attacks with the other hand (but not with the shield) unless you have Shield-Wall Training. In close combat, apply -3 for DB instead.
