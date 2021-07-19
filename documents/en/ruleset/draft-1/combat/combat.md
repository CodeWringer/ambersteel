# Combat
This section describes the rules and mechanics of combat. 

## Start of Combat
At the beginning of every combat encounter, the involved parties must roll for [initiative](combat-attributes#Initiative-[Ini]). Character's get to act in the reverse order of the value rolled. That means that higher values get to go first. 

If one party is surprised, the ambushing party gets to act for a full round, without initiative being rolled. This is called a *surprise round*. After the surprise round, initiative is rolled and combat begins as explained above. 

A party is considered surprised if they were unaware of their opponents when the first attack roll happens. 

As an example: this does not count for opponents standing right in front of each other in friendly conversation, when one of them suddenly draws a dagger and attacks. The attacker can be clearly seen by the attacked and thus they must both roll for initiative, to determine whether the attacked can react in time. 

## Attack
An attack roll follows this procedure:
1. The attacker subtracts their weapon's stamina cost from their [stamina points](combat-attributes#stamina-points-[sp]). 
1. The attacker rolls 1d20 (disadvantaged, if [overexerted](status-effects#overexerted)). 
1. If their used weapon is based on [dexterity](../attributes#dexterity-[dex]), they must also add or subtract their [precision modifier](combat-attributes#precision-[Prec]) value.
1. At this point, the defender has to decide on whether to try and [parry](combat-attributes#parry), [dodge](combat-attributes#dodge) or allow the hit uncontested. 
1. If they decide to parry or dodge, they must subtract the respective dodge or parry cost from their [stamina points](combat-attributes#stamina-points-[sp]) and also roll 1d20. Depending on which form of defense they picked, they must then add or subtract the according parry or dodge modifier value. If their final value is higher than the attacker's, the attack is ended and no damage dealt. 
1. If the defender achieves a critical success for a parry, they get to [riposte](combat-attributes#riposte). 
1. If the defender's final value is lower than the attacker's, the attacker gets to roll for damage. For that, they roll the damage for the damage type(s) of their choice and availability. 
1. If the attacker's weapon is based on [strength](../attributes#strength-[str]), the attacker must also add or subtract their *strength modifier* value for each of their weapon's damage types marked with (+ [Str-Mod](../attributes#strength-[str])). 
1. The defender's [protection](armor#protection) reduces the damage, resulting in the final damage value that is then applied to the defender's health points. 
1. If the attacker's chosen damage type is of an armor damaging type, the defender must also reduce their armor's [condition points](armor#condition) by 1. 
1. Lastly, the defenders [stamina points](combat-attributes#stamina-points-[sp]) are reduced by the amount of stamina damage the attacker's weapon deals. 

## Ranged Attack
Ranged attacks behave just like regular attacks, with the exception that there can be no [parry]() or [riposte](combat-attributes#riposte) made with them. 

A ranged weapon's reload speed governs how often an attack can be made with it. In order to reload, a weapon-specific number of the specified type of actions need to be spent. 

As an example, if the reload cost is 1 [standard action](combat-actions#standard-action), a character can choose to convert their movement action to a standard action, spend that to reload and then spend their regular standard action to shoot. 

Ranged weapons can be effectively used up to their effective range. Exceeding that range, a ranged attack incurs [disadvantage](../dis-advantage#disadvantage) and, at the game master's discretion, penalties to the value rolled. 

An example ruling could be a penalty of -2 for every additional range step past the effective range. As an example, with a weapon, that has an effective range of 'short', but wanting to shoot 'far', a character incurs a penalty of -4 for their attack roll.

Alternatively, a projectile could simply 'fall short', making it physically impossible to shoot past the effective range. 

### Throw attacks
Throw attacks behave much like ranged attacks, with the exception that the effective range depends on both the weight of the object or weapon thrown, as well as the strength of the character. 

In order to determine a thrown weapon's potential reach and damage, proceed as follows:
1. Roll 1d10
1. Add or subtract the character's [strength modifier](../attributes#strength-[str]) to/from the value rolled. 
1. Multiply the rolled and summed value with the according distance multiplier from the table below. This is how far the object can - but doesn't _have_ to - be thrown in this attempt. 
1. Multiply the rolled and summed value with the according damage multiplier from the table below. This is the total damage caused by the thrown object. 

| Object Weight | Distance Multiplier | Damage Multiplier |
| -- | -- | -- |
| Light      | 4m (13')   | 1 blunt |
| Medium     | 3m (10')   | 2 blunt |
| Heavy      | 2m (6.5')  | 3 crush |
| Very Heavy | 1m (3')    | 4 crush |

All of this requires the game master's judgement. They may overrule the throwable distance, as well as the damage and the type of damage caused. 

Weapons intended to be thrown may provide further specifics, such as, which damage or distance multiplier to use instead.

## Aimed Attack
An attack generally targets the center of mass (torso) of the targeted opponent. 

It is, however, possible to call out wanting to attack a specific part of an opponent's body. Generally, this means that the attack must be rolled with [disadvantage](../dis-advantage#disadvantage). However, the game master can also decide the part being targeted is fairly easy to hit, either generally or due to current circumstance, so no disadvantage is incurred. 

A player may call out what effect the aimed attack is supposed to have, such as limiting their opponent's ability to stand, move, attack or whatever else the body part may be useful for. If they don't, the game master decides the negative effect. 

## Difficult Attack
There may be attacks that are more difficult to perform, due to current circumstance. Such attack rolls are [disadvantaged](../dis-advantage#disadvantage). 

An example for a *difficult attack* would be targeting an opponent with a ranged weapon when the opponent is behind cover. 

Another example would be attacking backwards, at an invisible enemy or with a broken arm, and so on.

## Easy Attack
Opposite of the difficult attack, is the *easy attack*, which is [advantaged](../dis-advantage#advantage).

The following are generally considered easy attacks (but at the game master's discretion):
* From behind
* Against prone opponents
* Against restrained opponents

## Execution Attack
The extreme version of an easy attack, the *execution attack* allows outright killing or maiming an opponent, without having to roll for an attack or for damage. 

Such an attack can be carried out against any character who is unable to fight back (with the exception of player characters, see [death's door](combat-attributes#death's-door)). 

This kind of attack is always possible only at the game master's discretion. 

Examples for an execution attack would be a stealthed character slitting another's throat, without them being aware of their assailant, or a character restrained by chains and unable to avoid the attack at all, when their assailant pushes their spear through their heart. 

## Zone of Control (ZoC)
The immediate area around a character is considered their zone of control (ZoC). 

Other characters can freely go inside other characters' ZoC. However, trying to leave a ZoC allows for an *attack of opportunity* on them by the owner of the ZoC. 

An *attack of opportunity* behaves much like a regular attack, except that it occurs not during the turn of the character whose zone of control it is. 

What's more, the character with a chance for an *attack of opportunity* can decline to make the attack. After all, it's usually not a good idea to attack your ally leaving your ZoC, _just because you could_. 

## Turns
TODO

## Critical Success / Failure
When a 20 is rolled, an attack or defensive action is considered a critical success. A critical success cannot fail. 

This means that an attack roll of 20 makes a defensive roll irrelevant, as the attack in question simply cannot be defended against. 

For a critical success for an attack, all damage dealt (except stamina damage) is doubled. For this, damage does not get rolled twice and then summed, but only rolled once and then simply doubled. 

If parrying, a critical success also allows for an immediate counter-attack, which costs no additional stamina for the counter-attacker. 

If dodging, the dodge in question costs no stamina for the defender. 

On the other hand, when a 1 is rolled, an attack or defensive action is considered a critical failure. 

A critically failed attack cannot hit an opponent and may instead result in any negative course of action for the attacker, that the game master sees fit in the given situation. This may range from them getting knocked off-balance, their weapon getting stuck in furniture or perhaps them opening themselves up for a free counter-attack by their opponent. 