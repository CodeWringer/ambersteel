# Attributes
Attributes describe a character's basic, inherent abilities.

Value range: 1-20

## Physical Attributes
These numbers represent a character's basic physical abilities. 

### Strength [Str]
Affects the damage dealt in combat and the ability to lift and throw objects or to break objects. 

The following table outlines the dice to roll for successful attacks. A dice count prefixed with '-' indicates a penalty, meaning the result of the roll will be subtracted, as opposed to added. 

*Strength modifier* is abbreviated as *Str-Mod*.

| Strength | Strength Modifier |
| -------- | ----------------- |
| 1        | -5                |
| 2        | -4                |
| 3        | -3                |
| 4        | -3                |
| 5        | -2                |
| 6        | -2                |
| 7        | -1                |
| 8        | -1                |
| 9        | 0                 |
| 10       | 0                 |
| 11       | 0                 |
| 12       | 1                 |
| 13       | 1                 |
| 14       | 2                 |
| 15       | 2                 |
| 16       | 3                 |
| 17       | 3                 |
| 18       | 4                 |
| 19       | 4                 |
| 20       | 5                 |

### Dexterity [Dex]
Determines how dexterous a character is. Any action that requires a character to move very precisely, will require dexterity. 

Affects their [precision](combat/combat-attributes#Precision-[Prec]) during combat, as well as the ability to [dodge](combat/combat-attributes#Dodge) out of the way of attacks. 

### Endurance [End]
Governs how long a character can endure physical strains. 

Determines the stamina points available to a character, as well as the amount recovered, when [taking a breather](combat/stamina#taking-a-breather). 

Each point in endurance awards 2 points in stamina. 

Every 2 points in endurance awards 1 point of stamina regeneration per turn. 

### Constitution [Con]
Governs the toughness of a character. Determines the health points a character has. Also governs a character's poison resistance. 

Each point in constitution awards 5 hit points. 

### Speed [Spd]
Governs a character's movement and reaction speed.

A character can move up to their speed in meters (speed * 3 feet) and at least 1 meter (or 3 feet). 

When in difficult terrain, movement costs double for each meter (3 feet) of travel through difficult terrain. 

### Perception [Perc]
Governs a character's ability to pick up on fine details in their environment, on objects and other characters and to see under difficult conditions such as dim light and light fog. 

## Mental Attributes
These numbers represent a character's basic mental abilities. 

### Intelligence [Int]
Governs a character's ability to reason and analyze. 
Also affects a character's speed of learning. 

### Wisdom [Wis]
Governs a character's understanding of and ability to recall knowledge. 

### Arcana [Arc]
Governs a character's ability to control magic flow, sense magic and withstand magic-exertion effects. 

Also used to resist negative magic effects. 

## Social Attributes
These numbers represent a character's basic social abilities. 

### Will [Will]
Governs a character's ability to withstand persuasion, intimidation, charm or terror. 

### Oratory [Ora]
Governs a character's ability to convincingly speak with and before others. 

### Empathy [Emp]
Governs a character's ability to read and understand another's emotions and intentions. 

# Combat Attributes
These attributes govern a character's combat-relevant attributes. 

## Initiative [Ini]
Initiative dictates the order in which the characters take their turns in combat. A higher initiative results in a character acting earlier during the turn. 

Initiative is determined at the start of a combat encounter. Roll a d20 and add the character's initiative modifier. 

A character's initiative modifier is determined by summing every point of [speed](../attributes#speed-[Spd]) and [perception](../attributes#perception-[perc]) above 10, dividing that value by two and rounding down. 

An example: A character has a speed of 12 and a perception of 15. Summing the attribute points above 10 yields a value of 7 (that is 2 speed + 5 perception). Half of that, rounded down, results in 3, which is the final initiative modifier for that character. 

If two character's get the same initiative value, have both roll again. Whoever rolled higher this time, gets to act before the other. Their originally rolled initiative roll remains unchanged. This rule is supposed to help break ties, not completely topple the just established initiative order. 

Value range: 0 - 10

## Precision [Prec]
Governs a character's ability to circumvent an opponent's defense in combat. 

A character's precision determines their *precision modifier* value, which acts as either a bonus, or a penalty, to their attack rolls. 

The following table outlines the precision modifier values, based on a character's [dexterity](../attributes#dexterity-[dex]) vlaue. A value prefixed with '-' indicates a penalty, meaning the value must be subtracted, as opposed to added. 

*Precision modifier* is abbreviated as *Prec-Mod*.

| Dexterity | Precision Modifier |
| --------- | ------------------ |
| 1         | -5                 |
| 2         | -4                 |
| 3         | -3                 |
| 4         | -2                 |
| 5         | -1                 |
| 6         | -1                 |
| 7         | 0                  |
| 8         | 0                  |
| 9         | 0                  |
| 10        | 1                  |
| 11        | 1                  |
| 12        | 2                  |
| 13        | 2                  |
| 14        | 3                  |
| 15        | 3                  |
| 16        | 4                  |
| 17        | 4                  |
| 18        | 5                  |
| 19        | 5                  |
| 20        | 6                  |