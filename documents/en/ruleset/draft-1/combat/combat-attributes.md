# Combat Attributes
These numbers represent a character's base attributes relevant to combat. 

## Health Points [HP]
When a character's health points reaches 0, that character dies. 

An exception is made for player characters, who instead become unconscious and are brought to *death's door*. 

Value range: variable; typically 0-100 for a player character. 

### Death's door
A __player character__ whose health is 0, is considered at *death's door* and is very close to death. 

A player character must make a *death saving throw* at the beginning of each turn of combat, until they either achieve a critical success roll or are healed. A critical success will bring a player character back up to 1 health point and remove the unconscious status. 

A *death saving throw* is made by performing a [constitution](../attributes#constitution-[con]) attribute check. 

Additional damage received by the player character, after the point of dropping to 0 health points, will force the player character to make additional *death saving throws* for each time they are hit. The additional damage incurred is irrelevant. 

Should a player character fail their *death saving throw* three times, they die. 

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
| ---- | ---- |
| 1  | -5 |
| 2  | -4 | 
| 3  | -3 | 
| 4  | -2 | 
| 5  | -1 | 
| 6  | -1 | 
| 7  | 0  | 
| 8  | 0  | 
| 9  | 0  | 
| 10 | 1  | 
| 11 | 1  | 
| 12 | 2  | 
| 13 | 2  | 
| 14 | 3  | 
| 15 | 3  | 
| 16 | 4  | 
| 17 | 4  | 
| 18 | 5  | 
| 19 | 5  | 
| 20 | 6  | 

## Parry
The ability to deflect blows and even riposte off them, gaining an attempt at a counter-attack. 

A character's *parry modifier* is determined by summing every point of [strength](../attributes#strength-[str]) and [perception](../attributes#perception-[perc]) above 10, dividing that value by two and rounding down. 

An example: A character has a strength of 12 and a perception of 15. Summing the attribute points above 10 yields a value of 7 (that is 2 strength + 5 perception). Half of that, rounded down, results in 3, which is the final parry modifier for that character. 

Also used with a shield to block projectiles and other attacks that could reasonably be deflected by a shield. 

Whenever a character is attacked, they may make an attempt to parry it. A parry attempt will cost stamina, based on the weapon parry costs. If parrying with a shield, its stamina cost will be used, instead. 

A weapon much heavier than the weapon being parried with, will force disadvantage on the defender. 

### Riposte
Rolling a critical success on a parry allows a character to counter-attack (*riposte*) __immediately following__ the successful parry. 

## Dodge
Governs a character's ability to avoid being hit by an opponent's attack or a sprung trap mechanism. 

A character's *dodge modifier* is determined by summing every point of [dexterity](../attributes#dexterity-[dex]) and [speed](../attributes#speed-[spd]) above 10, dividing that value by two and rounding down, then subtracting 1 point for every two points of [encumbrance](armor#Encumbrance).

An example: A character has a dexterity of 16, a speed of 14 and an encumbrance of 5. 
Summing the attribute points above 10 yields a value of 10 (that is 6 dexterity + 4 speed). Half of that, rounded down, results in 5. For the five points of encumbrance, a penalty of 2 is applied, resulting in the final dodge modifier of 3. 

Another example: A character has a dexterity of 12, a speed of 13 and an encumbrance of 6. Summing the attribute points above 10 yields a value of 5 (that is 2 dexterity + 3 speed). Half of that, rounded down, results in 2. For the six points of encumbrance, a penalty of 3 is applied, resulting in the final dodge modifier of -1. 

Can be disadvantaged, when there is only little room to maneuver or if the character is in difficult terrain. 

A dodge attempt costs 2 (+ [AsP](armor#Encumbrance)) stamina. 