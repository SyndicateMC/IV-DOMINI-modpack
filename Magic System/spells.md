# Spells for the Modpack
This file just contains ideas for spells that I want to add to the modpack. They will be catagorized based on the school they are a part of. I will give the gist of the themes of the spells, I may not follow them super closely just so there is more variety of spells.

Terms to note:
- DMG: normal damage.
- M-DMG: magic damage, pierces armor.
- HP: health, health points.

Additional notes:
- The spell rarity system has been changed:
  - **Common -> Common**
  - **Uncommon -> Rare**
  - **Rare -> Epic**
  - **Legendary -> Epic**
  - **Legendary -> Flawless**
- Again, no spell leveling.

## Physical
Physical spells usually have to do with effecting a physical action of the player (ie. a stomp, punch, swipe?), physically effecting terrain, forming physical barriers, or direct contact with something. Can also be associated with summoning storms and such.

<details><summary><b><ins>Stomp</ins></b></summary>

```
Stats:
- long cast
- 0.5s cast time
- 10s cooldown
- 2 arcana cost
- common

Info:
- Functions similarly to the stomp spell in base ISS.
- Does 8DMG.
```
</details>

<details><summary><b><ins>Slam</ins></b></summary>

```
Stats:
- instant cast
- 20s cooldown
- 2 arcana cost
- rare

Info:
- Adds downwards velocity to the caster.
- Gives the caster the Heavy effect for 10s.
  - Entities with the Heavy effect are given increased gravity and cannot take fall damage.
  - Any fall damage that would be taken is applied to all entities in a 1.5 block radius.
```
</details>


## Deathly
Deathly spells usually have to do with direct damage or direct healing. Can also be associated with summoning things to fight for you.

<details><summary><b><ins>Heal</ins></b></summary>

```
Stats:
- long cast
- 2s cast time
- 20s cooldown
- 2 arcana cost
- common

Info:
- Heals the player for 6HP.
- Gives off little green particles when cast.
```
</details>

<details><summary><b><ins>Healing Hands</ins></b></summary>

```
Stats:
- instant cast
- 30s cooldown
- 3 arcana cost
- rare

Info:
- Gives the player five charges to cast.
- When a charge is consumed, heal the closest entity that is within 7 blocks in front of you.
- Heals for 3HP.
- Gives off little green particles that shoot out in the direction it was cast.
```
</details>

<details><summary><b><ins>Bolt of Hurting</ins></b></summary>

```
Stats:
- instant cast
- 30s cooldown
- 1 arcana cost
- common

Info:
- Fires off a magic bolt that flies at a similar tragectory as an arrow.
- Deals 6DMG on contact with an entity.
- Dissapates on contact with a surface or an entity.
```
</details>

## Emotional
Emotional spells usually have to do with support. Like applying a buff to a friend, and applying a negative effect to a foe.

<details><summary><b><ins>Strengthen</ins></b></summary>

```
Stats:
- long cast
- 0.5s cast time
- 30s cooldown
- 2 arcana cost
- rare

Info:
- Gives the caster the Strength (I) effect for 20s.
- If targeting an entity, give the entity the Strength (II) effect.
```
</details>

## Orderly
Orderly spells usually have to do with some sort of imbuement, or maybe telekinesis. In the same vein as **Physical** magic, or complementary in a way.

<details><summary><b><ins>Gust</ins></b></summary>

```
Stats:
- instant cast
- 10s cooldown
- 1 arcana cost
- common

Info:
- Adds velocity to the caster in the direction they are looking in.
- Pushes away any entities near the caster by a little bit.
```
</details>

<details><summary><b><ins>Moonshot</ins></b></summary>

```
Stats:
- long cast
- 0.2s cast time
- 20s cooldown
- 2 arcana cost
- rare

Info:
- Cannot be cast without a target entity.
- Adds a bunch of velocity to the entity the caster is targeting, sending them in the direction the caster is facing.
- Makes the target entity able to be effected by kinetic damage.
  - There's an effect in base ISS that does that. I forget what it is called.
```
</details>


<details><summary><b><ins>Tether</ins></b></summary>

```
Stats:
- long cast
- 2s cast time
- 1m cooldown
- 8 arcana cost
- legendary

Info:
- Cannot be cast without a target entity.
- Gives the caster and the target the effect "Tethered".
  - Tethered entities will share any damage they recieve, divided by the amount of tethered entities.
    - X = A / B; where A is the initial damage that would be applied to an entity with the Tethered effect, B is the amount of entities with the Tethered effect, and X is the damage all entities with the Tethered effect would recieve.
```
</details>
