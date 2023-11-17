# Combat
Combat proceeds in rounds. A round lasts one second. Each round, characters act in the order of their Basic Speed. Each player then chooses a Maneuver for their character from the following list. Most characters can make only one maneuver each round.
## Maneuvers
### Basic Maneuvers
**Move**: Use this maneuver to take Full Movement.

**Attack**: Attack an enemy with a ready weapon. A successful attack requires a success roll against your effective skill with the weapon. If you succeed the target must then fail to Defend (see active Defense below). The exception is if the enemy does not know you are there they do not get to defend, e.g. an attack from behind. As part of your Attack you may Step.

**Aim**: This maneuver can only be used with ranged attacks. Aim at a specific, visible enemy or point. If you attack your target with the same attack on your next turn, you may add your attack's Acc bonus to your effective skill – but if you lose sight of your enemy, make an Active Defense, change targets or change weapons, the bonus is lost. As part of your Aim you may Step.

**Ready**: used for any predominantly physical activity not covered by another maneuver. Use this Maneuver to draw a weapon, pick something up, or load a ranged weapon. Some actions require multiple or even concurrent readies, such as retrieving a potion from you backpack. As part of your Ready you may Step.

**Concentrate**: Focus on a primarily mental task - Spellcasting, non combat skills, or activating an ability that requires this maneuver. If the activity takes successive Concentration you become distracted when: taking damage, making an Active Defense roll, being shoved, or making a resistance roll. You must make a Will roll at -3, failure means you lose your concentration. As part of Concentrate you may Step.

**Free Actions**: Free actions can be performed at any time and do not take up the character’s turn. The most common free actions are to drop something and to talk.
### Advance Maneuvers
**All-Out Attack**: Sacrifice the ability to make any Active Defenses till your next turn to make an attack with full might. Specify one of the three options below when choosing this maneuver with a melee weapon.
 **Determined**: Make one attack with a +4 to hit. 
 **Double**: Make two attacks against the same foe, if you have two ready weapons or one that doesn't have to be readied after use.
 **Strong**: Make one attack. If you hit you get +2 to damage or +1 per die.
If you All-Out Attack with a ranged weapon you instead get +1 to hit.
As part of your All-Out Attack you gain Half Movement.

**All-Out Defense**: Spend all you effort on defending yourself. Specify one of these options when you choose this maneuver.
 **Increased Defense**: Add +2 to one active defense of your choice: Dodge, Parry, or Block. This bonus persists until your next turn.
 **Double Defense**: If you fail a defense roll against an attack, you may try a second, different defense against the same attack; e.g., if you fail a dodge, you may try a block or a parry. If you fail a parry (armed or unarmed) with one hand, a parry using the other hand does qualify as a “different defense.”
As part of your All-Out Defense you gain Half Movement.

**Move and Attack**: Gain full Movement and then attack with a -4 to hit to a maximum effective skill of 9.

**Wait**: Do nothing unless an event you’ve specified in advance occurs before your next turn. Specify the Maneuver and the specific trigger. You gain the movement of the prepared Maneuver which may be taken immediately or once triggered but cannot be split.

#### Attack options
Brace
Deceptive attack
Dual weapon attack
Rapid strike
Stop thrust

## Active Defense
These are defensive maneuvers used on the enemy's turn to prevent him from hitting. After a successful attack the target may attempt any one Active Defense, as long as they are aware of the attack.

**Dodge**: Your dodge skill is equal to your Basic Move + 3. If you make a success roll against this number, you dodge the attack. You may dodge any type of attack and there is no limit to the number of different attacks you can dodge in a turn, but you must be aware of the attacks. Your Dodge skill may be affected by how much you are carrying; see the Equipment section.

**Parry**: To parry, you must have a ready weapon. Your parry skill is equal to half your skill with the weapon you are parrying with +3. Make a success roll against this number and you have parried the attack. You may only parry melee attacks, thrown weapons, or attack and spells that specify they can be parried. Once you’ve attempted a parry with a given weapon or hand, further parries with that weapon or hand have a cumulative -4 per parry after the first.

**Block**: To block, you must have a readied shield or cloak. Your block skill is equal to half your skill with the shield + 3. Make a success roll against this number and you have blocked the attack. You can block any melee or ranged attack, but further blocks suffer a cumulative -5 penalty.

