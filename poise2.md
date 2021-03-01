---
description: An explanation of the Poise system in Genshin and how stagger works
---

# Poise

{% hint style="info" %}
If you come across any unknown terms, there is a section in the [glossary](../../common-terms.md#poise) dedicated to terms used for poise mechanics.
{% endhint %}

## How to Stagger an Enemy

1. Reduce **Poise** to 0, which will put the enemy into the **vulnerable** status
2. Attack the enemy, **staggering** them
    Different stagger levels exist for the various force of attacks that trigger the stagger
3. Vulnerable status ends, and the poise bar is reset

## Poise

All units have a hidden poise bar which decreases when receiving attacks that deal "poise damage". When the poise bar is depleted to 0, the unit becomes "vulnerable".

$$
Actual Poise Damage = Poise Damage * Vulnerability
$$

### 
Factors that affect Poise

Different enemies/characters have different poise, vulnerability, and poise regeneration

* > A Cryogunner has more poise, vulnerability, and poise regen than a normal Hilichurl

  > A melee character has more poise, vulnerability, and poise regen than a ranged character

Some attacks or abilities can change vulnerability.

* > The vulnerability when a Cryogunner is generating their shield is less than when the Cryogunner is spraying

  > “Increasing resistance to interruption” skills take effect via decreasing vulnerability. The same goes for shields.

The number of teammates in co-op mode will increase poise or decrease vulnerability

### Factors that affect Poise Damage

Different attacks/skills have different poise damage

* > Zhongli’s skill does more poise damage than his N1

Poise damage can change depending on the character's status

* > The poise damage of Xiao’s plunges increases after activating his burst

Large level differences can reduce poise damage

* > A low-level Kaeya can't knock back a level 89 Cicin Mage with his E, but a level 50 Kaeya can.

Poise damage can stack when petrified by Zhongli’s burst, but not when frozen

## The Vulnerable Status

A status that occurs when a unit's poise bar is 0. The next attack received by a vulnerable unit may stagger them depending on the level of the stagger.

* If an attack has enough force, the attack can both set the target’s status to vulnerable and stagger the target in one.

### About the Vulnerable Status:

Different enemies/characters have different vulnerable durations

* > The duration of a Cryogunner's vulnerable status is less than a normal Hilichurl’s

  > The duration of a melee character's vulnerable status is less than a ranged character
  's

When the vulnerable status ends, the poise bar is reset to its default value

During the stagger animation, an enemy is still considered vulnerable. Meaning, you can attack an enemy in the stagger animation to override the previous stagger level.

* > C4 Bennett uses charged level 1 E, causing a Stonehide Lawachurl to be staggered at level 4. Bennett then performs an additional attack, causing the Level 4 stagger animation to turn into a Level 2 Stagger.

## Stagger Levels

When a target is in the vulnerable status, the next attack received by a vulnerable unit may stagger them depending on the level of the stagger.

* Level 0: Nothing happens after being hit.
* Level 1: The enemy will shake a bit after being hit.
* Level 2: The enemy will be pushed back short to medium distance
* Level 3: The enemy will be thrown through the air a medium to long distance.
* Level 4: The enemy will be thrown into the air and spun.

## Force

### Factors that affect Force

For the object exerting the force

* The **strength and direction** of the force is affected by the level of the character/enemy and the talent used
  * > A low-level Venti can’t throw normal hilichurls into the air with his Q

    > Bennett can use his charged level 1 E to cause a level 4 stagger on Stonehide Lawachurls, while Venti can’t do this with his E.

For the object applied with the force

* **Mass**
  * > After using Ventis’s E, a hilichurl is thrown into the air and falls slowly, while an Anemoboxer falls quickly.

    > After using Kaeya’s E, a hilichurl is knocked back a large distance, while a cryogunner is only knocked back a small step
* **Drag Force**
  * > Chongyun’s N1 can stagger a Mitachurl at level 4 in the center of Venti’s burst, but can’t when a Mitachurl is standing on the ground. This indicates that the ground exerts a drag force.

    > Ningguang’s charged attack with 2 star jades can only cause a level 2 stagger on an Anemoboxer standing on the ground, but can cause a level 3 stagger on an Anemoboxer standing on the edge of a meteorite cast by Geo MC

## External Links

* [Genshin Impact Fandom](https://genshin-impact.fandom.com/wiki/Poise)

**Evidence Vault**

{% page-ref page="../../evidence/mechanics/combat/poise.md" %}