#### Defense options
Retreat
Dodge and drop
Acrobatic dodge
Sacrificial dodge

## Movement
Each maneuver allows for a different amount of movement based on your Basic Move. The three types of Movement are as follows.

**Full Movement**: Move a number of hexes equal to your Basic Move. Alternatively spend half your movement to shift from Prone to Kneeling or from Kneeling to Standing (for more details see Posture, p. XX).

**Half Movement**: Move a number of hexes equal to half of you Basic Move rounded up. Alternatively shift from Prone to Kneeling or from Kneeling to Standing.

**Step**: Move 1 hex. Alternatively you may Stand up from Kneeling.
## Facing
Whenever you have at least a step of movement you may shift your facing freely. You must always face toward one of the six hexes adjacent to your hex. Your facing defines your front, right, left, and back hexes (see illustration). Active defenses suffer a -2 when defending from the side and it is impossible to defend from the back. You may only attack into your front hexes.

![Facing](https://github.com/HeringtonPress/HeringtonPress.github.io/assets/93562930/446fa56c-2cea-482e-b27c-1c9589aa7dd0)

## Posture
**Prone**
While prone you have a movement of 1. You have a -4 to hit with melee attacks. You have a -3 to Active Defense. ranged attacks have a -2 to hit you.

**Kneeling**
While kneeling you have 1/3 movement to a minimum of 1. You have a -2 to hit with melee attacks. You have a -2 to active defense. ranged attacks have a -2 to hit you.

**Standing**
While standing you are unpenalized.
# [Advanced Combat](Combat/AdvancedCombat.md)

# Damage, Health, and Recovery
**Damage**: Damage is almost always ST-based and expressed as a modifier to the wielder’s basic thrusting (thr) or swinging (sw) damage, from the Damage Table (Character Creation). For example, a spear does “thr+2,” so with ST 11 and therefore a basic thrusting damage of 1d-1, you’ll inflict 1d+1 damage with a spear.

A parenthetical number after damage – e.g., (2) – is an armor divisor. Divide the target’s DR by this number before subtracting it from your damage. For instance, an attack with a divisor of (2) would halve DR.

Each damage rating is followed by an abbreviation indicating damage type:

| Abbreviation |      Type      | Wounding Multiplier |
|:------------:|:--------------:| ------------------- |
|      cr      |    crushing    | x1                  |
|     cut      |    cutting     | x1.5                |
|     imp      |    impaling    | x2                  |
|     pi-      | small piercing | x0.5                |
|      pi      |    piercing    | x1                  |
|     spec     |   see notes    |                     |

Any damage that penetrates DR is multiplied by the damage type's Wounding Multiplier. A victim loses HP equal to this new sum.

A successful attack always does at least 1 point of damage (before DR).

**Hit Points**: You do not automatically die at 0 HP, but every turn thereafter you must make a success roll against HT, with a -1 for each multiple of negative HP. Failure means you instantly pass out.

If you reach the end of an encounter and are still below 0 HP make an HT roll -5. On a success no further rolls are needed till you receive damage again, on a failure you pass out.

If you reach a negative multiple of your HP, you must immediately make an HT roll. On a failure of 3 or more you die. If you fail by 2 or less you are "Mortally wounded".

While Mortally Wounded you must make an HT roll every half hour or die. If you critically succeed on this roll you recover miraculously. If someone is tending to you, you can make a roll against their First Aid or Medicine skill instead but this requires that they be with you the full half hour. It takes an hour and a roll against Medicine -3 to stabilize someone who is Mortally Wounded. Magical healing does not work while you are Mortally Wounded, unless specified.

If you reach -5xHP you die instantly, -6xHP your body is destroyed.

**Recovery**: A character with the First Aid skill can make a success roll to attempt to heal an injured character (don't forget equipment modifiers.) This requires one minute and restores 1 HP if successful. If the caregiver continues to care for the wounded character for another 30 minutes, the wounded character recovers 1d-2 HP (minimum 1) *instead*.

Further healing requires rest. At the end of each day of rest, make a success roll against HT. On success, the character regains 1 HP for every 10 points of max HP (minimum 1).

Characters that fell unconscious automatically wake up 15 minutes after their HP becomes positive. Or an hour after receiving First Aid.

**Fatigue points** can be recovered at a rate of 1 per ten minutes of rest.
